# NewBx RenderDragonShaderLoader Variant

This repository is a fork of
[devendrn/newb-x-mcbe](https://github.com/devendrn/newb-x-mcbe). The default
`rdloader-variant` branch is a complete shader pack for RenderDragonShaderLoader.

## Upstream

- Original project: [devendrn/newb-x-mcbe](https://github.com/devendrn/newb-x-mcbe)
- Original author: devendrn
- Upstream version: Newb X Legacy `v16.56`
- Source license: MIT, preserved in [LICENSE](LICENSE)
- Compiled-pack notice: [COPYRIGHT.txt](COPYRIGHT.txt)

## Variant Changes

- Adds RenderDragonShaderLoader pack metadata (`options.json`, `rdloader.pack.json`,
  `variants.json`, and project profiles).
- Adds 87 parameters with Chinese and English display names under `lang/`.
- Maps selected NewBx controls to RenderDragonShaderLoader runtime uniforms.
- Converts NewBx cloud/fog subpacks into eight selectable variants.
- Includes 13 precompiled Windows material outputs.
- Flattens the source tree so GitHub's generated code ZIP can be imported directly.

## Compatibility

- Target game: Minecraft Bedrock `1.26.51`
- Required mod: RenderDragonShaderLoader `0.2.0-beta` or later
- Precompiled backend: shaderc / Direct3D_SM50

## Installation

1. Install RenderDragonShaderLoader.
2. Open the repository's default branch.
3. Click **Code > Download ZIP**.
4. Import the downloaded ZIP into the mod.
5. Select the `Default` configuration and apply it.

The repository package already contains compiled materials. A normal installation does not
need to run the shader compiler again.

## Licensing

The NewBx source is copyright (c) 2024 devendrn and licensed under MIT. The original compiled
resource-pack notice is preserved in [COPYRIGHT.txt](COPYRIGHT.txt). It states that compiled
packs distributed by the original project use CC BY-ND 4.0, while a result compiled from the
MIT-licensed source may be distributed under the compiler's own terms.

This variant was compiled from the MIT-licensed source with RenderDragonShaderLoader
compatibility changes. Attribution to the original project is preserved.

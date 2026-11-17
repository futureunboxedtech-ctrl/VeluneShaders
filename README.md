LUMINA SHADERS v19  -  for Minecraft Java (Iris + Sodium)

REQUIRED
  - Iris matching your Minecraft version (for 26.2: Iris 1.11.4+26.2 or newer) + Sodium 0.9.x
  - Fabric API (Fabric only)
  - Video Settings -> Graphics API must be OpenGL (Iris does not support Vulkan)

INSTALL
  1. Put LuminaShaders_v19.zip (do not unzip) in  .minecraft/shaderpacks
  2. Delete older Lumina zips/folders so you are sure which one is selected
  3. Video Settings -> Shader Packs -> LuminaShaders_v19 -> Apply  (press R in that menu to reload)

THE END
  Black hole ("Gargantua"):
    - Exact Schwarzschild light paths are integrated per pixel. The black shadow, the thin photon ring and
      the accretion disk bent over the top and under the bottom of the hole all come out of the physics.
    - Disk: inner edge at the innermost stable orbit (3x the horizon radius), Keplerian shear, relativistic
      Doppler beaming + gravitational redshift (approaching side hotter/brighter, receding side redder).
    - It is the End's sun: the shadow map, the warm light and the object in the sky all point the same way.
    - Fully procedural: no textures are needed.
  Ringed planet:
    - Banded gas giant to the left of the black hole, lit from the black hole's side, with a ring system,
      a ring shadow on the planet and the planet's shadow on the rings. (v18: the tiny lensed "ghost" copy of
      the planet that used to appear beside the black hole has been removed.)
  Solar system (no Earth, no Moon), all lit by the black hole with their real colours:
    Mercury (cratered grey-brown), Venus (pale yellow-white cloud deck), Mars (rust red, dark regions, polar cap),
    Jupiter (cream/ochre bands + Great Red Spot), Saturn (pale gold, rings), Uranus (pale cyan),
    Neptune (deep azure, Great Dark Spot, white cirrus). Toggle: "End Solar System Planets".
  Settings: Weather, Clouds & Particles ->
    End Black Hole, End Ringed Planet, Black Hole Distance (lower = bigger), Quality (ray steps),
    Brightness, Disk Inclination, Disk Roll, "Black Hole = End Light Source".
  If the End has a moving day/night cycle on your version, turn "Black Hole = End Light Source" off to
  pin the black hole to a fixed direction (X/Y/Z sliders) - shadows then no longer follow it.

OTHER FEATURES
  Shadows (soft, coloured), volumetric god rays, SSR water with refraction/absorption, procedural clouds,
  sunsets, night sky with Milky Way / shooting stars / moon phases, rain puddles, fireflies near firefly
  bushes, coloured light bleed, Nether look, bloom, ACES tonemapping, FXAA, presets Low/Medium/High/Cinematic.

PERFORMANCE: lower Black Hole Quality / Shadow Resolution / God Ray Quality, or use the Low or Medium preset.
# VeluneShaders
This repository contains the source code of VELUNE Shaders, including its GLSL shader programs, rendering logic, configuration files and visual effects. It serves as the central place for source code access, development, version tracking and future updates. The project was developed with substantial assistance from generative AI.

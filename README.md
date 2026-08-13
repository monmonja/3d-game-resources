# 3D Game Resources

A collection of 3D game systems, procedural sandboxes, and modular web resources built for Three.js.

---

## [achrefelouafi/LinearAbiltyCastingThreeJS](https://github.com/achrefelouafi/LinearAbiltyCastingThreeJS)

A skillshot VFX sandbox built with Three.js, Vite, and GLSL shaders.

* Implements directional line casting and ground-targeted area casting mechanics
* Features real-time targeting indicators with dynamic cursor tracking and range clamping
* Demonstrates custom GLSL shader effects, signed distance fields, and GPU particle systems
* Provides a real-time parameter editor to tweak visual and simulation settings on the fly
* Includes skeletal character animation blending for ability casting

---

## [MengTo/towers](https://github.com/MengTo/towers)

An architectural procedural construction sandbox built with Three.js.

* Animates procedural tower construction from the ground up using a rising clipping plane
* Supports six distinct global architectural styles with parametric geometry generators
* Features real-time atmospheric transitions across multiple times of day and weather conditions
* Incorporates interactive camera orbit, lean, zoom, and timeline scrubbing
* Integrates procedural audio with regional traditional instrumentation and dynamic environmental soundscapes
* Operates entirely client-side with zero external build dependencies or network requests

---

## [Braffolk/fable5-world-demo](https://github.com/Braffolk/fable5-world-demo)

A fully procedural 4x4 km open world engine built with Three.js, WebGPU, TSL, and WGSL.

* Synthesizes 4x4 km open-world terrain with hydraulic and thermal erosion, flow rivers, and quadtree CDLOD meshing
* Generates all meshes, textures, foliage, and lighting procedurally at runtime with zero external asset files
* Renders using WebGPU pipeline with Three.js Shading Language (TSL) materials and raw WGSL compute
* Features GPU clustered-Poisson scattering and compacted indirect draws for dense vegetation and understory
* Enables deterministic open-world generation reproducible from a single seed URL parameter

---

## [thebuggeddev/empire](https://github.com/thebuggeddev/empire)

An interactive 3D atlas of historical domestic architecture built with React, Three.js, and GLTF.

* Displays interactive 3D domestic architecture models across eight historical empires
* Features a turntable stage with orbit, pan, zoom, wireframe modes, and x-ray sectioning
* Anchors 3D hotspot pins directly to model geometry for architectural annotations and camera focus
* Integrates interactive educational modules including lessons, historical timelines, and quizzes
* Utilizes a data-driven architecture for loading Draco-compressed glTF models and UI state

---

## [partisan-games/partisan-games.github.io](https://github.com/partisan-games/partisan-games.github.io)

A collection of retro arcade and 3D web browser games built with Three.js and HTML5 Canvas.

* Features a suite of open-source 2D and 3D browser games playable directly in the browser
* Includes 2D games and mechanics:
  * Tank Duel (2P): Two-player local 2D tank battle simulation
  * Destroy the Bunker!: Artillery demolition game targeting fortified positions
  * Moon Landing / Lander: Thrust-based flight navigation and landing physics simulation
  * Cannon Shooting: Physics-based artillery aiming and trajectory game
  * Avatar: 2D side-scrolling platformer game
* Includes 3D games and mechanics built with Three.js:
  * Savo Mitraljezac: First-person shooter (FPS) combat scene
  * Attack on Airport: First-person shooter action game
  * Graveyard Survival: Third-person shooter (TPS) survival game
  * Tank Driving: 3D vehicle physics and driving simulation
  * Warcraft / Golem Demo: 3D fantasy strategy and creature navigation demo
* Operates entirely client-side with zero installation requirements

---

## [steffenpharai/skyward](https://github.com/steffenpharai/skyward)

A persistent open-world sandbox inhabited by humans and autonomous AI agents, rendered with Three.js (TSL) and WebGPU.

* Renders a persistent procedural open world over an infinite heightfield using Three.js (TSL) and WebGPU
* Implements a regional land stewardship lifecycle enabling users and AI agents to claim, author, and curate frontier land
* Connects autonomous AI agents via Model Context Protocol (MCP), REST, and WebSockets to inhabit and build in the shared world
* Features procedural traversal mechanics including wall climbing, gliding, stamina management, resource gathering, and farming
* Operates a server-authoritative world model with persistent reputation, memory, and curation mechanics
# Hi, I'm Rohit Kulkarni 👋

### Gameplay Programmer · Unity Developer · Engine & Graphics Enthusiast

Gameplay programmer and Unity developer with **4+ years of shipped mobile-game experience** across iOS and Android. My work spans gameplay systems, Unity editor tooling, animation and inverse kinematics, multiplayer, runtime memory optimization, graphics programming, and engine-level development.

I have contributed to games reaching **1M+ and 50M+ installs**, led production teams, shipped features across multiple platforms, and built systems with Unity, C#, C++, Unreal Engine, OpenGL, Vulkan, DirectX, GLSL, HLSL, and ShaderLab.

📍 Atlanta Metropolitan Area, USA · Open to relocation

[Email](mailto:rohit.kulkarni.271197@gmail.com) · [LinkedIn](https://www.linkedin.com/in/rohitk11/) · [GitHub](https://github.com/rohitkulkarni97)

---

## What I Work On

- Gameplay systems, player interactions, AI, animation, and multiplayer features
- Unity architecture, editor tools, Addressables, and runtime optimization
- Engine and graphics programming in C/C++
- OpenGL, Vulkan, DirectX, GLSL, HLSL, and ShaderLab
- Tools and workflows that help designers and developers iterate safely
- Mobile release pipelines across Android, iOS, and Amazon Marketplace

---

## Professional Experience

### [Space Station 3D](https://github.com/RE-SS3D/SS3D)
**Volunteer Game Programmer — Unity / C#**  
*Dec 2025 – Present*

Open-source contributor working across Unity UI, gameplay-item systems, input handling, lifecycle correctness, networked Addressables, and asset architecture.

- Fixed Construction and Crafting menu layout inconsistencies and corrected category-selection behavior.
- Extended the clothing architecture with typed containers and per-body-part mesh handling.
- Resolved a Unity Input System conflict where `Ctrl+E` interactions unintentionally triggered a debug action.
- Proposed lifecycle corrections for gameplay and UI components by moving event subscriptions into their appropriate enable/disable phases.
- Profiled the project with Unity Memory Profiler and demonstrated that its legacy asset bootstrap retained approximately **600 MB** of assets at startup.
- Filed [issue #1494](https://github.com/RE-SS3D/SS3D/issues/1494) and drove an open [asset-system rewrite in PR #1500](https://github.com/RE-SS3D/SS3D/pull/1500).
- Replaced the static bootstrap with an asynchronous, reference-counted, disposable `AssetHandle<T>` architecture.
- Added load deduplication, last-reference unloading, lifecycle tracking, Edit Mode and Play Mode tests, and an interchangeable backend abstraction.
- Built supporting FishNet integration for networked Addressable prefabs, server/client preload coordination, deterministic prefab registration, and late-join safety.

[My SS3D fork](https://github.com/rohitkulkarni97/SS3D) · [Upstream repository](https://github.com/RE-SS3D/SS3D)

### Rochester Institute of Technology
**Teaching Assistant / Grader — IGME 235: Intro to Game Web Tech**  
*Aug 2024 – Dec 2024*

- Supported undergraduate students building browser-based and game-adjacent projects with HTML, CSS, JavaScript, DOM APIs, web APIs, local storage, and PixiJS/WebGL.
- Helped students debug event-driven logic, API-integration flows, loading and error states, and interactive web projects.
- Coached students toward identifying root causes instead of simply providing fixes.
- Graded assignments and projects for functionality, usability, code quality, polish, and requirement completeness.

### Dot9 Games
**Senior Software Developer — Unity / C#**  
*Apr 2023 – Aug 2023*

- Shipped features for [FAU-G: Domination](https://play.google.com/store/apps/details?id=com.dotnine.faug&hl=en_US), a 3D mobile PvP FPS with **1M+ Google Play installs**.
- Integrated Unity clients with internal APIs for storing and retrieving player data and gameplay records.
- Owned character-animation and inverse-kinematics systems for weapon aiming, foot placement, and hit-reaction blending.
- Integrated animation and IK systems with Photon Fusion so poses, aiming, and reactions synchronized correctly across multiplayer clients.
- Built a Unity Addressables memory-management system that reduced peak runtime memory by approximately **300–400 MB**.
- Enabled on-demand asset loading for a multiplayer game targeting lower-end mobile devices.

[Google Play](https://play.google.com/store/apps/details?id=com.dotnine.faug&hl=en_US) · [App Store](https://apps.apple.com/us/app/fau-g-domination-mp-season-4/id6741766030)

### Dot9 Games
**Software Developer — Unity / C#**  
*Sep 2022 – Apr 2023*

- Shipped [Ram Setu: The Run](https://play.google.com/store/apps/details?id=com.dotnine.ramsetu&hl=en_US), an endless runner released on Android and iOS with **500K+ combined installs**.
- Designed and implemented mini-games that added variety to the core endless-runner loop.
- Built an advertising system using Google AdMob with mediation-layer support.
- Worked with Unity Ads and ironSource integrations.
- Integrated Unity Addressables to reduce APK and IPA size by approximately **100–200 MB** and improve runtime memory use.
- Served as the sole engineer responsible for the complete iOS upload pipeline, including certificates, provisioning, TestFlight, and App Store submission.

[Google Play](https://play.google.com/store/apps/details?id=com.dotnine.ramsetu&hl=en_US) · [App Store](https://apps.apple.com/in/app/ram-setu-the-run/id1639509113)

### IDZ Digital Pvt. Ltd.
**Unity Developer — Unity / C#**  
*Jun 2019 – Jul 2022*

- Shipped 2D children’s games across titles that collectively reached **50M+ downloads** on Google Play.
- Contributed to [Tizi Princess Home Design Game](https://play.google.com/store/apps/details?hl=en_US&id=com.iz.tizi.royal.princess.dollhouse.life.games.home.design.world.my.wonder.town), which reached 50M+ installs, and [Tizi Town: My Space Games](https://apps.apple.com/us/app/tizi-town-my-space-games/id1475089280).
- Supported the shared production codebase used across multiple released Tizi applications.
- Investigated iOS crash reports and fixed a Metal API issue affecting lower-end devices.
- Used Firebase Analytics with design to identify engagement patterns and guide new interactive content.
- Implemented an ad-supported system that gave players temporary access to individual paid scenes.
- Led a **six-developer team** delivering a school-themed game across iOS, Android, and Amazon Marketplace.
- Assigned work, reviewed code, mentored developers, planned releases, and coordinated with product and design.
- Built a reusable Unity editor tool that codified common interactive-object patterns and reduced repetitive scene-authoring work.
- Integrated and maintained AdMob, Firebase Analytics, Unity Ads, ironSource, Unity IAP, Meta Ads, AppLovin, Unity Asset Bundles, and Kidoz.

[IDZ Digital on Google Play](https://play.google.com/store/apps/dev?hl=en-US&id=5953899060857093739)

---

## Projects

### [Warflux](https://github.com/rohitkulkarni97/Flux-TimesUp)
**Unity · C# · ShaderLab · HLSL · MS capstone**

A time-bending action game in which the world fractures with every action, challenging the player to restore time stability.

- Served as Producer, Gameplay Programmer, and System Architect on a cross-disciplinary team.
- Owned stakeholder and team communication throughout the two-semester production.
- Designed gameplay architecture around composable state, command, and observer patterns.
- Helped maintain a stable architecture while designers and programmers added new gameplay features.
- Developed across a project containing **1,060+ commits**.

### [Dynamic Duo](https://github.com/rohitkulkarni97/601-Dynamic-Duo)
**Unity · C# · ShaderLab · HLSL**

A couch co-op puzzle game in which two players work together to solve spatial and mechanical challenges.

- Served as Tech Lead and designed the gameplay systems used by the rest of the team.
- Built robust, efficient, and expandable systems for puzzle development.
- Structured features so designers could create and modify puzzle content without repeated engineering assistance.
- Shipped **five tagged milestone releases** across 162+ commits.

### AI for Gameplay Portfolio
**Unity · C# · HLSL**

A four-part portfolio covering movement, pathfinding, decision-making, and their integration into a playable game.

#### [Movement Behaviors](https://github.com/rohitkulkarni97/760-HW1-Movement)

- Implemented reusable seek, flee, arrive, wander, and align steering behaviors.
- Integrated the behaviors with Unity’s physics model.

#### [Pathfinding](https://github.com/rohitkulkarni97/760-HW2-Pathfinding)

- Built graph-based pathfinding across Unity scenes.
- Implemented grid and navigation traversal using Dijkstra and A* algorithms.

#### [Decision Making](https://github.com/rohitkulkarni97/760-HW3-Deicision-Making)

- Implemented state machines, behavior trees, and decision trees.
- Used layered decision logic to control AI agents.
- Added HLSL effects that visualized agent state.

#### [Top-Down Shooter](https://github.com/rohitkulkarni97/Top-Down-Shooter-760-AIG)

- Combined movement, pathfinding, and decision-making in a playable top-down shooter.
- Built agents capable of targeting, chasing, and attacking the player.
- Added custom HLSL hit flashes and target-highlighting effects.
- Developed the project across 73 commits.

### Game Production Portfolio
**Unity · C# · ShaderLab · HLSL · Agile/Scrum**

Team projects developed through formal sprints, milestones, issue tracking, reviews, and production workflows.

#### [Alien Platformer](https://github.com/rohitkulkarni97/603_G2_AlienPlatformer)

- Developed a team-based 2D Unity platformer.
- Shipped playable builds as part of the repository.
- Contributed to a project containing substantial ShaderLab and HLSL work.
- Developed across 134 commits.

#### [Data-Driven RPG](https://github.com/rohitkulkarni97/603_G5_DataDrivenRPG)

- Built a team RPG around a data-driven architecture.
- Represented stats, abilities, enemies, and progression through serialized data assets rather than hardcoded logic.
- Used an issue-tracked production workflow covering 19 issues and 105 commits.

### Graphics Programming Portfolio
**C/C++ · OpenGL · GLSL**

Four graphics projects built from scratch without a game engine.

#### [OpenGL Paint App](https://github.com/rohitkulkarni97/740_Assignment_1)

- Built a paint-style application directly in OpenGL.
- Implemented input handling, brush primitives, and framebuffer drawing.

#### [Character Rig in OpenGL](https://github.com/rohitkulkarni97/740_Assignment_2)

- Built a hierarchical character rig with parented transforms.
- Implemented articulated posing and animation using matrix mathematics and 3D transformations.

#### [Programmable Rendering Pipeline](https://github.com/rohitkulkarni97/740_Assignment_3)

- Implemented a programmable OpenGL rendering pipeline.
- Wrote custom GLSL vertex and fragment shaders for geometry, shading, and visual effects.

#### [Particle System](https://github.com/rohitkulkarni97/740_Assignment_4)

- Built a reusable OpenGL particle-system renderer.
- Separated the engine scaffold into camera, shader, shader-program, particle-system, and text modules.
- Organized GLSL source files into a dedicated shader pipeline.

### [Contra Remake](https://github.com/rohitkulkarni97/P797_G1_ContraRemake)
**Unreal Engine · C++**

An Unreal Engine recreation of the classic Contra arcade shooter.

- Built gameplay logic in C++ within a complete Unreal project.
- Worked across the project’s source, configuration, and Unreal build structure.
- Delivered the game as part of RIT’s IGME 797 production-studio course.

### [Minimal Engine](https://github.com/urvashi1206/GameEngineDesign)
**C++ · CMake · Ninja · vcpkg · Vulkan · GLSL**

A collaborative research project exploring the construction of a multithreaded, ECS-based game engine.

- Designed and implemented the rendering engine.
- Separated the renderer into a high-level interface and lower-level graphics API implementations.
- Targeted Vulkan as the primary low-level rendering API.
- Organized the codebase into separate ECS and Minimal Engine targets.
- Used CMake, Ninja, and vcpkg for the Windows build toolchain.

### Angry Birds Clone
**C/C++ · Sony PlayStation 5 SDK**

A solo four-level Angry Birds-style game built for PlayStation 5 development hardware.

- Worked directly with the PlayStation 5 SDK in C/C++.
- Built on course-provided rendering and controller scaffolding without middleware physics.
- Implemented a Unity-like object system and an ordered frame loop for input, gameplay, physics, engine updates, and rendering.
- Built custom 2D forces, collision detection and response, sprite rendering, geometry abstractions, and shader modifications.
- Investigated and corrected collision tunneling in high-speed projectile interactions.

*Source code is not publicly available because the project uses the proprietary PlayStation SDK.*

### Highway Rider Remake
**Unreal Engine · C++ · Procedural Content Generation**

A team recreation of the Highway Rider arcade game with original gameplay additions.

- Implemented procedurally generated highway sections with Unreal Engine’s PCG framework.
- Built spline-based vehicle-obstacle generation.
- Exposed tunable controls for vehicle density, spacing, and lane behavior.
- Combined Unreal PCG graphs with supporting C++ systems.

---

## Technical Toolkit

### Languages

`C#` `C` `C++` `JavaScript` `GLSL` `HLSL` `ShaderLab`

### Engines and Platforms

`Unity` `Unreal Engine` `PlayStation 5 SDK`

### Graphics and Engine Development

`OpenGL` `Vulkan` `DirectX` `Rendering Pipelines` `Shaders` `ECS` `CMake` `Ninja` `vcpkg`

### Gameplay and Production Systems

`Gameplay Architecture` `AI` `Pathfinding` `Behavior Trees` `State Machines` `Animation` `Inverse Kinematics` `Physics` `Procedural Generation`

### Unity and Multiplayer

`Unity Addressables` `Unity Input System` `Photon Fusion` `FishNet` `Unity Editor Tools` `Memory Profiler`

### Mobile and Services

`Android` `iOS` `TestFlight` `App Store Connect` `Firebase Analytics` `AdMob` `Unity Ads` `ironSource` `Unity IAP` `AppLovin`

---

## Education

### Rochester Institute of Technology
**Master of Science — Game Design and Development**  
*Aug 2023 – May 2025*

### University of Mumbai
**Bachelor of Engineering — Computer Science**  
*Jul 2015 – Jun 2019*

---

## Beyond Code

When I’m away from the keyboard, I enjoy:

- Playing guitar
- Listening to music
- Reading
- Working out
- Football
- Games that leave a lasting impression

---

## Let’s Connect

I’m open to opportunities involving:

- Gameplay programming
- Unity development
- Tools programming
- Engine development
- Graphics and rendering
- Game AI
- Multiplayer systems

[LinkedIn](https://www.linkedin.com/in/rohitk11/) · [Email](mailto:rohit.kulkarni.271197@gmail.com)

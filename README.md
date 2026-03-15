# Nicolas Mancone
**Gameplay & Systems Programmer**

📧 [nicolas.mancone11@gmail.com](mailto:nicolas.mancone11@gmail.com) &nbsp;|&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/nicolas-mancone-292497198/) &nbsp;|&nbsp; 📄 [Download CV](https://github.com/user-attachments/files/26008392/CV_Mancone_Nicolas.pdf)

I’m a Gameplay and Systems Programmer based in Rome. I'm currently finishing my studies at ITS Academy 'Roberto Rossellini', where I’ve spent most of my time digging into Unreal Engine 5. I’ve always been interested in what happens 'under the hood'—I don't just want to make things work, I want to understand the logic and the systems behind them. 

I mainly work with C++ and Blueprints, focusing on networking, AI, and physics-based logic. Right now, I’m looking for a Junior role or an internship to start my professional career in a dev team.

---

## 🛠️ Featured Projects

### ⏳ Chrono:Switch

> A first-person multiplayer puzzle-platformer built in **C++ and Unreal Engine 5.7**. The core mechanic revolves around two players collaborating across parallel timelines (Past and Future) to solve environmental puzzles through physics-based causality.

**My Roles & Responsibilities:**
* **$O(1)$ Collision Masking:** Developed a highly optimized modular framework where the Character handles timeline transitions by updating capsule responses to custom channels (`ECC_Past`/`ECC_Future`), bypassing heavy world-actor toggling.
* **Networked Async Physics:** Engineered stable, synchronized interactions for `CausalActor` objects across timelines, utilizing custom "spring" logic within the **Async Physics Tick** to ensure deterministic server-side consistency.
* **Movement Prediction & Correction:** Implemented robust client-side prediction, dynamically flushing the Character Movement Component (CMC) buffer during timeline shifts to prevent rubber-banding artifacts.
* **Game Direction & Visual State:** Designed the core mechanics and tied C++ logic directly to Material Parameter Collections (MPC), shifting the global color palette (Blue for Past, Orange for Future) and post-process lighting in real-time.

**Key Features:**
* $O(1)$ Timeline Switching | Async Physics Synchronization | CMC Prediction Validation

🔗 [View Repository](https://github.com/nicolas-mancone/ChronoSwitch)

---

### 🎭 Gala Nightmare

<a href="https://github.com/nicolas-mancone/Gala-Nightmare-Systems-Showcase">
<img align="left" src="https://github.com/user-attachments/assets/bca6691d-6677-44bf-b857-b841e6bb8498" alt="Gala Logo" width="350" style="margin-right: 20px;">
</a>

> Developed in 48 hours for the **Global Game Jam 2026** (Theme: "Mask"), *Gala Nightmare* is a 2-player local co-op action game. Players survive waves of enemies by collecting masks that grant unique abilities, leading up to a final PVP duel.

**My Roles & Responsibilities:**
* **Character & Movement:** Developing the core movement logic and local multiplayer framework for a seamless 2-player experience.
* **Animation-Driven Combat:** Implementing a hitbox system synchronized with sprite animations through **Anim Notifies**, ensuring frame-accurate combat logic.
* **Mask Power-up System:** Engineering the logic for collecting and swapping masks, including the real-time application of different combat stats and abilities.
* **Shared Camera & Input:** Building a dynamic camera system to keep both players in view and managing multiple gamepad inputs.

🔗 [View Repository](https://github.com/nicolas-mancone/Gala-Nightmare-Systems-Showcase)

<br clear="left"/>

---

### 🤖 ShapeKiller (AI State Tree)

<a href="https://github.com/nicolas-mancone/ShapeKiller">
  <img align="right" src="https://github.com/user-attachments/assets/3c1cb1a8-d4bf-4735-ab4e-885b146d99e0" alt="ShapeKiller State Tree Architecture" width="350" style="margin-left: 20px;">
</a>

> A stealth AI prototype developed to explore the capabilities of Unreal Engine 5's experimental State Trees and Environment Query System (EQS) within a dynamic "Prop Hunt" environment.

**My Roles & Responsibilities:**
* **State Tree Architecture:** Engineering a modular, hierarchical AI logic system using Linked Assets to seamlessly handle transitions between Routine, Investigation, and Chase states.
* **Predictive Pursuit (EQS):** Implementing an advanced seeking logic using EQS Cone Queries to simulate target trajectory prediction when the player breaks line-of-sight.
* **Designer-Friendly Tools:** Creating a highly customizable, component-based patrol system allowing level designers to dictate paths via Splines or Waypoints without touching code.
* **Context-Aware Detection:** Developing a scalable detection system driven by Gameplay Tags and Data Assets, adjusting AI suspicion rates based on player actions, distance, and zone types.

🔗 [View Repository](https://github.com/nicolas-mancone/ShapeKiller)

---

### 🦾 Technical Animation Prototype

<a href="https://github.com/nicolas-mancone/Technical-Animation-Project">
  <img align="left" src="https://github.com/user-attachments/assets/b636c62c-651c-4dd4-9d03-54fb3412bbd5" alt="AnimGraph Architecture" width="350" style="margin-right: 20px;">
</a>

> A student project developed to explore the core pipelines of Technical Animation and Data-Driven Systems in Unreal Engine 5, focusing on modularity and procedural adjustments.

**My Roles & Responsibilities:**
* **Animation Graph Architecture:** Designing a clean, modular AnimBP using Cached Poses and `Layered blend per bone` to seamlessly separate lower-body locomotion from upper-body combat actions.
* **Procedural Animation & IK:** Implementing procedural leaning via Additive nodes and applying **FABRIK IK** to ensure dynamic, accurate hand placement across different weapon meshes.
* **Data-Driven Weapon System:** Building a decoupled Actor Component where all weapon behaviors—including stats, meshes, and specific Animation Montages—are managed entirely through scalable Data Tables.
* **Aiming Mechanics:** Creating precise Aim Offsets for head tracking and weapon aiming to maintain correct alignment during complex movement states.

🔗 [View Repository](https://github.com/nicolas-mancone/Technical-Animation-Project)

<br clear="left"/>

---

## 💻 Tech Stack & Core Competencies

* **Languages:** C++, Unreal Blueprints, Python, SQL
* **Engine:** Unreal Engine 5
* **Core Systems & Networking:** Replicated Multiplayer (RPCs, Client-Side Prediction), Character Movement Component (CMC) optimization.
* **AI & Behavior:** State Trees, Behavior Trees, Environment Query System (EQS), AI Perception System.
* **Technical Animation:** AnimGraph Architecture, Anim Notifies, Procedural Additives, FABRIK IK, Layered Blending.
* **Architecture & Data:** Modular Actor Components, Data-Driven Design (Data Tables), Gameplay Tags, GAS (Gameplay Ability System).
* **Physics:** Chaos Physics, Async Physics Tick for deterministic synchronization.
* **Tools & Version Control:** Git, GitHub, Visual Studio, JetBrains Rider, Google Cloud Platform (GCP), Jira.

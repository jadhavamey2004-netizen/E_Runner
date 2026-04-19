# Unreal Engine 5: Procedural Endless Runner

This project was developed as a comprehensive technical exploration into **Unreal Engine 5** mechanics during my internship at **Stacklab.in**. The game implements core "Endless Runner" features, focusing on procedural level generation, optimized actor lifecycles, and responsive character controllers.

---

## 🛠️ Technical Stack
* **Engine:** Unreal Engine 5
* **Scripting:** Blueprints Visual Scripting
* **Mentorship:** Mr. Sagar Wankhede

---

## 🚀 Key Features

### 1. Procedural Level Generation
The environment is built dynamically during runtime to ensure an infinite gameplay loop.
* **Modular Floor Tiles:** Developed a blueprint-based spawning system that utilizes arrow components as transform markers for seamless tile attachment.
* **Trigger-Based Spawning:** Implemented box collision triggers within floor tiles; once a player enters a tile, the next segment is instantiated ahead while previous segments are destroyed to conserve memory.
* **Dynamic Expansion:** The system allows for the continuous addition of floor blocks during runtime without performance hitches.

### 2. Character & Movement System
* **Inputs & Controls:** Configured custom input mappings for character navigation, including left/right lane switching and jump mechanics.
* **Character Setup:** Integrated skeletal meshes with Animation Blueprints to handle transitions between idle, run, and jump states.
* **Collision Logic:** Utilized specialized collision profiles to handle interactions between the player, the floor, and obstacles.

### 3. Obstacle & Hazard Orchestration
* **Randomized Spawning:** Developed logic to populate floor tiles with randomized obstacle actors upon instantiation.
* **Performance Optimization:** Leveraged actor destruction logic to clean up obstacles and tiles once they are no longer visible to the player, preventing memory leaks.

---

## 🏗️ System Architecture
* **Game Mode:** Manages the high-level game state and score persistence.
* **Floor Tile Blueprint:** Contains the logic for its own spawning markers and hazard population.
* **Character Blueprint:** Houses the movement component logic and input handling.

---

## 📈 Learning Outcomes
Through this project at Stacklab.in, I mastered the **Game Development Life Cycle (GDLC)** within Unreal Engine, specifically focusing on:
* Project setup and asset migration.
* Advanced Blueprint communication.
* Dynamic environment optimization.

---

## 🤝 Acknowledgments
Special thanks to **Mr. Sagar Wankhede** for his mentorship and the team at **Stacklab.in** for providing the professional environment to develop this project.

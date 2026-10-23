# Space Defender Game (Harvard CS50x - Week 0 Project)

This is my first professional software development project built as a requirement for **Harvard University's CS50x (Introduction to Computer Science)** course. The game scored **8/8 (100%)** on Harvard's automated grading system (`check50`).

## 🎮 Game Concept
"Space Defender" is an interactive 2D arcade-style game where the player controls a rocket ship defending Earth against incoming meteors. The game dynamically scales in difficulty as the player scores higher.

## 🛠️ Technical Concepts Applied (Harvard Criteria)
To prove algorithmic thinking and structural correctness, this project successfully implements the following computer science fundamentals inside Scratch:

* **Object-Oriented Design (Multi-Sprites):** Independent control logic for the `Rocketship` (Player), `Lightning` (Weapon), and `Rocks` (Enemy).
* **Asynchronous Execution & Multi-Threading:** Utilizing concurrent loops (`forever`) allowing smooth background movements while tracking inputs simultaneously.
* **Cloning Systems:** Utilizing dynamic scaling by spawning and deleting laser clones to optimize memory handling.
* **Encapsulation via Custom Blocks (Functions):** Created a custom function block named `Reset Rock` with an integer argument (`Y_Position`) to handle repetitive boundary-reset logic safely.
* **Control Structures & Dynamic Difficulty Evaluation:** Nested conditional statements (`if/then`) to increment scores, track game over metrics, and increase asteroid drop speed dynamically.

## 📂 How to Run the Project
1. Download the `Untitled.sb3` file from this repository.
2. Go to the official [Scratch MIT Website](https://mit.edu).
3. Click on **File** -> **Load from your computer** and select the `.sb3` file to preview and play.
٤.

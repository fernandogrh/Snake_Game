# 🐍 **FR Python Snake Game**

    > Python Snake game built with **OOP and multi-module design**.  
    > Features optimized game loop, **inheritance, dynamic object spawning, collision logic, and modular architecture**.  
    > Built to showcase **scalable code structure and core development principles**.

![GitHub Repo](https://img.shields.io/badge/Repository-Active-black?logo=github)
![Python](https://img.shields.io/badge/Python-OOP_Modules-blue?logo=python&logoColor=white)
![Code Quality](https://img.shields.io/badge/Code-Clean_&_Modular-brightgreen)
![Game Dev](https://img.shields.io/badge/Game_Logic-Collision_&_Loop_Design-orange)


## 🚀 Project Highlights

    This project was built with a focus on **architecture over flashiness**, proving strong understanding of:

    - Multi-class systems with clear responsibility separation  
    - **Inheritance** (`Food` and `Scoreboard` extend `Turtle`)  
    - Stable and optimized **real-time game loop**  
    - Collision detection (food, walls, self-body)  
    - **Randomized dynamic object spawning** (food placement)  
    - Modular Python file architecture  


## 🧠 Core Concepts Implemented

    | Concept | Implementation in Project |
    |---|---|
    | **Loops** | Continuous `while play:` game loop driving state & rendering |
    | **Functions** | Direction controls, score increment, collision logic |
    | **OOP** | Classes manage game objects (`Snake`, `Food`, `Scoreboard`) |
    | **Inheritance** | `Food(Turtle)`, `Scoreboard(Turtle)` reuse built-in behavior |
    | **Encapsulation** | Each module controls its own logic independently |
    | **Collision Logic** | Uses distance + screen bounds + segment overlap checks |


## 🧩 Module Responsibilities

    main.py
	•	Initializes screen, snake, food, scoreboard
	•	Handles keyboard input listeners
	•	Runs game loop & collision detection

    snake.py
	•	Builds snake body using loops
	•	Moves snake using reverse iteration
	•	Prevents invalid 180° turning
	•	Implements extend() for growth

    food.py
	•	Inherits core traits from Turtle
	•	Spawns in random screen positions with RNG

    scoreboard.py
	•	Displays current score at top of screen
	•	Updates score using a class method
	•	Triggers Game Over display when called


## How to Run

```bash
git clone <repo_url_here>.git
cd <repo_folder>
python main.py
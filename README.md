# 🐍 Classic Snake Game in Python

A simple recreation of the classic Snake Game built using Python's `turtle` module. This project is built using Object-Oriented Programming principles and includes persistent high score tracking using a local text file.

## 🎮 Game Features

- Move the snake using arrow keys: **Up, Down, Left, Right**
- Eat food (blue dots) to grow the snake and increase your score
- Game resets upon collision with wall or self
- High score is saved across sessions using `data.txt`
- Modular design using classes: `Snake`, `Food`, and `Scoreboard`

---

## 🧱 Project Structure
snake-game/
│
├── main.py # Main game loop and event listeners
├── snake.py # Snake class (movement, growth, collision)
├── food.py # Food class (random repositioning)
├── scoreboard.py # Scoreboard class (score and high score tracking)
├── data.txt # Stores high score persistently
└── README.md # This file

---

## 💻 Techniques Used

- Turtle Graphics (built-in)
- OOP (Object-Oriented Programming)
- Basic File I/O

# 🎮 Tetris Game in C++ using Raylib

A modern recreation of the classic **Tetris** game built with **C++** and the lightweight **Raylib** graphics library.  
This project focuses on the fundamentals of game development such as game loops, collision detection, input handling, and real-time rendering.

---

## 🔧 Features

- 🎲 Classic Tetris mechanics  
- 🎨 Smooth 2D graphics using Raylib  
- 🧱 Real-time falling blocks with rotation  
- 💥 Line-clearing logic with scoring  
- 🎮 Keyboard controls  
- 🔁 Restart functionality after game over  

---

## 🧰 Tech Stack

- **Language**: C++  
- **Graphics Library**: [Raylib](https://www.raylib.com)  
- **Build Tools**: GCC / g++ (Linux or Windows), or CMake (optional)

---

## 🚀 How to Run

### 1. Install Raylib

Follow Raylib installation steps from:  
👉 [Raylib Wiki – Installation](https://github.com/raysan5/raylib/wiki#installation)

### 2. Clone this Repository

```bash
git clone https://github.com/your-username/tetris-raylib.git
cd tetris-raylib
```
## Build and Run
## On Linux / macOS:
```bash
g++ main.cpp -o tetris -lraylib -lGL -lm -lpthread -ldl -lrt -lX11
./tetris
```
## On Windows (MinGW):
```bash
g++ main.cpp -o tetris.exe -lraylib -lopengl32 -lgdi32 -lwinmm
./tetris.exe
```

## 📚 Learnings
- **This project helped understand:**
- **Game loop architecture**
= **Real-time graphics with Raylib**
- **2D grid manipulation using arrays**
- **Collision detection logic**
- **Input handling in C++**

  ## 📄 License
- **This project is licensed under the MIT License.**
- **Feel free to use, modify, or distribute for personal and educational purposes.**

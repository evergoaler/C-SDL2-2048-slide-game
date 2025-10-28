# C-SDL2-2048-slide-game
# 2048-SDL2 🎮  
A modern recreation of the classic **2048** puzzle game written in **C** using **SDL2**.  
This project features multiple play modes, a clean design, and smooth gameplay — built from scratch as a university project.

---

## 🚀 Features
- 🧠 **Three play modes**:
  - **Player** – Play manually with arrow keys.
  - **Machine** – Watch an AI play automatically.
  - **Player vs Machine** – Compete against the AI.
- 🎨 **Custom grid rendering** using SDL2 graphics.
- 🔢 **Score system** that updates in real-time.
- 🧱 **Tile spawning and combination** logic fully implemented.
- 🕹️ **Keyboard input handling** and frame updates.
- 🧰 **Clean modular code** split into headers and source files.

---

## 🛠️ Tech Stack
- **Language:** C  
- **Graphics Library:** SDL2  
- **Font Rendering:** SDL2_ttf  

---

## 🧩 How to Build
### 🔧 Requirements
Make sure you have the following installed:
- [SDL2](https://www.libsdl.org/download-2.0.php)
- [SDL2_ttf](https://github.com/libsdl-org/SDL_ttf)
- A C compiler (e.g., MinGW, GCC, or MSVC)

### 💻 Build Command (example for MinGW)
```bash
gcc -Isrc/include -Lsrc/lib -o main main.c game.c -lmingw32 -lSDL2main -lSDL2 -lSDL2_ttf

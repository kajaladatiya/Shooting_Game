# 🎯 Enemy Shooting Game (OpenGL + GLUT)

A 2D shooting game developed using **C++ and OpenGL (GLUT)** where the player controls a shooter to destroy falling enemies, earn points, and survive with limited lives.

---

## 🕹️ Game Features
- Interactive main menu (New Game, High Score, How To Play, About, Exit)
- Real-time enemy spawning with increasing difficulty
- Bullet firing mechanics
- Collision detection (bullet–enemy & enemy–shooter)
- Score & life tracking
- High score saved using file handling
- Keyboard & mouse interaction
- Smooth animation using GLUT timer

---

## 🎮 Controls
| Action | Key |
|------|-----|
| Move Left | ← Left Arrow |
| Move Right | → Right Arrow |
| Shoot | Spacebar |
| Exit Game | ESC |
| Menu Selection | Mouse Click |

---

## 🛠️ Technologies Used
- **Language:** C++
- **Graphics Library:** OpenGL
- **Utility Toolkit:** GLUT
- **IDE:** VS Code / Code::Blocks
- **Platform:** Windows

---

## 🖥️ How to Run
### 🔹 Prerequisites
- OpenGL & GLUT installed
- GCC / MinGW compiler

### 🔹 Compile & Run
```bash
g++ Shooting_Game.cpp -o Shooting_Game -lfreeglut -lglu32 -lopengl32
./ShootingGame
```

---

## 📁 Project Structure
SHOOTING_GAME/
│
├── screenshots/                 # Game screenshots for README & itch.io
│   ├── Menu.png
│   ├── Gameplay.png
│   ├── GameOver.png
│   ├── HighScore.png
│   ├── HowToPlay.png
│   └── About.png
│
├── freeglut.dll                 # GLUT runtime library (Windows)
├── output.txt                   # Stores high score data
├── Shooting_Game.cpp            # Main C++ OpenGL source code
├── Shooting_Game.exe            # Compiled Windows executable
├── README.md                    # Project documentation (GitHub)
│
└── (root folder: SHOOTING_GAME)


---

## 👨‍💻 Developed By
Kajal Adatiya

---

## 🎮 Playable Game Download
https://kajaladatiya.itch.io/shootinggame

---

## 📜 License
This project is for educational purposes only.
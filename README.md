# 🏓 Pong Game

A modern remake of the classic **Pong Game** using Python's `turtle` module. Two-player game where each player controls a paddle and the goal is to bounce the ball past the opponent.

---

## 🎮 How to Play

- **Right Paddle (Player 1):**
  - `Up Arrow`: Move paddle up
  - `Down Arrow`: Move paddle down

- **Left Paddle (Player 2):**
  - `W`: Move paddle up
  - `S`: Move paddle down

- Game starts immediately.
- If the ball goes past your paddle, the opponent gets a point.
- First to your desired score wins!

---

## 📁 Project Structure

.
├── main.py # Main game loop
├── paddle.py # Paddle class for both players
├── ball.py # Ball movement and bounce logic
├── scoreboard.py # Score tracking and display
├── pycache/ # Python cache (ignore)


---

## 🚀 How to Run

### 1. Prerequisites

- Python 3.x installed
- No external libraries needed (uses built-in `turtle`)

### 2. Run the Game

```bash
python main.py

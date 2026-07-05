# 🎮 Tic Tac Toe AI using Minimax Algorithm

A simple command-line Tic Tac Toe game built in **Python**, where the player competes against an AI powered by the **Minimax Algorithm**.

The AI always makes the optimal move, making it impossible to beat if it plays perfectly.

---

## 🚀 Features

- Human vs AI gameplay
- AI uses the Minimax Algorithm
- Detects wins, losses, and draws
- Input validation
- Simple command-line interface
- Beginner-friendly Python project

---

## 🛠️ Technologies Used

- Python 3
- Minimax Algorithm
- Math module

---

## 📂 Project Structure

```
TicTacToe-AI/
│
├── main.py
├── README.md
```

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/TicTacToe-AI.git
```

### 2. Go to the project folder

```bash
cd TicTacToe-AI
```

### 3. Run the program

```bash
python main.py
```

---

## 🎮 How to Play

The board positions are numbered as:

```
1 | 2 | 3
--+---+--
4 | 5 | 6
--+---+--
7 | 8 | 9
```

- You play as **X**
- Computer plays as **O**
- Enter a number from **1 to 9** to place your move.

Example:

```
Enter position (1-9): 5
```

---

## 🧠 Minimax Algorithm

The AI uses the **Minimax Algorithm**, a decision-making algorithm commonly used in two-player games.

### Evaluation

- AI (O) wins → **+1**
- Player (X) wins → **-1**
- Draw → **0**

The algorithm recursively explores all possible game states and chooses the move that maximizes the AI's chances of winning while minimizing the player's chances.

---

## 📸 Sample Output

```
===== TIC TAC TOE AI =====
You are X
Computer is O

  |   |
--+---+--
  |   |
--+---+--
  |   |

Enter position (1-9): 5

Computer is thinking...

  |   |
--+---+--
  | X |
--+---+--
O |   |
```

---

## 📈 Future Improvements

- GUI using Tkinter or Pygame
- Difficulty levels (Easy, Medium, Hard)
- Alpha-Beta Pruning optimization
- Scoreboard
- Multiplayer mode
- Better board UI with colors

---

## 🎯 Learning Outcomes

This project helps understand:

- Python functions
- Lists
- Recursion
- Backtracking
- Game theory
- Minimax Algorithm
- AI decision making

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Open a Pull Request

---

## 📜 License

This project is open source and available under the **MIT License**.

---

## ⭐ Support

If you found this project helpful, consider giving it a **⭐ Star** on GitHub.

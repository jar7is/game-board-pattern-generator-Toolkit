# 🎮 Game Board & Pattern Generator Toolkit

A Python-based project that uses **NumPy and Matplotlib** to create game boards, generate patterns, visualize grids, and implement basic Tic-Tac-Toe game logic.

## 📌 Project Overview

The Game Board & Pattern Generator Toolkit demonstrates how NumPy arrays can be used to build and manage different types of game boards.

It combines array operations, indexing techniques, conditional logic, and data visualization to create an interactive learning experience through practical examples.

## ✨ Features

- **Tic-Tac-Toe Board:** Creates and visualizes a 3×3 game board.
- **Checkerboard Generator:** Generates an 8×8 alternating checkerboard pattern.
- **Diagonal Patterns:** Creates main diagonal and anti-diagonal patterns.
- **Piece Placement:** Places X and O using NumPy indexing.
- **Move Validation:** Checks whether a move is within board boundaries and whether a cell is empty.
- **Winner Detection:** Identifies winning rows, columns, and diagonals.
- **Draw Detection:** Detects when the board is full without a winner.
- **Visualization:** Displays boards and patterns using Matplotlib.
- **Testing:** Includes test cases for different game states.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| NumPy | Array creation, indexing and board operations |
| Matplotlib | Board and pattern visualization |
| Google Colab | Development and execution environment |
| Jupyter Notebook | Organizing code and demonstrations |

## 📂 Project Structure

```text
game-board-pattern-generator-Toolkit/
│
├── game_board_pattern_generator.ipynb
└── README.md
```

## 🚀 Getting Started

### Option 1: Run on Google Colab

No local installation is required.

1. Open the notebook using the link below.
2. Click **Runtime → Run all**.
3. Wait for the cells to execute.
4. Explore the generated boards and visualizations.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jar7is/game-board-pattern-generator-Toolkit/blob/main/game_board_pattern_generator.ipynb)

### Option 2: Run Locally

**1. Clone the repository**

```bash
git clone https://github.com/jar7is/game-board-pattern-generator-Toolkit.git
```

**2. Navigate to the project directory**

```bash
cd game-board-pattern-generator-Toolkit
```

**3. Install the required libraries**

```bash
pip install numpy matplotlib notebook
```

**4. Launch Jupyter Notebook**

```bash
jupyter notebook
```

Open `game_board_pattern_generator.ipynb` and run the cells.

## 🧠 Concepts Demonstrated

This project covers several important Python and NumPy concepts:

- NumPy array creation using `np.zeros()`, `np.ones()`, `np.full()` and `np.eye()`.
- Array slicing and stepped slicing.
- Fancy indexing.
- Matrix manipulation using `np.fliplr()`.
- Conditional statements and functions.
- Game-state validation using `np.all()`.
- Data visualization using Matplotlib.

## 🎯 Learning Outcomes

Through this project, I explored how:

- NumPy arrays can represent game boards.
- Indexing techniques can simplify board manipulation.
- Conditional logic can identify game outcomes.
- Matplotlib can convert numerical arrays into visual representations.
- Testing can help verify different game scenarios.

## 🔮 Future Improvements

- Add an interactive user interface.
- Allow users to play Tic-Tac-Toe directly.
- Add more board sizes and pattern types.
- Introduce additional game mechanics.

## 👨‍💻 Author

**Prabhat Kumar**

- GitHub: [@jar7is](https://github.com/jar7is)

---

⭐ If you find this project interesting, consider giving the repository a star!

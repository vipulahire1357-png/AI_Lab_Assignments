# 🤖 Artificial Intelligence — Lab Practicals

**Student:** Vipul Dilip Ahire  
**Subject:** Artificial Intelligence  
**Language:** Python 3 (Jupyter Notebooks)

---

## 📁 Repository Structure

```
AI_Practicals/
├── AILAB1.ipynb       → Rule-Based Expert System
├── AILAB2BFS.ipynb    → Breadth-First Search (BFS)
├── AILAB2DFS.ipynb    → Depth-First Search (DFS)
├── AILAB3.ipynb       → A* Search Algorithm
├── AILAB4.ipynb       → Constraint Satisfaction Problem (CSP)
├── AILAB5.ipynb       → Minimax Algorithm
└── AILAB6.ipynb       → Minimax with Alpha-Beta Pruning
```

---

## 🧪 Lab Assignments Overview

| Lab | Topic | Key Concepts |
|-----|-------|--------------|
| Lab 1 | Rule-Based Expert System | If-then logic, career recommendation system |
| Lab 2A | Breadth-First Search (BFS) | Graph traversal, queue (FIFO), shortest path |
| Lab 2B | Depth-First Search (DFS) | Graph traversal, stack (LIFO), maze solving |
| Lab 3 | A\* Search Algorithm | Heuristic search, Manhattan distance, pathfinding |
| Lab 4 | Constraint Satisfaction Problem | Map coloring, backtracking, Australia regions CSP |
| Lab 5 | Minimax Algorithm | Game tree, Tic-Tac-Toe AI, optimal decision-making |
| Lab 6 | Minimax + Alpha-Beta Pruning | Pruning optimization, reduced game tree exploration |

---

## 🔍 Detailed Lab Descriptions

### Lab 1 — Rule-Based Expert System
Implements a simple expert system that recommends a career path based on user interests (math, problem-solving, art, etc.). Demonstrates if-then rule logic that mimics human decision-making.

### Lab 2A — Breadth-First Search (BFS)
Graph/maze traversal using BFS. Explores nodes level by level using a queue (deque). Guarantees shortest path when one exists.

### Lab 2B — Depth-First Search (DFS)
Graph/maze traversal using DFS. Goes as deep as possible along a path before backtracking, implemented using a stack. Includes path reconstruction via a parent map.

### Lab 3 — A\* Search Algorithm
Heuristic-based pathfinding on a grid maze. Uses Manhattan distance as the heuristic with a min-heap (priority queue) to find the optimal path efficiently.

### Lab 4 — Constraint Satisfaction Problem (CSP)
Solves the classic Australia map-coloring problem. Assigns colors (Red, Green, Blue) to 7 regions such that no two neighboring regions share the same color, using backtracking.

### Lab 5 — Minimax Algorithm
Implements an AI agent for Tic-Tac-Toe using the Minimax algorithm. The AI evaluates all possible game states recursively to always play the optimal move.

### Lab 6 — Minimax with Alpha-Beta Pruning
Extends Lab 5 with Alpha-Beta Pruning to optimize the Minimax tree. Prunes branches that cannot affect the final decision, significantly reducing computation time.

---

## 🛠️ Tech Stack

- **Language:** Python 3
- **Environment:** Jupyter Notebook
- **Libraries:** `collections`, `heapq`, `math`, `time`, `random`

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/AI_Practicals.git
   cd AI_Practicals
   ```

2. Install Jupyter (if not installed):
   ```bash
   pip install notebook
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Open any `.ipynb` file and run cells sequentially.

---

## 📌 Topics Covered (for Resume)

- Uninformed Search: BFS, DFS
- Informed Search: A\* Algorithm
- Knowledge Representation: Rule-Based Expert Systems
- Constraint Satisfaction Problems (CSP)
- Adversarial Search: Minimax & Alpha-Beta Pruning
- Game AI: Tic-Tac-Toe intelligent agent

---

## 📄 License

This repository is for educational purposes only.

# Year Work Portfolio — Algorithm Design & Analysis

> **Author:** Engy Ehab Saad Elsaid
> **Subject:** Algorithm Design & Analysis
> **Year:** 2025 / 2026

---

## 📁 Project Structure

```
Year_Work_Portfolio/
│
├── README.md                  ← You are here
├── portfolio.html             ← Main page (all 5 tasks in one file)
│
└── tasks/
    ├── task1_search.html      ← Task 1: Linear vs Binary Search
    ├── task2_greedy.html      ← Task 2: Job Sequencing (Greedy)
    ├── task3_lcs.html         ← Task 3: Longest Common Subsequence (DP)
    ├── task4_graphs.html      ← Task 4: Connected & Disconnected Graphs
    └── task5_parallel.html    ← Task 5: Parallel vs Distributed Algorithms
```

---

## 🚀 How to Run

No installation, no server, no dependencies required.

1. Download all files and place them in the folder structure above
2. Double-click `portfolio.html`
3. It opens directly in any browser (Chrome, Firefox, Edge)

> ⚠️ Requires an internet connection **only** for Google Fonts (decorative — the site works without it)

---

## 📋 Tasks Overview

### Task 1 — Linear Search vs Binary Search
Implements and compares both search algorithms interactively.

- Adjustable array size (5–50 elements)
- Live visualiser highlights which elements each algorithm visits
- Real-time comparison counter for both algorithms
- Complexity table: Best / Worst / Average case
- Advantages and disadvantages of each

**Key result:** Binary search needs only `log₂(n)` comparisons vs `n` for linear search. For n = 1,000,000 that is 20 steps vs 1,000,000.

---

### Task 2 — Greedy Algorithm: Job Sequencing with Deadlines
Designs and implements the greedy job scheduling algorithm.

- Problem explanation and algorithm steps
- Interactive job table — toggle jobs on/off, add random jobs
- Live schedule output showing which slot each job is assigned
- Visual timeline of the resulting schedule
- Profit analysis with sample input/output

**Key result:** Always schedule the highest-profit job in the latest available slot ≤ its deadline to maximise total profit.

---

### Task 3 — Dynamic Programming: Longest Common Subsequence (LCS)
Implements LCS with full DP table visualisation.

- Enter any two strings to solve interactively
- DP table rendered with the traceback path highlighted in green
- Reconstructed LCS string displayed
- Space-optimised version (O(n) space) included
- Reflection covering: implementation process, complexity, challenges, optimisations, and real-world applications

**Complexity:** Time O(m × n) · Space O(m × n) · Traceback O(m + n)

---

### Task 4 — Connected & Disconnected Graphs with DFS & BFS
Implements graph traversal on both connected and disconnected graphs.

- Toggle between a connected graph (1 component) and disconnected graph (3 components)
- Animated BFS (Breadth-First Search) and DFS (Depth-First Search)
- Nodes colour-coded by component and visit order
- Visit order printed live during traversal
- Adjacency list and adjacency matrix representations
- BFS vs DFS comparison table
- Real-world applications for both algorithms

**Key insight:** On a disconnected graph the traversal must restart from each unvisited node to cover all components.

---

### Task 5 — Parallel vs Distributed Algorithms
Simulates and compares parallel and distributed execution models.

- Live worker progress simulation (2–8 workers)
- Switch between Parallel (shared memory) and Distributed (message passing) modes
- Speedup and efficiency metrics calculated on completion
- Python code examples using `multiprocessing` (parallel) and `mpi4py` (distributed)
- Amdahl's Law explanation and code
- Full comparison table across 11 dimensions

**Key insight:** Parallel algorithms are faster per operation (nanosecond memory access) but limited by core count. Distributed algorithms have network overhead but scale horizontally without limit.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structure and content |
| CSS3 | Styling, layout, animations |
| Vanilla JavaScript | All interactivity and algorithms |
| Canvas API | Graph visualiser, search visualiser, LCS table, simulations |
| Google Fonts | Typography (Sora + JetBrains Mono) |

> No frameworks, no libraries, no build tools — pure HTML/CSS/JS.

---

## 🎯 Features

- ✅ Fully interactive — all algorithms run live in the browser
- ✅ Clean dark-theme UI
- ✅ Responsive — works on desktop and tablet
- ✅ Self-contained — each file works independently
- ✅ Python code included for every algorithm
- ✅ No installation or setup required

---

## 📽️ Demo Video Guide

| Task | What to demonstrate |
|---|---|
| Task 1 | Change slider → enter target → click Run → show comparison counts |
| Task 2 | Click Schedule → toggle a job off → re-run → show profit difference |
| Task 3 | Change strings → click Solve → point out green traceback path |
| Task 4 | Run BFS on connected → switch to disconnected → run DFS |
| Task 5 | Run parallel → switch to distributed → compare speedup values |

---

*Year Work Portfolio · Algorithm Design & Analysis · 2025–2026*

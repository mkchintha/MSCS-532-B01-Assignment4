# MSCS-532-B01-Assignment 4

# Assignment 4: Heap Data Structures - Implementation, Analysis, and Applications

## Overview

This assignment explores two fundamental applications of heap data structures:
1. **Heapsort Algorithm**
2. **Priority Queue Implementation using Min-Heap**

It includes implementation, theoretical analysis, and practical comparisons with other sorting algorithms.

---

##  Contents

- `heap_assignment.py`: Python source code containing:
  - Heapsort implementation
  - Priority Queue implementation with Task class
- `Heap_Assignment_Report.docx`: Final report including:
  - Design choices
  - Time & space complexity analysis
  - Code snippets
  - Observations & conclusions

---

##  Heapsort

Heapsort is implemented using a **max-heap**, which ensures an in-place and consistent O(n log n) time complexity.

### Time Complexity:
- **Best / Average / Worst Case**: O(n log n)

### Space Complexity:
- O(1) (in-place)

---

##  Priority Queue

A **min-heap** is used to implement the priority queue, ideal for scheduling tasks based on priority.

### Supported Operations:
- `insert(task)` – O(log n)
- `extract_min()` – O(log n)
- `decrease_key(index, new_priority)` – O(log n)
- `is_empty()` – O(1)

Each task includes:
- `task_id`
- `priority`
- `arrival_time`
- `deadline`

---

##  How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/heap-assignment.git
   cd heap-assignment
   ```

2. Run the Python code:
   ```bash
   python heap_assignment.py
   ```

3. Open the report:
   - `Heap_Assignment_Report.docx`

---

## Author

Murali Krishna  

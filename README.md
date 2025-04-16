# CS374-Prim-sAlgorithm
Prim's Algorithm

Prim's Algorithm - Custom vs Library Implementation

This project demonstrates **Prim's Minimum Spanning Tree (MST) algorithm** using:

- A **custom implementation** from scratch using basic data structures
- A **library implementation** using Python’s `networkx`

The algorithm is applied to a **randomly generated weighted undirected graph** with at least 20 nodes and random edge weights.

---

## 📁 Files

### `prim_basic.py`
- Implements Prim’s algorithm using:
  - `dict` for graph representation
  - `heapq` for priority queue
  - No external libraries
- Outputs:
  - All edges in the generated graph
  - All MST edges
  - Total weight of the MST

### `prim_library.py`
- Uses `networkx` to:
  - Generate the same type of graph
  - Run the built-in `minimum_spanning_tree()` function (with Prim's algorithm)
  - Visualize the graph and its MST using `matplotlib`
- Outputs:
  - All edges in the generated graph
  - All MST edges
  - Total weight of the MST
  - Optional graph visualization

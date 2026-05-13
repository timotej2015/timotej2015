# Timotej Kuzma 👋

C++ & CUDA developer. I write low-level code for things that need to be fast — GPU kernels for mathematical search spaces, real-time AI planners for game agents.

- 🚀 **Currently:** GOAP planner optimization (bitmask state representation, Dijkstra over world-state graphs) and CUDA-accelerated binary matrix enumeration over GF(2).
- 🎓 **Education:** B.Sc. Computer Science, University of Maribor — thesis on intelligent AI agents in Unreal Engine 5.
- 🛠️ **Stack:** C++, CUDA, Python (CuPy), Unreal Engine 5, Blender, CloudCompare.

---

### ⚡ GF(2) Binary Matrix Diameter Search — CUDA

Custom CUDA kernels for searching the diameter of a 9×9 matrix space over GF(2), built to support an academic research paper. Standard libraries don't support binary arithmetic, so all matrix multiplication runs on XOR/AND logic written from scratch. Three filtration phases reduce a search space of 2³⁶ candidates to a tractable set — block matmul filter, inverse consistency check, and a binary tree membership lookup running entirely on the GPU to avoid CPU roundtrips. Pipeline glued together in Python via CuPy's `RawModule`.

---

### 🎮 GOAP AI System — Unreal Engine 5 & Standalone C++

A Goal-Oriented Action Planning system that evolved from a UE5 thesis project (2024) into an engine-agnostic C++ planner (2026). World states encoded as bitmasks; planning runs Dijkstra over a prebuilt action graph with dynamic edge weights. Supports multiple weighted goals in a single pass.

[![GOAP AI System Demo](https://raw.githubusercontent.com/timotej2015/GOAP_UnrealEngine/main/screenshots/Posnetek%20zaslona%202024-06-11%20211309.png)](https://www.youtube.com/watch?v=D5K0g2sD15g)

---

### 🏰 Jeterbenk — Medieval Castle Reconstruction

3D reconstruction of a 13th century fortified complex in Slovenia, based on LiDAR data (GURS) and archaeological research. No code involved — just CloudCompare, Blender, and a lot of reading.

[![Jeterbenk 3D Reconstruction](https://github.com/timotej2015/timotej2015/blob/main/CompositingTest4.png)](https://www.youtube.com/watch?v=OelK8SlSK8E)

---

## 📫 Contact
📧 [timotej.kuzma2015@gmail.com](mailto:timotej.kuzma2015@gmail.com)
📺 [YouTube — @timotejkuzma5838](https://www.youtube.com/@timotejkuzma5838)

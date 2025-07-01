# Technical Interview Notebooks

This repository provides a curated set of Jupyter Notebooks designed to prepare candidates for technical interviews, especially for backend, system design, and infrastructure roles.

---

## 📚 Included Notebooks

### ✅ 01 - Coding Challenges: Arrays, Trees, and Basic Algorithms

Covers:

- Array manipulation
- Linear & Binary Search
- Bubble, Quick, and Merge Sort
- Tree traversal (inorder, preorder, postorder)

📘 File: `01_coding_challenges_basics.ipynb`

---

### ✅ 02 - Data Structures: Lists, Queues, Stacks, Maps, and Graphs

Covers:

- Lists and common operations
- Queues with `deque`
- Stacks using `list`
- Maps with `dict`
- Graph traversal (DFS)

📘 File: `02_data_structures.ipynb`

---

### ✅ 03 - Web Services & APIs

Covers:

- REST vs SOAP
- HTTP status codes
- JSON vs XML (with examples)
- Authentication (API Key, Bearer, JWT)
- Pagination with mocked API

📘 File: `03_web_services_apis.ipynb`

---

### ✅ 04 - Architecture & Scalability

Covers:

- Distributed systems (latency simulation, CAP theorem)
- Layered architecture (presentation, logic, data)
- Relational vs NoSQL databases

📘 File: `04_architecture_scalability.ipynb`

---

### ✅ 05 - Architecture Patterns & Network Design

Covers:

- DMZ (Demilitarized Zone)
- Three-tier architecture
- Microservices
- Caching strategies and simulation
- Messaging queues (RabbitMQ, Kafka)
- Horizontal scaling

📘 File: `05_network_arch_patterns.ipynb`

---

### ✅ 06 - Dynamic Programming & Recursion

Covers:

- Recursion and memoization
- Tabulation (bottom-up DP)
- Fibonacci comparisons
- 0/1 Knapsack Problem

📘 File: `06_dynamic_programming_recursion.ipynb`

---

### ✅ 07 - Graph Algorithms: BFS, DFS, Dijkstra

Covers:

- Graph representation with adjacency lists
- Breadth-First Search (BFS)
- Depth-First Search (DFS)
- Dijkstra's shortest path algorithm

📘 File: `07_graph_algorithms.ipynb`

---

### ✅ 08 - Linked Lists and Heaps

Covers:

- Singly Linked List implementation
- MinHeap & MaxHeap using `heapq`
- Heap use cases and simulation

📘 File: `08_linked_lists_heaps.ipynb`

---

### ✅ 09 - System Design: Rate Limiter, Cache, URL Shortener

Covers:

- Fixed window rate limiter
- LRU cache with `OrderedDict`
- URL shortener with base62 encoding

📘 File: `09_system_design_examples.ipynb`

---

## ⚙️ How to Run Locally

```bash
# 1. Create and activate a virtual environment
python3 -m venv interview_env
source interview_env/bin/activate  # Windows: interview_env\Scripts\activate

# 2. Install Jupyter
pip install --upgrade pip
pip install jupyter

# 3. Start Jupyter Notebook
jupyter notebook
```

Then open any `.ipynb` file from the browser interface.

---

## 🚧 Upcoming Topics (planned)

- Sorting advanced (heap sort, radix sort)
- Real-world data modeling challenges
- Mock interview walkthroughs

# ⚡ Power Grid Optimizer: Prim's Algorithm for Electricity Distribution

## 📖 Overview
This project simulates an optimal electricity distribution network using **Prim's Algorithm**. In power grid planning, the goal is to connect a central power station to various substations, neighborhoods, or houses with the minimum total cost (usually measured in wire length or installation cost). 

By modeling the locations as **nodes** and the potential power lines as **edges**, Prim's Algorithm calculates the **Minimum Spanning Tree (MST)**. This ensures every node receives electricity while using the absolute minimum amount of resources.

## ✨ Features
* **Graph Modeling:** Represents power stations and consumers as a weighted, undirected graph.
* **Cost Optimization:** Implements Prim's Algorithm to find the lowest-cost path to connect all nodes.
* **Adjacency Matrix/List Support:** Flexible graph representation depending on grid size.
* **Visual Output (Optional):** Displays the final grid connections and total installation cost.

## 🛠️ How It Works (The Algorithm)
1. **Initialize:** Start with a single node (the main power station).
2. **Explore:** Look at all possible power lines (edges) connecting the current power grid to unpowered nodes.
3. **Select:** Pick the power line with the lowest cost (shortest distance/cheapest material).
4. **Connect:** Add that node to the power grid.
5. **Repeat:** Continue steps 2-4 until every node is connected to the grid.

## 🚀 Getting Started

### Prerequisites
Make sure you have the following installed (update this based on your language, e.g., Python, C++, Java):
* [Python 3.x](https://www.python.

# RL_CIA: Recommendation System and Grid Navigation

## Overview
This repository contains two projects focused on different applications of reinforcement learning:

1. **CIA 1: Product Recommendation System**
   - Develops a product recommendation system for an e-commerce platform using the K-arm bandit algorithm to maximize user engagement and purchases.

2. **CIA 2: RL-Based Grid Navigation**
   - Implements an RL agent to navigate a 100x100 grid with obstacles between random start and goal points using MDP. The project benchmarks Dynamic Programming (DP) methods against Q-learning for performance.

---

## CIA 1: Product Recommendation System

### Key Features
- **Products as Arms**: Each product is treated as an arm with estimated rewards (profit).
- **Epsilon-Greedy Algorithm**: Balances exploration and exploitation of product recommendations.
- **User Interaction Recording**: Records user interactions as rewards to refine recommendations.
- **Reward Updates**: Regularly updates product reward estimates based on user feedback.
- **Performance Evaluation**: Periodic evaluations ensure optimal recommendation performance.

### File
- `cia_1.py`: Python script containing the implementation of the recommendation system.


# CIA 2: RL-Based Grid Navigation

## Problem Statement
This project creates a 100x100 grid with obstacles between two random points. A reinforcement learning agent is built to optimize policies and actions at each state using Markov Decision Processes (MDP). The solution benchmarks the Dynamic Programming (DP) method against other RL solutions for performance.

## Key Features
- **Dynamic Grid Creation**: Generates a 100x100 grid with obstacles placed randomly.
- **MDP-Based Transitions and Rewards**: Utilizes MDP to define rewards and state transitions for the agent.
- **Policy Optimization**: Implements both DP-based policy iteration and Q-learning algorithms for pathfinding.
- **Performance Benchmarking**: Compares metrics of both methods to evaluate their effectiveness, including path length and convergence rates.

## File
- `cia_2.ipynb`: Jupyter Notebook containing the full implementation of the grid setup, agents, and performance comparison.

  
### Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/navin1111/RL_CIA.git
   cd RL_CIA

# RL-Based Supply Chain Optimization

## Overview

This project implements a **reinforcement learning (RL) solution** to optimize inventory and supply chain decisions in a multi-echelon supply chain system. The RL agent learns to make intelligent ordering decisions to minimize inventory holding costs, stockout costs, and ordering costs under uncertain and stochastic demand.

**Key Features:**

* Custom Gym environment simulating warehouse and retail inventory
* Stochastic demand modeling for realistic scenarios
* Training of DQN and PPO reinforcement learning agents
* Evaluation and visualization of inventory policies over time
* Business-oriented documentation for non-technical stakeholders

---

## Business Context

Effective supply chain management is crucial for any business dealing with products. Poor inventory decisions can result in:

* Excess stock leading to increased storage costs
* Stockouts causing lost sales and unhappy customers
* Inefficient capital allocation and operational inefficiency

This project demonstrates how AI can act as a **self-learning inventory manager**, making decisions based on past outcomes to balance costs and customer service levels. It provides insights into reducing operational costs by **20–30% in simulated scenarios** while maintaining high service standards.

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/rishabhkarnwal04/rl-supply-chain-optimization.git
cd rl-supply-chain-optimization
```

2. Create and activate a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

3. Install required packages:

```bash
pip install -r requirements.txt
```

---

## Run Instructions

### 1. Train the DQN Agent

```bash
python src/train_dqn.py
```

### 2. Train the PPO Agent

```bash
python src/train_ppo.py
```

### 3. Evaluate a Trained Agent

```bash
python src/evaluate.py
```

### 4. Visualize Inventory Levels

```bash
python src/visualize.py
```

> Note: Ensure the `src/` folder contains all necessary Python scripts (`env.py`, `train_dqn.py`, `train_ppo.py`, `evaluate.py`, `visualize.py`).

---

## License

This project is released under the MIT License.

---


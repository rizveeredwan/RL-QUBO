# RL-QUBO
The implementation of the article,  ``Reinforcement Learning-Based Formulations With Hamiltonian-Inspired Loss Functions for Combinatorial Optimization Over Graphs``, in IEEE Access, vol. 12, pp. 171055-171065, 2024, doi: 10.1109/ACCESS.2024.3497955


In this repository we address the Max-Cut problem in an attempt to solve it using Reinforcement learning based methods with the help of Hamiltonian function. For such, we have experimented with the following approaches,

- Monte Carlo Tree Search with GNN based Architecture / MCTS-GNN (mcts_hamiltonian_gnn.ipynb)
- A Generic RL framework with Hamiltonian as reward (grl_hamiltonian.ipynb)
- PI-GNN with fuzzy strategy (pi_gnn_fuzzy.ipynb)


To install the requirements run the following command.
``pip install -r requirements.txt``

We used python 3.8 to implement and run the experiments. Some of the experimented graphs can be found in ``Graph Dataset`` folder. 
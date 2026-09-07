*Frozen Lake Q-Learning Agent
This project implements a Q-learning agent to solve the FrozenLake-v1 environment from the Gymnasium library. 
The agent learns to navigate a slippery 8x8 frozen lake to reach a goal while avoiding holes.

*Project Overview
Q-learning is a model-free reinforcement learning algorithm. 
This implementation allows for training a Q-table that represents the optimal actions to take in each state of the Frozen Lake environment.
After training, the agent can be evaluated to observe its learned behavior, with optional visual rendering of its path.

*Dependencies
The following Python libraries are required:
gymnasium
numpy
matplotlib
pickle
Pillow (PIL)
moviepy

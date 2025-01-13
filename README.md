# Rainbow DQN: Combining Improvements in Deep Reinforcement Learning

## Overview
This repository provides a comprehensive summary of the paper [*"Rainbow: Combining Improvements in Deep Reinforcement Learning"*](https://arxiv.org/pdf/1710.02298) by Hessel et al., alongside a practical implementation of a Rainbow DQN agent. The implementation is tested on the CartPole environment, showcasing its efficiency in solving reinforcement learning problems.

## Contents
1. **Paper Summary**
   - A concise breakdown of the key components and contributions of the Rainbow DQN architecture.
2. **Implementation**
   - A detailed notebook implementing the Rainbow DQN agent. It can be open and run directly in [[Colab]](https://colab.research.google.com/github/thibautboyenval/reinforcement-learning-rainbow/blob/main/rainbow.ipynb).
   - Hyperparameter configurations and explanations of the key improvements.
3. **Application**
   - Demonstration of the Rainbow DQN agent's performance in the CartPole environment.

## Key Features of Rainbow DQN
Rainbow DQN combines several advancements in deep reinforcement learning into a unified framework:
1. **Double Q-Learning**: Reduces the overestimation bias present in standard Q-learning.
2. **Dueling Network Architecture**: Separates the state-value and advantage functions to improve policy evaluation.
3. **Prioritized Experience Replay**: Samples important transitions more frequently for efficient learning.
4. **Multi-Step Returns**: Incorporates rewards from multiple steps into the target update for faster convergence.
5. **Distributional RL**: Models the distribution of future rewards rather than just their expectation.
6. **Noisy Nets**: Adds parameterized noise to the network weights to improve exploration.
7. **C51 Algorithm**: Utilizes categorical distribution to represent the value distribution.

## Notebook Details
The notebook includes the following:
- **Environment Setup**: Initialization of the CartPole-v1 environment using Gymnasium.
- **Agent Implementation**:
  - Neural network architecture for the Rainbow DQN agent.
  - Implementation of key features (e.g., dueling networks, prioritized replay).
  - Training loop and evaluation metrics.
- **Visualization**:
  - Training curves to track agent performance.
  - CartPole environment simulations showcasing the agent's learned policy.

## Results
The Rainbow DQN agent achieves strong performance on the CartPole environment, demonstrating the benefits of combining multiple advancements in deep reinforcement learning.

## References
[1] M. Hessel, J. Modayil, H. van Hasselt, T. Schaul, G. Ostrovski, W. Dabney, D. Horgan, B. Piot, M. Azar, and D. Silver, "Rainbow: Combining Improvements in Deep Reinforcement Learning," arXiv preprint, arXiv:1710.02298, 2017.

[2] V. Mnih, K. Kavukcuoglu, D. Silver, A. A. Rusu, J. Veness, M. G. Bellemare, A. Graves, M. Riedmiller, A. K. Fidjeland, G. Ostrovski, et al., "Human-level control through deep reinforcement learning," Nature, vol. 518, no. 7540, pp. 529–533, 2015.

[3] H. van Hasselt, A. Guez, and D. Silver, "Deep Reinforcement Learning with Double Q-learning," arXiv preprint, arXiv:1509.06461, 2015.

[4] T. Schaul, J. Quan, I. Antonoglou, and D. Silver, "Prioritized Experience Replay," arXiv preprint, arXiv:1511.05952, 2015.

[5] Z. Wang, T. Schaul, M. Hessel, H. van Hasselt, M. Lanctot, and N. de Freitas, "Dueling Network Architectures for Deep Reinforcement Learning," arXiv preprint, arXiv:1511.06581, 2015.

[6] M. Fortunato, M. Azar, B. Piot, J. Menick, I. Osband, A. Graves, V. Mnih, R. Munos, D. Hassabis, O. Pietquin, et al., "Noisy Networks for Exploration," arXiv preprint, arXiv:1706.10295, 2017.

[7] M. G. Bellemare, W. Dabney, and R. Munos, "A Distributional Perspective on Reinforcement Learning," arXiv preprint, arXiv:1707.06887, 2017.

[8] R. S. Sutton, "Learning to predict by the methods of temporal differences," Machine Learning, vol. 3, no. 1, pp. 9–44, 1988.

Additional Resources:
- RL Adventure by Higgsfield: [https://github.com/higgsfield/RL-Adventure/tree/master](https://github.com/higgsfield/RL-Adventure/tree/master)
- Kaixhin's Rainbow Implementation: [https://github.com/Kaixhin/Rainbow/tree/master](https://github.com/Kaixhin/Rainbow/tree/master)


---

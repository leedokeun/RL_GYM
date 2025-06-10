# RL_GYM
Reinforcement Learning for Gym Environment
This project implements and compares the performance of three foundational Deep Reinforcement Learning algorithms—DQN, Double DQN, and Dueling Double DQN—on classic control environments from the OpenAI Gym library.

### Maintainers
* [Dokeun Lee](https://github.com/leedokeun)

## Requirements
* OpenAI Gym
* PyTorch
* CUDA
* NumPy
* Matplotlib
* Pandas

## Getting started

Open RL_GYM.ipynb, and run the cell sequentially. You can also refer RL_GYM.pdf.

## Algorithms Implemented
* DQN (Deep Q-Network): A fundamental value-based RL algorithm that utilizes a replay buffer and a target network.
* Double DQN: An improvement over DQN that mitigates overestimation bias by decoupling the action selection and value evaluation steps.
* Dueling Double DQN: A further enhancement that modifies the network architecture to separately estimate state-values (V(s)) and action-advantages (A(s, a)), leading to more efficient learning.

## Environments Tested
* CartPole-v1
* Acrobot-v1
* MountainCar-v0

## License

MIT license.


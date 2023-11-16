# Cart and Pole Balancing with Deep Reinforcement Learning

## Overview
This project implements a deep reinforcement learning algorithm to solve the cart and pole balancing problem using the OpenAI Gym environment. The algorithm uses a deep neural network to learn and make decisions, and it employs reinforcement learning techniques to improve its balancing performance over time.

## Installation
To run the code in this repository, you will need to install the following dependencies:
- git
- Python 3.x
- OpenAI Gym
- NumPy
- Keras
- Theano

To install OpenAI Gym, you can use Git by following the instructions at [git-scm.com](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git). After installing Git, you can use the following commands to download and install OpenAI Gym:
```
git clone https://github.com/openai/gym
cd gym
pip install -e . # minimal install
```
You can then install the required Python libraries (NumPy, Keras, Theano) using Conda or pip.

## Usage
1. Clone this repository to your local machine.
2. Navigate to the cloned directory and run the provided Python script.

    ```bash
    python cartpole_dqn.py
    ```

## Details

### The Repository Includes:
1. **cartpole_dqn.py**: The Python script that contains the implementation of the deep reinforcement learning algorithm for cart and pole balancing.

### Implementation Details:
- The code defines the neural network model using Keras with a deep Q-learning algorithm.
- It includes functions for running the environment, choosing actions, and updating the model based on new experiences.
- The training parameters like the number of episodes, discount factor, exploration rate, and learning rate are configurable.



## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



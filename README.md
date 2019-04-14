# Baba is gym

Requirements:
- Python 3
- OpenAI Gym
- NumPy

## Installation

Clone this repository and install the other dependencies with `pip3`:

```
git clone https://github.com/mtrazzi/baba-is-gym.git
cd baba-is-gym
pip3 install numpy
pip3 install gym
```

## Use gym-alttp-gridworld

```
import gym
import baba-is-gym
env = gym.make('BabaIsGymEnv-v0')
_ = env.reset()
_ = env.step(env.action_space.sample())
```

## Getting Started with Table Q-learning

For the Reinforcement Learning algorithm, I used an algorithm based on Table Q-learning.

To start the training and visualize the environment, do the following command at the root of the directory:

```
python3 main.py
``` 

### Terminal Render

## Environments Design

### Structure of the world:
	

### Possible Actions:
	

### Rewards:

### Episodes:
	
### Observations:

# License

MIT

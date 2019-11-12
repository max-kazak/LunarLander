# Lunar Lander
In this project I trained Q-Learner network for solving LunarLander game from [_gym_](https://gym.openai.com/) toolkit.

The goal of this project is to apply Reinforcement Learning techniques in combination with neural network to solve the task that requires responsive action (firing certain engines of the lunar lander) to observable environment (location, angle, speed, etc.)

Training process explores hyperspace of various hyperparameters to find optimal combination for the best performance.

## Environment
To run this code one has to create _python 3_ environment with following libraries:

 - numpy, 
 - matplotlib, 
 - tensorflow, 
 - jupyter, 
 - [gym](https://gym.openai.com/)
 
## Execution
To reproduce the results one can run in the terminal with created environment: _jupyter notebook_

After that open DQN.ipynb file in jupyter web interface and run all cells.

Notebook contains implementation of the Q-Learner as well as graphs showing effects of various hyperparameters on learning process.

Also _checkpoints_ folder contains saved tensorflow environments, so anyone can skip agent training step and proceed stright to testing stage.

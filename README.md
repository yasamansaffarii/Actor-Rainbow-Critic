# Actor-Rainbow-Critic
A combined architecture of state of arts algirithms of DQN for a task based dialogue system
## Dialogue system
Based off of the code repo TC-Bot and paper End-to-End Task-Completion Neural Dialogue Systems. This repo is a simplified version of TC-Bot, performed in [Goal-Oriented Chatbot trained with Deep Reinforcement Learning](https://github.com/maxbren/GO-Bot-DRL)
## DRL
To improve the performance of agent in this task, Rainbow and Actor critic and all combination of the Rainbow's components and Actor Critic implemented. And finally the best combonents chosen and combined to make a best model.
##Dependencies
Python >= 3.5
Keras >= 2.24 (Earlier versions probably work)
numpy
##How to Run
All codes run in colab.

You can train an agent from scratch with python train.py.

In constants.json you can change hyperparameters including.

All the constants are pretty self explanatory other than "vanilla" under agent which means DQN (true) or Double DQN (false). Defualt is vanilla DQN.

##dqn_agent.py
To train each model, replace it's code with dqn_agent.py codes.


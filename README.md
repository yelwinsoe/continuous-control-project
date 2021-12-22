# Continuous Control Project
This is a project for Udacity Nanodegree program Deep Reinforcement learning. This project solve moving double-jointed arm (Reacher environment) to it target location.A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

This project will be considered solved if the agent yields average score of +30 of 20 agents.

## Getting Started
Following the instruction below to setup your development environment.
1. Follow the instruction from [this link](https://github.com/udacity/deep-reinforcement-learning#dependencies) to setup your python development and install dependencies.
2. Download this repository.
3. Download one of the Unity Environment based on your operating system pre-build by Udacity.
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip)

    Put the file in this repository folder and unzip the file.
4. Run jupyter notebook in the root of this repository, if you don't have it yet you can [click here](https://jupyter.org/install) to install.
5. Follow along the instruction in Continuous_Control.ipynb to train and test the model.
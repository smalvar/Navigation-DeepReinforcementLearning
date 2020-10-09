# Deep Reinforcement Learning Nanodegree - Project 1: Navigation

### Introduction

For this project, I’ve trainned an agent to navigate and collect bananas in a square world using Unit environment.

** WITHOUT TRAINNING **
![Without trainning](https://s8.gifyu.com/images/ezgif.com-resize4d9dd8916883ee58.md.gif)

Each time the agent collect a yellow banana, it’s given a reward of +1. For each blue banana, it received a -1 reward. The goal of the agent is to collect as many yellow bananas as possible and avoid any blue bananas, as it must increase the score given by the amount of rewards received.  

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  4 discrete actions are available, corresponding to:

- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

To complete the task the agent must get an average score of 13 over 100 consecutive episodes. 


### Starting
0. Clone this repo.

1. Setup the python enviroment following next link: ![udacity/deep-reinforcement-learning](https://github.com/udacity/deep-reinforcement-learning#dependencies)

2. Copy the content of the `p1_navigation/` folder from this repo to the `p1_navigation/` folder of the udacity/deep-reinforcement-learning repo and replaces or remove existing files.

3. Unzip the Banana_Linux.zip file that is located under the `p1_navigation/` folder under the same directory. If you are not using Linux, follow the instructions on the botton of this file.



### Instructions

Open a jupyter notebook and open the Navigation.ipynb to train or test the agent.

1. For training from zero run all the cells inside the navigation notebook

2. For testing skip the training section and follow the instructions to load the weights. 

### Download the environment (not Linux users)

You need to select the environment that matches your operating system:

   - Linux: ![click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    
   - Mac OSX: ![click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    
   - Windows (32-bit): ![click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    
   - Windows (64-bit): ![click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    

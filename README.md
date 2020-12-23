# Deep-Q-Learning-PACMAN

In this project, I used Deep Reinforcement Learning to combine artificial neural networks with reinforcement learning.

## Deep Neural Network
I have created 2 hidden (Dense) layers with 128 neurons in each to create my DQN. My input layer is directly feeded by states of the environment. There are 9 possible actions that my agent can take, so my output layer consists of 9 neurons in total. 

Same applied for my target network.

## Epsilon Greedy Strategy
My agent takes its actions based on epsilon greedy strategy, where I initialized epsilon as 1.0 and decayed it gradually.

## Initial Parameters
<li>Epsilon: 0.99 </li>
<li>Epsilon decay: 0.9998</li>
<li>Disctount factor: 0.99</li>
<li>Learning rate: 0.0001</li>



<br>Even though initial results are promising, the model has only trained around 70 hours now, whereas I need weeks to complete full training.</br>


### Links
<b> GitHub </b>: [Link](https://github.com/gorkemguneser/Deep-Q-Learning-PACMAN)</br>
<b> Presentation </b>: [Here](https://docs.google.com/presentation/d/1hc7L-Xvr2DYcYipKMPUnhRqCNlJXesiG3y5EMFrViDM/edit#slide=id.gb1ff898c40_0_222)</br>

### Authors
[Gorkem Guneser](https://www.linkedin.com/in/gorkemguneser/)

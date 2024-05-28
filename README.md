# Reinforcement Learning
 Notebooks from University of Alberta RL Courses

## Course 1
key concepts of Reinforcement Learning, underlying classic and modern algorithms in RL. 
Introduction to statistical learning techniques where an agent explicitly takes actions and interacts with the world. 


<ins>Key Ideas</ins>  
The K-Armed Bandit Problem  
Markov Decision Processes  
Value Functions & Bellman Equations  
Dynamic Programming


## Course 2
Investigate several sample based learning algorithms that can learn near optimal policies based on trial and error interaction with the environment—learning from the agent's own experience. Learning from actual experience is striking because it requires no prior knowledge of the environment's dynamics, yet can still attain optimal behavior.  
Using simple but powerful Monte Carlo methods, and temporal difference learning methods including Q-learning. Investigating how we can get the best of both worlds: algorithms that can combine model-based planning (similar to dynamic programming) and temporal difference updates to accelerate learning.

<ins>Key Ideas</ins>  
Monte Carlo Methods for Prediction & Control  
Temporal Difference Learning Methods for Prediction  
Temporal Difference Learning Methods for Control  
Planning, Learning, & Acting  

## Course 3  
Prediction and Control with Function Approximation
Solving problems with large, high-dimensional, and potentially infinite state spaces. Estimating value functions can be cast as a supervised learning problem—function approximation—allowing the building of agents that carefully balance generalization and discrimination in order to maximize reward. Investigating how policy evaluation or prediction methods like Monte Carlo and TD can be extended to the function approximation setting. Learn about feature construction techniques for RL, and representation learning via neural networks and backprop. End with a deep-dive into policy gradient methods; a way to learn policies directly without learning a value function. Solve two continuous-state control tasks and investigate the benefits of policy gradient methods in a continuous-action environment. 

<ins>Key Ideas</ins>  
On-policy Prediction with Approximation  
Construction Features for Prediction  
Control with Approximation  
Policy Gradient  

## Course 4 - A Complete Reinforcement Learning System (Capstone)
In this final course, put together knowledge from Courses 1, 2 and 3 to implement a complete RL solution to a problem. This capstone wshows how each component—problem formulation, algorithm selection, parameter selection and representation design—fits together into a complete solution, and how to make appropriate choices when deploying RL in the real world. This project implements both the environment to stimulate your problem, and a control agent with Neural Network function approximation. In addition it conducts a scientific study of your learning system to develop an ability to assess the robustness of RL agents. To use RL in the real world, it is critical to (a) appropriately formalize the problem as an MDP, (b) select appropriate algorithms, (c ) identify what choices in your implementation will have large impacts on performance and (d) validate the expected behaviour of your algorithms. This capstone is valuable for anyone who is planning on using RL to solve real problems.

<ins>Key Ideas</ins>  
Formalize Word Problem as MDP  
Choosing the Right Algorithm  
Identify Key Performance Parameters  
Implement the Agent  

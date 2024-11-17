# CART POLE BALANCING

## AIM
To develop and fine tune the Monte Carlo algorithm to stabilize the Cart Pole.

## PROBLEM STATEMENT
This environment corresponds to the version of the cart-pole problem described by Barto, Sutton, and Anderson in “Neuronlike Adaptive Elements That Can Solve Difficult Learning Control Problem”. A pole is attached by an un-actuated joint to a cart, which moves along a frictionless track. The pendulum is placed upright on the cart and the goal is to balance the pole by applying forces in the left and right direction on the cart.

The action is a ndarray with shape (1,) which can take values {0, 1} indicating the direction of the fixed force the cart is pushed with.

i) 0: Push cart to the left

ii) 1: Push cart to the right

## MONTE CARLO CONTROL ALGORITHM FOR CART POLE BALANCING
* Import necessary libraries such as gym, numpy, tqdm, time, and matplotlib.pyplot.
  
* Define constants and global variables required for the algorithm, like the number of bins, initial Q-values, and decay parameters.

* Define functions for state discretization based on bins and for creating a decay schedule for alpha and epsilon values.

* Implement a function to generate trajectories using an epsilon-greedy policy.

* Develop the Monte Carlo control algorithm to update Q-values iteratively based on observed trajectories, using epsilon-greedy policy and decaying alpha and epsilon values.

* Run the Monte Carlo control algorithm using provided Q-values and default or modified parameters, optionally considering using previous Q-values.

* Implement functionality to save or load Q-values from/to a file for later use.

* If necessary, include code to visualize the results, such as plotting epsilon decay over episodes.

* Test the algorithm with various parameters and environments to ensure it behaves correctly.

* Document and optimize the code for readability and efficiency, adding comments and refining variable names where necessary.


## MONTE CARLO CONTROL FUNCTION


## OUTPUT:
1. Specify the average number of steps achieved within two minutes when the Monte Carlo (MC) control algorithm is initiated with zero-initialized Q-values..
2. Mention the average number of steps maintained over a four-minute period when the Monte Carlo (MC) control algorithm is executed with pretrained Q-values.

## RESULT:

Thus, a Python program is developed to find the optimal policy for the given cart-pole environment using the Monte Carlo algorithm.

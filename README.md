# Fractional/Continous Knapsack problem



#### In theoretical computer science, the continuous knapsack problem is an algorithmic problem in combinatorial optimization in which the goal is to fill a container with fractional amounts of different materials chosen to maximize the value of the selected material.

#### This algorithm attempts to address the fractional knapsack problem by calculating the actual value of each item and the capacity of the knapsack. Inherently, it uses a greedy approach by including the maximum valued item until the item is either exhausted or the knapsack is filled. 

## Directions

#### Download the python script

```
$ git clone https://github.com/rcvenkata/Fractional-Knapsack-problem.git
```
#### Run the script

```
$ python2 fractional_knapsack.py
```

#### After prompted for user-input values, enter each value (of knapsack and items) followed by ****spaces****

##### Enter the values of the knapsack (number of items and total weight the knapsack can hold) followed by total values and weights of individual items available. 

#### Example : 
```
$ Enter the values and weights after knapsack attributes placing spaces between numbers : 3 50  60 20 100 50 120 30

```

##### As shown in the example above, the first two integers (3, 50) are total number of items (n) and total weight the knapsack (W) can hold. The next set of numbers are values (**v**<sub>i</sub>) and weights (**w**<sub>i</sub>) of an i-th item respectively. 


## References:

http://www.cs.ust.hk/mjg_lib/Classes/COMP3711H_Fall14/lectures/Greedy_Knapsack_Slides.pdf




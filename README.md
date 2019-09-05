# Pruning-Neural-Networks

### This project explores the extent to which a neural network can be pruned. 

### Pruning
Neural networks can be very large and storing the unnecessary weights and units of a neural network increases the size and makes it less easier for use on devices with limited resources. Pruning is one of the solutions that addresses this problem.
The process of pruning goes from analyzing how many connections/units are redundant in calculating the output of a neural network and then implementing efficient strategy for removing them.



### Notes:

1. The weights associated with a unit(neuron) of a layer are stored as ROWS in the weight matrix of that layer

2. The input samples are stored as columns in batch matrices where No. of Columns = No. of Samples, No. of Rows = No. of features

3. The model is implemented as a function rather than as a 'class'.

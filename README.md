# Linear Regression Using A Neural Net

A short example in MATLAB demonstrating the connection between a simple linear regression problem and the training of a neural net with a single hidden layer consisting of just one node. We show that the two problems are equivalent when using a single hidden layer of just one node with a linear activation function. That is, the weight and bias terms correspond to the gradient and intercept of the linear line of best fit.

We also include the option of using different activation functions (sigmoid, tanh, ReLU, leaky ReLU and ELU) and different batch sizes in the stochastic gradient descent algorithm used to train the model.

The path of the parameters (W, the weight and b, the bias) in parameter space during training is plotted to demonstrate the difference in behaviour between stochastic gradient descent, batch method and full gradient descent.

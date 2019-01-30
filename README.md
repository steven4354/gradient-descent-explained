# Gradient Descent

For many linear regressions, the model is sufficiently simple that the true minimum of the cost function can be calculated by solving a system of equations (least squares). However, many other models that we will encounter from this point forward are too complex to be solved for a true minimum (due to # of different variables). For those models it's useful to use an iterative algorithm that starts from a random set of parameters and slowly works toward optimizing the cost function.

One such algorithm is gradient descent, which iteratively minimizes the cost function using derivatives. This approach is robust and flexible, and can be applied to basically any differentiable function.

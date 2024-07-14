In this project I implemented logistic regression for wine classification using both batch gradient descent and stochastic gradient descent (SGD) and plotted the cost function against iteration count, observing gradual convergence. For SGD, I used a learning rate of 0.01, shuffled the data similarly, and compared the convergence rate to batch gradient descent, finding that SGD required more iterations to converge due to its stochastic nature. Finally, I enhanced SGD with a diminishing step size of ϵt = 0.1/t and observed improved convergence compared to the constant step size SGD.
See [Gradient_descent.ipynb](Gradient_descent.ipynb) for the code.

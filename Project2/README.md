# Assignment 2:  Stochastic Gradient Descent

Read sections: 4.1, 4.3 (not 4.3.1 and 4.3.2), 4.4-4.4.2  and the following paper:
https://leon.bottou.org/publications/pdf/compstat-2010.pdf

Grab a binary classification dataset from UCI or other repository. 
- Divide your data into roughly 80% train, 10% validation, 10% test.
- Implement logistic regression with stochastic gradient descent as the optimization algorithm.
- Implement SGD without regularization and report your % correct on the test dataset.
- Implement SGD with regularization, select the best lambda parameter using the validation dataset, and report your % correct on the test dataset.

Plot the likelihood function with respect to iterations for unregularized and regularized on one set of axes. Which one converges to a higher likelihood, and why?

Optional, advanced things to try:
- Implement SGD with the L-1 penalty and use it for feature selection (it is not that hard actually)
- Compare SGD to Newton-Raphson by plotting the likelihood of both on one set of axes and explain why they are different.

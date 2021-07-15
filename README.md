# Calculating the stationary distribution

You can calculate the limiting stationary distribution for a Markov chain by sampling.  You can also extract this vector by calculating the principle left eigenvector of the transition matrix.  NumPy provides a function for calculating the eigenvalues and eigenvectors of a matrix.  In this exercise I am thus going to show you how you can use these tools to extract the stationary distribution for a Markov chain.

The first thing to do is to set a variable called `A` equal to the transition matrix below:

![](matrix.png)

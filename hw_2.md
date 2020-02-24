**Homework 2**

**Problem 1**

Implement a simulation of the Hadamard test for any qubit state |psi> and any single qubit unitary U using numpy.  Observe that you have 
to compute how the state of the quantum register changes. It is not enough to just code up the formula for the probabilities that we 
derived in class.

Recall that you can realize the controlled-U gate as follows: |0><0| otimes I + |1><1| otimes U. Use the numpy command 
[np.kron](https://docs.scipy.org/doc/numpy/reference/generated/numpy.kron.html) for the tensor product.  

For |psi> use the state |0> and for the unitary U use the orthogonal matrix that describes the rotation by angle 2 pi theta, where theta 
\[0, 1). 

Create a plot showing the probability Pr(0) in dependence on theta.

**Problem 2**

Implement a simulation of the SWAP test.

Use |psi1> = |0> and |psi2> = cos(2 pi theta) |0> + sin(2 pi theta) |1>. Create a plot showing the probability Pr(0) in dependence on 
theta.

# QOSF

Task 1 

Implement, on a quantum simulator of your choice, the following 4 qubits state |\psi>  
Where the number of layers, denoted with L, has to be considered as a parameter. We call ¨Layer¨ the combination of 1 yellow + 1 green block, so, for example, U1 + U2 is a layer. The odd/even variational blocks are given by:

Even blocks
Odd blocks
 
The angles \theta_{i,n} are variational parameters, lying in the interval (0, 2*pi), initialized at random. Double qubit gates are CZ gates.

Report with a plot, as a function of the number of layers, L, the minimum distance

\epsilon= min || |(\psi)> - |\phi> ||

Where |\phi> is a randomly generated vector on 4 qubits and the norm || | v> ||, of a state | v>, simply denotes the square root of the sum of the modulus square of the components of |v >. The right set of parameters \theta_{i,n} can be found via any method of choice (e.g. grid-search or gradient descent)

Bonus question:
Try using other gates for the parametrized gates and see what happens.

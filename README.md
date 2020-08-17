# QuantumRandomNumberGenerator
The code is exceedingly simple. The user provides the number of bits, after which the quantum program is run. 1 qubit (doesn't matter if at 1 or 0), is hadamard shifted, which puts the qubit in a state of superposition. The qubit is then measured, but the probability of observing a 1 or 0 are equivalent and the returned number is thus truly generated at random (though I'm not sure how random the qasm simulator is). This is repeated for the number of bits specified by the user, and then the bit array is converted into an numeric. 

This code was developed using the qiskit platform (https://qiskit.org), which makes coding these codes very simple in Python. 

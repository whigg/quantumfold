# QuantumFold
Quantum Annealing on 2D lattice protein folding with D'Wave's 2000Q Annealer 

# The Protein Folding Problem 
The Protein Folding Problem is characterized by the question on exactly how a protein’s amino acid sequence can determine its three-dimensional atomic structure. This sequence is a chain of amino acids from a combination of 20 available ones, with the length dependent on the type of protein (a human protein can be around 400 amino acids long). The computational complexity of this is huge, and as a result, our conventional ways of using classical machine learning techniques are extremely restricted due to computational size limits. This is the reason why the current drug discovery process is extremely slow, which can take around 10 years for a new discovery to be made. However, with the rise in the development of quantum computers and quantum technologies, the drug discovery process can have an exponential speed up due to the quantum nature of being able to compute superpositions of qubits (strings of both 0s and 1s) simultaneously.

# Approach
This approach utilizse quantum annealing in order to simulate 2D lattice protein folding. The advantage of using quantum annealing is its ability to find the lowest energy path (global optimum of a given function within a large search space) when creating a protein, which is ideal for optimization problems. 
This process will test the efficiency in the folding of amino acids in varying residue length in 3 different parts: 1) simulated annealing with the conventional Monte Carlo method 
2) simulated annealing with turn ancilla encoding on a regular CPU
3) quantum annealing with turn ancilla encoding on a QPU (quantum processing unit). This is completed with the 2000Q Annealer simulator from D'wave's Leap

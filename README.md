# Solving the Travelling Salesman Problem with QAOA and Cirq
## Georgiy Zemlevskiy
In the Travelling Salesman Problem (TSP) we are presented a graph of cities with weighted edges that represent the distance between the cities. We are then asked to find the shortest path, or Hamiltonian Cycle, in the graph that visits all the cities exactly once. This program uses the Quantum Approximate Optimization Algorithm (QAOA) to solve the TSP for 3 cities. The approach consists of a quantum circuit with multiple layers of parametrized cost and mixer operators applied to a quantum state, and the classical optimizer which modifies the parameters based on the circuit energy measurement. The Google Cirq framework is used to construct and manipulate the quantum circuit.

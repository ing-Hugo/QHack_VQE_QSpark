

Variational Quantum Eigensolver (VQE) is an algorithm for quantum chemistry using near-term quantum computers .
Tunable Gates & Tunable Circuits: Variational algorithms are ones with a circuit
that can be varied and rerun to produce better results each time. This is called a
tunable circuit and comes in many forms. Each form or template is called an
ansatz. Designing a good ansatz is the key to working with hybrid algorithms.

![image](https://user-images.githubusercontent.com/68777214/220974987-3f557806-07dc-4756-91e8-b61bd3946244.png)

The gate operations used in creating a tunable circuit can include:
i. Rx- This gate rotates 𝜃 radians around the x axis.
ii. Ry - This gate rotates 𝜃 radians around the y axis.
iii. Rz - This gate rotates 𝜃 radians around the z axis.
iv. CNOT - This gate is used to entangle qubits

![image](https://user-images.githubusercontent.com/68777214/220975619-5d5b095d-c989-4b7b-92dc-ffdeee79dd95.png)



![image](https://user-images.githubusercontent.com/68777214/220974060-45a7f5d7-7b33-4b6d-a094-323b89c8d53a.png)

Further readings and resources:
● Qiskit textbook page on VQE to simulate molecules
○ URL: https://qiskit.org/textbook/ch-applications/vqe-molecules.html
● Quantum Variational Eigensolver original paper
○ URL: https://arxiv.org/pdf/1304.3061.pdf
● Pennylane’s tutorial on VQE:
○ URL: https://pennylane.ai/qml/demos/tutorial_vqe.html

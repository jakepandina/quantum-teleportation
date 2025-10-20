# 🧠 Quantum Teleportation with Qiskit

This project implements and visualizes the **quantum teleportation protocol** using [Qiskit](https://qiskit.org/).  
Quantum teleportation allows the transfer of an **unknown qubit state** from one location (Alice) to another (Bob) using **entanglement** and **classical communication** — without physically moving the qubit itself.

---

## 🚀 Overview

In this notebook, I simulate the full teleportation process step-by-step:

1. **State Preparation** – Create an arbitrary qubit state (the one we want to teleport).  
2. **Entanglement Generation** – Use a Hadamard and CNOT gate to entangle two qubits between Alice and Bob.  
3. **Bell Measurement** – Alice performs quantum operations and measurements on her qubits.  
4. **Classical Communication** – Alice sends her two measurement results to Bob.  
5. **Reconstruction** – Bob applies conditional gates (X and Z) to recover the original state.  
6. **Verification** – Compare Bloch spheres and statevectors to confirm teleportation fidelity.

---

## 🧩 Key Features

- Full implementation of **quantum teleportation** in Qiskit  
- Step-by-step visualization of circuit evolution  
- **Bloch sphere** plots to show qubit state transfer  
- **Statevector comparison** to verify fidelity  
- Educational comments for understanding each part of the protocol  

---

## 🧪 Technologies Used

- **Python 3.10+**  
- **Qiskit** (Terra, Aer, and Visualization modules)  
- **NumPy**  
- **Matplotlib**

---

## 📘 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/jakepandina/quantum-teleportation.git
   cd quantum-teleportation
   ```
2.	Install dependencies:
   ```bash
   pip install qiskit numpy matplotlib
   ```
3.	Open the notebook or script:
   ```bash
   jupyter notebook
   ```

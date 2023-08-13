# IBM Quantum Challenges

This repository contains the solutions to the challenges hosted by IBM Quantum. The events have been organized folder wise. 

- `spring-2023` folder contains the files for IBM Quantum Challenge Spring 2023
- `qgss23` folder contains the lab solutions and lecture notes for the Qiskit Global Summer School 2023: From Theory To Implementation organised by IBM Quantum. 

## Current Status
[![contributor for this repository](https://img.shields.io/badge/contributor-tapashreepradhan-blue.svg)](https://github.com/tapashreepradhan/)

[![status of this version no. 1](https://img.shields.io/badge/status-finished-green.svg)](https://github.com/tapashreepradhan/ibm-quantum-challenge)
[![status of this version no. 2](https://img.shields.io/badge/status-final-green.svg)](https://github.com/tapashreepradhan/ibm-quantum-challenge)
[![status of this version no. 3](https://img.shields.io/badge/status-stable-green.svg)](https://github.com/tapashreepradhan/ibm-quantum-challenge)
[![status of this version no. 4](https://img.shields.io/badge/status-documentel-green.svg)](https://github.com/tapashreepradhan/ibm-quantum-challenge)

[![keyword of this version no. 1](https://img.shields.io/badge/keyword-quantum&nbsp;computing-purple.svg)]()
[![keyword of this version no. 2](https://img.shields.io/badge/keyword-quantum&nbsp;mechanics-purple.svg)]()
[![keyword of this version no. 3](https://img.shields.io/badge/keyword-quantum&nbsp;algorithms-purple.svg)]()
[![keyword of this version no. 4](https://img.shields.io/badge/keyword-quantum&nbsp;error&nbsp;correction-purple.svg)]()

[![technology used no. 1](https://img.shields.io/badge/built&nbsp;with-jupyter&nbsp;notebook-red.svg)](https://www.jupyter.org/)
[![technology used no. 2](https://img.shields.io/badge/built&nbsp;with-python-red.svg)](https://www.python.org/)
[![technology used no. 3](https://img.shields.io/badge/built&nbsp;with-ibm&nbsp;qiskit-red.svg)](https://www.qiskit.org/)
[![technology used no. 4](https://img.shields.io/badge/built&nbsp;with-ibm&nbsp;quantum&nbsp;experience-red.svg)](https://www.quantum-computing.ibm.com/)

## IBM Quantum Spring Challenge 2023

### Lab 1 : Intro to Dynamic Circuits

This lab consists of simple exercises where you will create small circuits to understand what dynamic circuits are and how they work. There will be also exercises about dynamic circuit gates that simulate the classical if statement. Finally we’ll introduce you to the "repeat until success" method.

### Lab 2: Quantum Teleportation

In this lab we’ll be sending a quantum message from one person to another. The only issue? Once a superposition is observed, the message is destroyed. This lab walks through the theory behind that problem, and the clever solution called Teleportation.

### Lab 3: Iterative Phase Estimation

Iterative Phase Estimation (IPE) is a variant of the phase estimation algorithm which requires the use of only one auxiliary qubit. Because it requires mid-circuit measurements and classical feedforward operations, IPE could not be executed on IBM Quantum hardware before the introduction of dynamic circuits. In this lab, we will use the newly introduced dynamic circuits capabilities to implement IPE.

### Lab 4:  Quantum Error Correction

In this lab we’ll dive into Error Correction, starting from how it’s used on classical data, and then demonstrating (some of) our approach for quantum computers. We’ll explore how to use a bit flip code, and conclude with a conversation about how to run error correction on a real device.

### Lab 5 : 127Q System

In the final lab we’ll explore how to combine our knowledge of dynamic circuits and error correction to create a GHZ state on one of IBM’s 127-qubit processors. You will try to modify the GHZ state with additional qubits as stabilizers. Please have patience, no one has ever offered a quantum computer of this type to the public before!

## Qiskit Global Summer School 2023: From Theory To Implementation

### Lab 1: Qiskit 101

In the first lab we will be exploring different ways of representing and manipulating quantum states using Qiskit, based on the quantum theory you learned in the first 3 lectures. We will cover important Qiskit classes including Operator, Statevector and QuantumCircuit, and learn how to use them to perform deterministic, probabilistic and unitary operations. Lastly we'll cover different ways of measuring quantum states using Qiskit.

### Lab 2: Creating Entanglement with Qiskit

In this lab, we explore interesting properties of entangled qubits. However, we first explore the Sampler and Estimator primitives to measure quasi-probability distributions (related to counts) and expectations of an observable, respectively. We then use the Estimator to measure an observable that violates the CHSH inequality, thereby disproving local hidden variable theories. Next, we build a quantum state and teleport it by entangling it with a shared resource, using the Sampler to show that we obtain the same quasi-probabilities from measuring both the prepared state and the teleported state.

### Lab 3: Diving in Quantum Algorithms

In this lab, we will be applying what we've learned so far about quantum algorithms to implement our own version of Quantum Phase Estimation as well as Shor's factoring algorithm. We will explore how increasing the number of qubits used to store the phase estimation changes the accuracy, as well as examine how this algorithm performs on real hardware. Afterwards, we will use your implementation of QPE to execute Shor's algorithm to find the prime factors of a small number. Each step will be walked through, and by the end we will have created a complete generalized function which can be run on the QasmSimulator.

### Lab 4: Iterative Phase Estimation

In this lab, you'll implement a simple version of the iterative phase estimation algorithm. Using the recently introduced dynamic circuits capabilities, you'll be able to run the algorithm on an IBM quantum processor!

### Lab 5: Error Mitigation with Qiskit Runtime

In this lab, we'll explore a few of the error mitigation options available through Qiskit Runtime. Specifically, we'll define a simple observable and initial state and use the Estimator primitive to measure the expectation value. Using noisy simulations, we'll explore the effect of different error mitigation strategies.

![qgss23](https://github.com/tapashreepradhan/ibm-quantum-challenge/assets/50409780/f487968b-fe58-40b7-9c0c-8ec34ae19a2b)


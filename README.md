# **Quantum Random Number Generator (QRNG)**  
### *IBM Qiskit Fall Fest 2025 – Hackathon Project*

This project implements a **Quantum Random Number Generator (QRNG)** using Qiskit and AerSimulator.  
It was developed as part of the **IBM Qiskit Fall Fest 2025 Hackathon**, where participants submitted a working quantum circuit that generates randomness through quantum measurement.

---

## **Overview**

The notebook generates quantum-random numbers through the following steps:

1. The user inputs:
   - Number of **qubits**
   - Number of **shots**
2. A quantum circuit is built with a Hadamard gate (`H`) applied to each qubit.
3. The qubits are measured, producing random classical outcomes.
4. The circuit is executed on **Qiskit AerSimulator**.
5. A histogram is plotted to visualize the distribution of measurement results.

This approach uses the **intrinsic randomness of quantum mechanics**, making the output fundamentally unpredictable.

---

##  **Key Features**
- User-defined qubit count and shot count  
- Automatic circuit generation  
- True quantum randomness from the Hadamard transform  
- Histogram visualization  
- Fully interactive via Jupyter Notebook  

---

## **Technologies Used**
- Qiskit  
- Qiskit Aer  
- Python  
- NumPy  
- Matplotlib  
- Jupyter Notebook  

---

##  **Screenshots**

### **Quantum Circuit**
![QRNG Circuit](screenshots/QRNG_Circuit.png)

### **Random Output Distribution**
![QRNG Histogram](screenshots/QRNG_Histogram.png)

---

## **Event Context**

This notebook was created and submitted for the  
**IBM Quantum – Qiskit Fall Fest 2025 Hackathon**,  
and was accepted as a correct and complete solution by the event organizers.

---

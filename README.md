# **Belief Propagation with Quantum Messages in Qiskit**

"This notebook is based on belief propagation with quantum messages for quantum-enhanced classical communication from the following paper: Rengaswamy, Narayanan, Kaushik P. Seshadreesan, Saikat Guha, and Henry D. Pfister. \"[Belief propagation with quantum messages for quantum-enhanced classical communications.](https://www.nature.com/articles/s41534-021-00422-1)\" npj Quantum Information 7.1 (2021): 97.

The approach builds on the concept of belief propagation, which is a classical algorithm for computing marginal probabilities of a graphical model. It is a popular decoding technique for messages encoded using LDPC codes. The key idea of quantum belief propagation is to interpret message-combining of classical belief propagation as \"channel combining\" rules, which allows for quantum messages. Local inference is performed using suitable unitary operations, whose outputs are quantum messages

In [BPQM_in_qiskit.ipyb](https://github.com/nayakanuj/QAP/blob/main/BPQM_in_qiskit.ipynb), we will implement Belief Propagation with Quantum Messages in Qiskit.

XOR Problem with MLP (Multi-Layer Perceptron)
Aim
This program aims to demonstrate the implementation and training of a Multi-Layer Perceptron (MLP) to solve the classic XOR (exclusive OR) problem. It showcases both a custom-built MLP using NumPy and an implementation using TensorFlow/Keras for comparison.

Dataset Used
The dataset used is the standard XOR truth table, which consists of four 2-dimensional input patterns and their corresponding single-bit outputs:

Inputs (X): [[0, 0], [0, 1], [1, 0], [1, 1]]
Expected Outputs (y): [[0], [1], [1], [0]]
Brief Note on Results
Both the custom NumPy-based MLP and the TensorFlow/Keras MLP successfully learned the XOR function after training for 10,000 and 1,000 epochs respectively. The custom MLP achieved outputs very close to the expected values (e.g., ~0.07 for 0 and ~0.93 for 1). The TensorFlow/Keras model achieved 100% accuracy, providing perfectly rounded predictions matching the XOR truth table. This demonstrates the capability of MLPs to model non-linear relationships like XOR.
# Physics-Informed-Quantum-ML
Predicting orbital mechanics using Classical Polynomial Regression and Variational Quantum Circuits (VQC)
# 🛰️ Physics-Informed Quantum Machine Learning (QML)
### Project: Orbital Velocity Prediction (The "Newton's Cannon" Experiment)

This project explores the intersection of **Classical Mechanics**, **Classical Machine Learning**, and **Variational Quantum Circuits (VQC)**. The goal is to predict the required orbital velocity for an object (like a satellite or even a planet) to stay in a stable orbit around Earth based on its altitude.

## 🌌 The Physics Challenge
According to Newton's Law of Universal Gravitation, the velocity $v$ required for a circular orbit is:
$$v = \sqrt{\frac{G \cdot M}{R + h}}$$
Where:
- $G$: Gravitational Constant
- $M$: Mass of Earth
- $R$: Radius of Earth
- $h$: Altitude

## 🤖 Hybrid AI Approach
I implemented two different models to "learn" this physical law from raw data:
1. **Classical ML:** A Polynomial Regression model (Degree 2) using `scikit-learn`.
2. **Quantum ML:** A Variational Quantum Circuit (VQC) built with `PennyLane`, using qubit rotations (RX, RY, RZ gates) to represent the gravitational decay.

## 📈 Key Results
- **Classical Accuracy:** R² Score ~ 0.999 (Near perfect fit).
- **Quantum Advantage:** The quantum model successfully learned the non-linear relationship using only **2 trainable parameters**, demonstrating high data representation density.

## 🛠️ Tech Stack
- **Languages:** Python
- **Quantum:** PennyLane
- **ML:** Scikit-Learn, NumPy, Pandas
- **Visualization:** Matplotlib

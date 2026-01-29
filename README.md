# Optimization Algorithms Comparison

A practical and educational project that compares the behavior and performance of classical optimization algorithms commonly used in machine learning and deep learning.

This project was developed as part of an academic assignment and focuses on understanding how different optimization strategies affect convergence speed, stability, and loss minimization.

---

##  Overview

Optimization algorithms play a critical role in training machine learning models. Choosing the right optimizer can significantly impact training efficiency and final performance.

This project provides a **side-by-side comparison** of multiple optimization algorithms applied to the same objective function, allowing clear and fair evaluation.

---

##  Algorithms Covered

The following optimization algorithms are implemented and analyzed:

- Gradient Descent (GD)
- Stochastic Gradient Descent (SGD)
- Momentum
- Nesterov Accelerated Gradient
- AdaGrad
- RMSProp
- Adam

Each algorithm is evaluated under the same conditions to highlight their differences in:
- Convergence behavior
- Stability
- Speed
- Loss minimization patterns

---

##  Experiments & Analysis

- All experiments are implemented in a single Jupyter Notebook for clarity.
- Loss curves are visualized to compare convergence trends.
- A detailed written report explains the theoretical background and experimental results.

---

##  Project Structure

optimization-algorithms-comparison/
│
├── notebooks/
│ └── optimization_algorithms_comparison.ipynb
│
├── report/
│ └── Optimization_Algorithms_Comparison_Report.docx
│
└── README.md

---

##  Key Takeaways

- Different optimizers behave very differently even on the same problem.
- Adaptive methods (Adam, RMSProp) converge faster but may be less stable.
- Classical methods (GD, Momentum) provide more predictable behavior.
- There is no universally best optimizer — the choice depends on the task.

---

##  Technologies Used

- Python
- NumPy
- Matplotlib
- Jupyter Notebook

---

##  Author

**Motasem Alwedyan**  
Artificial Intelligence Student  
Jordan University of Science and Technology (JUST)

---

##  Notes

This project is intended for educational and demonstration purposes and is suitable for:
- Students learning optimization techniques
- Beginners in machine learning
- Academic portfolios
- GitHub project showcases

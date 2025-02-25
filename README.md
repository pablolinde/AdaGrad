# Comparison of Optimization Methods

This notebook presents a comparison between different optimization methods:

- **Gradient without momentum**: Converges slowly and may oscillate in its trajectory.
- **Gradient with momentum**: Accelerates convergence and improves stability.
- **AdaGrad**: Automatically adjusts the learning rate, making it useful for problems with varying curvature in every direction.

The implementations are based on the book *Optimization for Machine Learning* by J. Brownlee.

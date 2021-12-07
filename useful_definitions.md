# Useful Definitions

#### What is the difference between an anomaly and an outlier ?

An anomaly is a result that can't be explained given the base distribution (an impossibility if our assumptions are correct). An outlier is **an unlikely event given the base distribution** (an improbability).

#### Positive Definite vs Positive Semi-Definitive Matrix

For a matrix  A to be positive semi-definite, the inequality below needs to hold: $\vec{x}^{T}A\vec{x}\geq0$

For positive definite , the condition is stronger:  $\vec{x}^{T}A\vec{x}>0$. This is useful for covariance matrices, as this is required for $p(\bold{x})$ to be a density (probability density function). Used in the multivariate Gaussian distribution.
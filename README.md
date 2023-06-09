# Change_CovFun
change point detection and estimation procedures for the covariance kernel of functional data based on the norms of a generally weighted process of partial sample estimates.

Reference: Change point analysis of covariance functions: a weighted cumulative sum approach, L. Horvath, G. Rice, Y. Zhao (2022) Journal of Multivariate Analysis.

We consider the objective data observations: $X_1(t), \dots, X_N(t)$, $t\in[0,1]$, where each functional observation $X_i(t)$ is a stochastic process with sample path in $L^2([0,1])$. The sequence $X_i(t)$ is assumed to follow the Data Generating Process: $X_i(t)= \mu(t)+\epsilon_i(t)$.

The code provided in this package aims to detect changes in the covariance function $C(t,s) = E\epsilon_i(t) \epsilon_i(s)$ via weighted CUSUM statistics.

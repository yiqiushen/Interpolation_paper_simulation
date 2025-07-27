# Interpolation_paper_simulation

This notebook reproduces the setting in **Minsker et al. (2021)** and shows how the empirical risk of Linear Discriminant Analysis grows relative to an interpolating minimum-norm classifier when the ambient dimension is much larger than the sample size.
The code follows the exact mixture model in Equation (1) of the paper "Minimax Supervised Clustering in the Anisotropic Gaussian Mixture Model: A new take on Robust Interpolation":

$$
Y_i \;=\; \theta\,\eta_i \;+\; W_i,\qquad 
\eta_i\in\{-1,1\},\; W_i\sim\mathcal N(0,\Sigma)\;.
$$

The experiment highlights the theorem that **LDA becomes minimax-suboptimal in the high-dimension regime $p\gg n$** ([arXiv][1]).

[1]: https://arxiv.org/pdf/2111.07041 "Minimax Supervised Clustering in the Anisotropic Gaussian Mixture Model: A new take on Robust Interpolation"

This package contains the algorithms of IRL when the behavior data is provided by multiple experts. 
The experiments are conducted in gridworld and highway problem.

- The Spectral algorithms are still under test.
- The DPM algorithms are described in [ChoiKim.12].
- The EM algorithms are described in [BabesETAL.11].

# Requirement
This package was built with Matlab R2013a.

# Package overview
- Spectral: merge the feature expectation based on SVD to build TF matrix and build cluster by reward matrix using the idea of pseudo inverse.
- BIRL: Finding a maximum-a-posterior (MAP) estimate in Bayesian framework for IRL [ChoiKim.11].
- DPM-BIRL: Extending BIRL with Dirichlet process mixture model to address IRL problems for multiple experts [ChoiKim.12].
- EM_IRL: Using expectation-maximization method to address IRL problems for multiple experts [BabesETAL.11].
- Ind_BIRL: Using MAP inference for BIRL on each trajectory to address IRL problems for multiple experts.

# Usage
Use the scripts whose filename starts with "run".

[ChoiKim.11] J. Choi and K. Kim, MAP inference for Bayesian inverse reinforcement learning, NIPS 2010.
[ChoiKim.12] J. Choi and K. Kim, Nonparametric Bayesian inverse reinforcement learning for multiple reward functions, NIPS 2011.
[BabesETAL.11] M. Babes-Vroman, V. Marivate, K. Subramanian, M. L. Littman, Apprenticeship learning about multiple intentions, ICML 2011.
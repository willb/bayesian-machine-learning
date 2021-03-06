## Bayesian machine learning notebooks

This repository is a collection of notebooks covering various topics of Bayesian methods for machine learning.

### Basics

- [Gaussian processes](gaussian_processes.ipynb). Introduction to Gaussian processes. Example implementations with 
plain NumPy/SciPy as well as with libraries scikit-learn and GPy.

- [Bayesian optimization](bayesian_optimization.ipynb). Introduction to Bayesian optimization. Example implementations 
with plain NumPy/SciPy as well as with libraries scikit-optimize and GPyOpt. Hyperparameter tuning as application example.  

- [Variational auto-encoder](variational_autoencoder.ipynb). A guide to variational auto-encoders described as a journey
from expectation maximization (EM) algorithm via variational inference to stochastic variational inference. Example 
implementation with Keras.

- ...

### Applications

- [Conditional generation via Bayesian optimization in latent space](variational_autoencoder_opt.ipynb). Describes an approach
for conditionally generating outputs with desired properties by doing Bayesian optimization in latent space of variational 
auto-encoders. Example application implemented with Keras and GPyOpt.

- ...

# Bayesian Structured Time Series Analysis with Parallel Tempering for Stock Market Prediction

## Overview
- An experimental project which implemented the Bayesian structured time series (BSTS) model using Langevin-gradients parallel tempering.
- Markov chain Monte Carlo (MCMC) methods were implemented in a parallel computing environment.
- Compare the stock price forecasting model with state-of-art neural network training algorithms (FNN-SGD and FNN-Adam)

## Specifications
- **data.py** - Used for data preprocessing.\
- **ann.py** - Desired parameters should be set in the artificial neural network to run the results.

## Output
- Following are some sample results of MMM’s stock price prediction.
- These are one-step, two-step, five-step prediction result and error analysis respectively.
- The grey area is the uncertainty of the prediction results.
<img src="https://github.com/issacjohannli/bayesian-structural-time-series-model/blob/main/results/readme_result_samples.png">
Figure 1: Sample outputs of MMM's stock price prediction 70 days from the time of analysis.

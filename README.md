## Uncertainty Analysis of Developed ANN in Prediction of Electrical Conductivity

# Abstract

One of the critical water quality indicators is Electrical Conductivity (EC) parameter. It is useful in mineralization and Total Dissolved Solids (TDS) estimation. This project aims to model daily EC values in Barwon River, Australia, by using Artificial Neural Network (ANN). For this purpose, three observed data including Turbidity, PH, and Temperature were used as predictors and observed EC values as predictand. In order to obtain the best structure, trial and error procedure was
used and different number of nodes, hidden layers with different activation functions were constructed. Afterward, bootstrapping method and Mont Carlo (MC) were employed respectively for parameter estimation and uncertainty analysis. The performance of best structures for test stage was 0.82 μs/cm and 0.8 in terms of RMSE and R, respectively. It was found that the
ANN was not able to estimate EC values accurately. Moreover, the uncertainty extent of each selected model for first 10 test data was estimated. Results showed that the extent of uncertainty of both selected models was low, with less than 20% of observed data lying within 10th and 90th percentile of MC outputs.

# Data
National Geochemical Survey of Australia: The Geochemical Atlas of Australia: [Public Dataset](https://data.gov.au/dataset/ds-ga-0dc4a02b-21e9-9b28-e053-12a3070af396/distribution/dist-ga-0dc4a02b-21e9-9b28-e053-12a3070af396-0/details?q=minerals) 

# Methodology

In order to uncertainty analysis for mineral exploration models the Bayesian approach can be applied, in which the posterior distribution of parameters is connected to the prior distribution of parameters. However, only if the underlying processes belong to the model space or that the model space is fully specified will the model parameters sampled based on a formal likelihood function be from a posterior parameter distribution. So the Bayesian approach cannot be generally evaluated by analytical means for complex Mineral exploration models. In recent years, the Markov Chain Monte Carlo (MCMC) method has been used to approximate the posterior distribution of the

The recent studies showed that Monte Carlo simulations are an effective method for characterizing uncertainty in circumstances where a considerable amount of data that describe the system dynamics is available. It is perhaps the most widely used probabilistic technique for propagating uncertainty in simple or complex models particularly mineral exploration models(Y. Jiang et al., 2013).

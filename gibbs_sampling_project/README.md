## Hierarchical Model using Gibbs Sampling 

This is the project to estimate failure rate of each pumps using Hierarchical Bayesian Model. Here, the model has Poisson likelihood with gamma priors for lambda and beta parameters. The goal is to use Gibbs sampling to compute posterior distribution of the parameters from the given data by iteratively sampling from conditional distributions of each parameter given current values of other parameters and the data. The data includes information on number of failures, observation time and the number of pumps.


## Getting Started

To run the hierarchical model using Gibbs Sampling for pump failure rate estimation, follow these steps:

1. **Prerequisites**: Ensure that you have the necessary software and dependencies installed, such as Python and relevant libraries (e.g., NumPy, Pandas, Matplotlib).

2. **Data Preparation**: Prepare your data in the required format. Ensure that you have information on the number of failures, observation time, and the total number of pumps.

3. **Configuration**: Adjust the model configuration parameters, such as the number of iterations and burn-in period, according to your requirements.

4. **Run the Model**: Execute the code to run the hierarchical model using Gibbs Sampling. Monitor the progress and convergence of the sampling process.

5. **Posterior Analysis**: Analyze the obtained posterior distribution to estimate the failure rates of individual pumps. Visualize the results and perform further analysis as needed.


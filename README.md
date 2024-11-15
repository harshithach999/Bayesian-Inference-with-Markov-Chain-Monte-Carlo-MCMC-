# Bayesian-Inference-with-Markov-Chain-Monte-Carlo-MCMC

# **Bayesian Inference on Titanic Survival Data**

## **Project Overview**
This project applies Bayesian inference to analyze the factors influencing the survival of passengers on the Titanic. Using **Markov Chain Monte Carlo (MCMC)** methods and the PyMC library, we create a probabilistic model to estimate survival probabilities and explore the relationships between key features and survival outcomes.

## **Key Objectives**
- To demonstrate the application of Bayesian inference using **Markov Chain Monte Carlo (MCMC)** algorithms.
- To develop a probabilistic model for estimating survival probabilities.
- To visualize posterior distributions of the parameters for actionable insights.

## **Technologies Used**
- **Python**: Core programming language.
- **PyMC**: For Bayesian modeling and MCMC sampling.
- **Pandas & NumPy**: Data manipulation and preprocessing.
- **Matplotlib & Seaborn**: Visualization of results.

## **Steps Involved**
1. **Data Preprocessing**:
   - Handled missing values.
   - Transformed categorical variables into numerical formats.
   - Selected relevant features for the analysis.
2. **Bayesian Model Definition**:
   - Built a probabilistic model using PyMC.
   - Included prior distributions for parameters based on domain knowledge.
3. **MCMC Sampling**:
   - Employed the **No-U-Turn Sampler (NUTS)** to estimate the posterior distributions.
4. **Posterior Analysis**:
   - Analyzed parameter estimates and interpreted the posterior distributions.
   - Visualized results for clarity and insight.

## **Results**
- The project provides posterior estimates for the impact of various features, such as passenger class, age, and gender, on survival probability.
- It demonstrates how Bayesian methods can integrate prior knowledge and quantify uncertainty in predictions.

## **Usage**
To replicate or extend this analysis:
1. Clone the repository.
2. Install the required libraries: `pip install pymc pandas matplotlib`.
3. Run the notebook to see the analysis step-by-step.

## **Future Scope**
- Expand the analysis to include additional features.
- Experiment with alternative MCMC algorithms or prior distributions.
- Compare Bayesian methods with frequentist approaches for further insights.

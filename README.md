# Funding_Success_Predictor

# Alphabet Soup Funding Predictor

## Prerequisites

Before diving into the project, make sure you have the following installed:

- Python (version 3.0 or higher)
- Jupyter Notebook (for running the analysis)
- Libraries: pandas, scikit-learn, and TensorFlow
  
## Overview

The Alphabet Soup Funding Predictor is a deep learning model designed to assist the nonprofit foundation Alphabet Soup in selecting funding applicants with the highest potential for success in their ventures. This repository contains the code for developing and evaluating the deep learning model.

## Data

The dataset used for training and testing the model contains information on over 34,000 organizations that have received funding from Alphabet Soup. Each organization is described by various features, including application type, affiliation, classification, use case, organization type, income amount, special considerations, funding amount requested, and the effectiveness of fund utilization.

## Approach

### Data Preprocessing

- **Target Variable**: The target variable for the model is `IS_SUCCESSFUL`, indicating whether the funding provided to an organization was utilized effectively.
- **Feature Variables**: The features used in the model include `APPLICATION_TYPE`, `AFFILIATION`, `CLASSIFICATION`, `USE_CASE`, `ORGANIZATION`, `INCOME_AMT`, `SPECIAL_CONSIDERATIONS`, and `ASK_AMT`.
- **Variables Removed**: The `EIN` and `NAME` columns were removed from the input data as they were neither targets nor features.

### Model Architecture

The deep learning model is constructed with two hidden layers. The first hidden layer has 50 neurons, and the second hidden layer has 30 neurons. Rectified Linear Unit (ReLU) activation functions are used for both hidden layers, while a sigmoid activation function is used for the output layer.

### Model Evaluation

The model achieved an accuracy of approximately 72.5% on the test data. Although falling slightly below the target performance of 75%, the model demonstrates reasonable predictive capability.

### Optimization Strategies

Attempts to improve model performance included adjusting hyperparameters such as the number of neurons and layers, as well as experimenting with different activation functions. Further optimization may be achieved through fine-tuning these hyperparameters or exploring more complex neural network architectures.

## Conclusion

The Alphabet Soup Funding Predictor provides valuable insights for Alphabet Soup in selecting funding applicants. While the current model demonstrates promising performance, there is room for improvement through continued optimization and exploration of alternative model architectures.

## Acknowledegments

Special thanks to [ChatGPT](https://www.openai.com/gpt) for providing assistance and guidance during the development of this project.

Special thanks to Berkely Data Analytics for providing code snippets and resources used in this project. [UC Berkeley Extension](https://extension.berkeley.edu/)

### Source Code

Special thanks to the contributors of the UCB-VIRT-DATA-PT-11-2023-U-LOLC GitHub repository for providing valuable code and resources used in this project.

## References

- IRS. Tax Exempt Organization Search Bulk Data Downloads. [https://www.irs.gov/](https://www.irs.gov/)



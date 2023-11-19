# DEEP LEARNING CHALLENGE

## Background:
The purpose of this repristory is to use my knowledge of machine learning and neural networks, in order to use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup. The goal is to predict the likelihood of success for applicants funded by Alphabet Soup using the features present in the provided dataset. The dataset, supplied by Alphabet Soup's business team, comprises information on over 34,000 organizations that have received funding from Alphabet Soup throughout the years. It includes various columns capturing metadata about each organization, including:
- EIN and NAME—Identification columns
- APPLICATION_TYPE—Alphabet Soup application type
- AFFILIATION—Affiliated sector of industry
- CLASSIFICATION—Government organization classification
- USE_CASE—Use case for funding
- ORGANIZATION—Organization type
- STATUS—Active status
- INCOME_AMT—Income classification
- SPECIAL_CONSIDERATIONS—Special considerations for application
- ASK_AMT—Funding amount requested
- IS_SUCCESSFUL—Was the money used effectively

## Written Analysis
    DATA PROCRESSING
Target Variable:
The model's target variable is "IS_SUCCESSFUL," signifying the success (1) or failure (0) of a charitable organization.

Feature Variables:
The feature variables encompass diverse input features utilized to forecast the success of charitable organizations. These features encompass:

Application data (e.g., status, ask amount).
Categorical variables (e.g., charity names, income amounts).
Variables to Exclude:
There is no need to exclude any variables from the input data, as all of them serve as either targets or features.

    COMPILING, TRAINING, AND EVALUATING THE MODEL
The neural network comprises three hidden layers with 10, 8, and 6 neurons, respectively. Activation functions applied in the hidden layers include "relu" and "sigmoid." The output layer utilizes a "sigmoid" activation function. The selection of this architecture is driven by the necessity for a model capable of capturing intricate patterns within the data. The model underwent training for 30 epochs, resulting in an accuracy of approximately 75.98% and a loss of 0.4877. However, the model's performance fell short of the target, suggesting potential room for improvement through further refinement.
### To improve performance, I undertook the following steps:
- Modified the model architecture by introducing additional layers or neurons to better capture intricate patterns.
- Experimented with various activation functions and optimization algorithms to identify the most effective configuration.
- Expanded the number of epochs and explored the use of a learning rate scheduler for more comprehensive training.
- Engaged in feature engineering to elevate the quality of input data.
- Implemented data balancing techniques to mitigate potential class imbalance.

      SUMMARY OF DEEP LEARNING MODEL PERFORMANCE:
The deep learning model demonstrated moderate accuracy in forecasting the success of charitable organizations but fell short of the target performance. To enhance model efficacy, it is advisable to explore diverse model architectures, hyperparameters, and data preprocessing techniques.

     CONSIDERATION OF ALTERNATIVE APPROACHES:
An alternative strategy involves investigating other machine learning algorithms, such as random forests, gradient boosting, or support vector machines, which may potentially capture underlying patterns more effectively in the provided data. Additionally, applying feature selection or dimensionality reduction techniques can refine the input variables and contribute to improved model performance.

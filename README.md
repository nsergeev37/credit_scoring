# Credit Risk Prediction Model

Machine learning solution for predicting loan defaults using optimized XGBoost.

## Project Description
This project compares multiple machine learning approaches for credit scoring:
- Tested XGBoost, Random Forest, and other boosting algorithms
- Optimized hyperparameters using F2-score  to prioritize default detection


## Repository Structure
credit-scoring/
├── notebooks/

│ ├── ML_scoring_preprocessing.ipynb # Data preprocessing

│ └── ML_scoring_training.ipynb # Model training and evaluation


├── data/


│ └── cleaned_data.csv # Processed dataset


└── README.md

## Key Results
**Best Model**: XGBoost with custom hyperparameters

| Metric        | Non-Default (0) | Default (1) |
|---------------|-----------------|-------------|
| Precision     | 0.95            | 0.78        |
| Recall        | 0.94            | 0.82        |
 


## How to Use
Run notebooks in order:

   ML_scoring_preprocessing.ipynb

   

   ML_scoring_training.ipynb


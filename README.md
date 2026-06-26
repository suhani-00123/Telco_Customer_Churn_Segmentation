## About the Project
The main goal of this project is to predict whether a customer is likely to leave a company (churn) or stay.

In this project, I worked on the complete workflow—from understanding the data and cleaning it to building machine learning models and analyzing the results. It helped me understand how real-world business problems can be solved using data.

## What I Did
Loaded and explored the customer dataset.
Cleaned the data by handling missing values and preparing it for analysis.
Performed Exploratory Data Analysis (EDA) to understand customer behavior.
Converted categorical data into numerical format.
Scaled the data for better model performance.
Trained multiple machine learning models.
Compared the models and selected the best-performing one.
Predicted customer churn probabilities.
Created customer segments using clustering.
Visualized important insights using graphs and charts.
## Tools & Technologies
Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

XGBoost

Jupyter Notebook
## Approach Used

#### 1.Handle class Imbalance
#### 2.Hyperparameter Tuning
#### 3.Feature Importance Analysis
#### 4.XGBoost Classifier
## Scores
| Approach                    | Accuracy | Precision |  Recall | F1-Score |
| --------------------------- | -------: | --------: | ------: | -------: |
| Handle Class Imbalance      |    80.5% |       69% |     50% |      58% |
| Hyperparameter Tuning       |    80.5% |       54% | **83%** |  **66%** |
| Feature Importance Analysis |    80.5% |       53% |     81% |      64% |
| XGBoost Classifier          |    80.5% |       68% |     51% |      58% |

## Final Model
After experimenting with different approaches, Hyperparameter Tuning was selected as the final approach because it achieved the highest Recall (83%) and F1-Score (66%) while maintaining an Accuracy of 80.5% and a ROC-AUC Score of 85%. This makes the model more effective at identifying customers who are likely to churn.

## Project Outcome

The project can identify customers who are more likely to leave the company. This can help businesses take early actions to improve customer retention and reduce churn.

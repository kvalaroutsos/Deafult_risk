# Default Risk Estimation

This project focuses on estimating default risk using data from Lending Club spanning the period from 2007 to 2014, obtained from Kaggle. The objective is to develop a model for evaluating risk.
Dataset with description is in the following link https://www.dropbox.com/s/tq3xz0piqitnc59/loan_data_2007_2014.csv?dl=0
## Data Preprocessing

The data underwent cleaning and preprocessing to prepare for model development.

## Model Evaluation

Two classification models were examined: Logistic Regression and Random Forest Classification.

### Logistic Regression Model

The logistic regression model showed promising performance metrics on the test data:

- Precision ratio for good loans: 98%
- Recall for good loans: 100%
- Precision for bad loans (defaults): Nearly 100%
- Recall for bad loans: 83%

This indicates that when the model predicts a borrower will default, it is highly accurate. However, there is a 17% false negative rate, meaning some defaults may be missed.

### Random Forest Model

The Random Forest model demonstrated similar results, with slightly improved performance in the recall rate for bad loans, achieving 85%.

## Conclusion

Both models show promise in predicting default risk, with the Random Forest model slightly outperforming the Logistic Regression model in certain aspects.

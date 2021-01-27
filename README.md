# Credit-Card-Fraud
Project on Credit card fraud detection techniques, Imbalanced Dataset

## Project Information
Classification on imbalanced dataset is not rare, Credit card fraud detection was one such. These scenarios are troublesome cause model brings poor results and evaluation metrics we use, such as accuracy does not give a very differentiable result due to very large majority cases.
This Project uses Precision Recall curve (PR curve) to evaluate model.

### File 1 : [CC_Fraud_EDA](https://github.com/kaustubhadixit/Credit-Card-Fraud/blob/main/CC_Fraud_EDA.ipynb)
* Scatter PLots, Historgrams to understand Class, Amount and Time.
* Finding the point of difference in fraudulent and non fraudulent cases.
* Correlation analysis.
   
### File 2 : [Preprocessing_and_Models](https://github.com/kaustubhadixit/Credit-Card-Fraud/blob/main/Preprocessing_and_Models.ipynb)
* Randomly split the dataset into train, validation, and test set.
* Resample the dataset(SMOTE).
* Predict and Evaluate using Original Dataset.
* Predict and Evaluate using Resampled Dataset.
* Comparing Predictions and choosing the best model
* Finding optimised threshold and report results in form of confusion matrix
        

Using PR AUC over ROC AUC cause PR does not account for true negatives therefore more suited for imbalanced classification.
**Clustered Random Forest is the best one!**

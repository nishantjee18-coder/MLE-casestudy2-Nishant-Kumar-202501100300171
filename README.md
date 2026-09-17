# MLE-casestudy2-Nishant-Kumar-202501100300171

## Case Study

Credit Card Fraud Detection using XGBoost, SMOTE, Threshold Tuning and SVM.

## Objective

The objective is to detect fraudulent credit card transactions using machine learning.

## Dataset

The dataset contains transaction records with features such as Time, V1-V28, Amount and Class.

Class:
- 0 = Normal Transaction
- 1 = Fraudulent Transaction

## Methodology

1. Load the dataset
2. Check class distribution
3. Split data into training and testing sets
4. Apply SMOTE to the training data
5. Train XGBoost classifier
6. Evaluate using classification report and ROC-AUC
7. Tune the decision threshold
8. Analyze feature importance
9. Train SVM as a baseline model
10. Compare XGBoost with SVM

## Models Used

- XGBoost
- SVM

## Techniques Used

- SMOTE
- Threshold Tuning
- Feature Importance
- ROC-AUC

## Technologies

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Imbalanced-learn
- XGBoost
- Google Colab
- GitHub

Logistic Regression - Breast Cancer Classification

This project is part of my AI & ML internship. The goal is to build a binary classifier using  logistic regression on the Breast Cancer Wisconsin Dataset to predict whether a tumor is benign or malignant.


Objective

To apply logistic regression for binary classification and evaluate the model using essential metrics like confusion matrix, precision, recall, and ROC-AUC curve.



 Dataset

- Name: Breast Cancer Wisconsin (Original)
  Source: [UCI Machine Learning Repository]
- Instances: 699 samples
- Features: 10 numeric attributes




 Technologies & Libraries Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
-  Seaborn

 Steps Performed

1. Data Preprocessing
   - Removed ID column
   - Handled missing values in 'Bare_Nuclei'
   - Converted class labels to binary (0, 1)

2. Train-Test Split
   - Used `train_test_split` from Scikit-learn

3. Feature Scaling
   - Applied `StandardScaler` for normalization

4. Model Building
   - Trained a Logistic Regression model using `LogisticRegression()`

5. Evaluation
   - Confusion matrix
   - Classification report (precision, recall, F1-score)
   - ROC curve and AUC
   - Sigmoid function visualization




# AI & ML Internship – Task 9
## Random Forest – Credit Card Fraud Detection

### Overview
This task focuses on detecting fraudulent credit card transactions using
a Random Forest classifier. Due to the imbalanced nature of fraud data,
evaluation was performed using precision, recall, and F1-score.

### Dataset
- Credit Card Fraud Dataset
- Source: Kaggle
- File used: creditcard.csv
- Target variable: Class (0 = Normal, 1 = Fraud)

### Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

### Steps Performed
- Loaded and explored the dataset
- Analyzed class imbalance
- Split data using stratified sampling
- Trained a baseline Logistic Regression model
- Trained a Random Forest model
- Compared models using precision, recall, and F1-score
- Visualized confusion matrix and feature importance
- Saved the trained model for reuse

### Conclusion
Random Forest performed significantly better than Logistic Regression
for fraud detection. Feature importance analysis helped identify key
patterns contributing to fraudulent transactions.

### Learning Outcome
- Understanding ensemble learning
- Handling imbalanced datasets
- Importance of evaluation metrics beyond accuracy
- Practical experience with Random Forest

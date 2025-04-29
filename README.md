# Task_4

# Logistic Regression - Breast Cancer Classification

It is a **binary classification model** using **Logistic Regression** to classify breast cancer tumors as malignant or benign using the Breast Cancer Wisconsin Dataset.

## Dataset
- Used dataset: `data.csv` (Breast Cancer Wisconsin Dataset)
- Target column: `diagnosis` (Malignant = 1, Benign = 0)
- Features: 30 numeric features related to tumor characteristics

## Tools & Libraries
- Python
- Pandas
- Scikit-learn
- Matplotlib / Seaborn

## Steps Performed
1. **Data Cleaning**
   - Removed ID and unnamed columns
   - Encoded target variable
2. **Preprocessing**
   - Train-test split
   - Standardized features using `StandardScaler`
3. **Model Training**
   - Used `LogisticRegression` from `sklearn`
4. **Evaluation Metrics**
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-score)
   - ROC Curve & AUC Score
5. **Visualization**
   - ROC Curve plotted to visualize model performance

## Result
- Achieved high accuracy and ROC-AUC score
- Well-performing classifier for medical diagnosis

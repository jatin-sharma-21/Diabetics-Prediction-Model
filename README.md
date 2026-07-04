# 🩺 Diabetes Prediction using Logistic Regression

A Machine Learning project that predicts whether a patient is likely to have diabetes using the Logistic Regression algorithm. The project includes data exploration, model training, evaluation, ROC curve analysis, and cross-validation.

---

## 📌 Project Overview

This project uses the **Pima Indians Diabetes Dataset** to build a binary classification model that predicts diabetes based on several medical features.

The workflow includes:
- Data loading and exploration
- Data visualization
- Train-test split
- Logistic Regression model training
- Performance evaluation
- ROC Curve visualization
- 5-Fold Cross Validation

---

## 📂 Dataset

The project uses the **Pima Indians Diabetes Dataset** (`diabetes.csv`).

### Features

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

### Target Variable

- **Outcome**
  - 0 → Non-Diabetic
  - 1 → Diabetic

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Exploratory Data Analysis

The project performs:

- Dataset inspection
- Statistical summary
- Class distribution visualization
- Feature preparation for model training

---

## 🤖 Machine Learning Model

**Algorithm Used**

- Logistic Regression

### Train-Test Split

- Training Data: 80%
- Testing Data: 20%
- Random State: 42

---

## 📈 Model Evaluation

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC Curve
- AUC Score
- 5-Fold Stratified Cross Validation

### Test Accuracy

**Accuracy:** **77.04%**

**F1 Score:** **0.63**

Cross-validation is also performed to measure the model's stability across different data splits.

---

## 📉 ROC Curve

The project plots the Receiver Operating Characteristic (ROC) Curve to evaluate the model's ability to distinguish between diabetic and non-diabetic patients.

---

## 📁 Project Structure

```
Diabetes-Prediction/
│
├── diabetes.csv
├── logisticregressionmodel_diabetes_prediction.py
├── README.md
└── requirements.txt (optional)
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Diabetes-Prediction.git
```

Move into the project directory:

```bash
cd Diabetes-Prediction
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Run the project:

```bash
python logisticregressionmodel_diabetes_prediction.py
```

---

## 📌 Results

- Successfully trained a Logistic Regression classifier.
- Achieved approximately **77% testing accuracy**.
- Evaluated using multiple classification metrics.
- Validated using **5-Fold Stratified Cross Validation** for improved reliability.

---

## 🚀 Future Improvements

- Feature Scaling
- Hyperparameter Tuning
- Handling Missing/Zero Values
- Compare with Random Forest, XGBoost, SVM, and Decision Trees
- Deploy using Flask or Streamlit
- Build an interactive web application



## 📜 License

This project is intended for educational and learning purposes.

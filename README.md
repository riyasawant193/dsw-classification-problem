# Classification problem for Loan Default Prediction
This repository contains a comprehensive machine learning solution to a classification problem for a Non-Banking Financial Company (NBFC). The project aims to predict loan defaulters using a classification model, leveraging historical loan data. The goal is to assist the NBFC in streamlining its loan approval process and mitigating financial risks.



## Problem Statement
The task is to predict whether a loan applicant is likely to default based on historical loan data. The dataset contains customer demographics, loan specifics, financial behavior, and credit history. The key challenge lies in handling the class imbalance and extracting meaningful insights to build a reliable predictive model.

---

## Project Structure

```
📂 dsw-classification-problem
├── 📁 Datasets
│   ├── train.csv       # Training dataset
│   ├── test.csv        # Test dataset
├── 📁 Solution notebook
│   ├── EDA.ipynb                                               # Exploratory Data Analysis
│   ├── Riya Rajesh Sawant DSW_Classification_Problem.ipynb     # EDA & Model building and evaluation
│   ├── performance metrics results.png
├── 📁 Problem Statement
│   ├── DSW_ML_Problem_Statement
├── Riya Rajesh Sawant.zip
├── README.md           # Project overview (this file)
└── requirements.txt    # Dependencies
```

---

## Workflow

1. **Exploratory Data Analysis (EDA):**
   - In-depth analysis of data distribution, correlations, and feature importance.
   - Visualizations to identify skewness and class imbalance.

2. **Data Preprocessing:**
   - Standardized numerical features and encoded categorical variables.
   - Addressed class imbalance using SMOTE (Synthetic Minority Oversampling Technique).

3. **Modeling:**
   - Built and evaluated multiple machine learning models:
     - Naive Bayes
     - Logistic Regression
     - Random Forest
     - Decision Tree
     - K-Nearest Neighbors (KNN)
     - XGBoost

4. **Evaluation:**
   - Used metrics such as Accuracy, Precision, Recall, F1-Score, and ROC-AUC.
   - XGBoost achieved the best performance:
     - Accuracy: **0.72** (Highest among all models)
     - Precision: **0.79** (Moderate precision)
     - Recall: **0.84** (Best at capturing defaulters)
     - F1-Score: **0.81** (Balanced precision and recall)
     - ROC-AUC: **0.60** (Room for improvement in class separability).

5. **Results:**
Performance of various models across key metrics:

![performance metric results](https://github.com/user-attachments/assets/e123124e-53dd-4a33-80cd-af43c90ab8dc)

---

## Installation and Usage

### Prerequisites
Ensure you have the following installed:
- Python 3.7+
- pip

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/riyasawant193/dsw-classification-problem.git
   ```
2. Navigate to the project directory:
   ```bash
   cd dsw-classification-problem
   ```
3. Run the notebooks or scripts to reproduce results:
   - EDA: `Solution notebook/EDA.ipynb`
   - Modeling: `Solution notebook/Riya Rajesh Sawant DSW_Classification_Problem.ipynb`




# 🏠 House Price Prediction using Scikit-Learn

## 📌 Project Overview

This project was built as a **beginner-friendly, end-to-end Machine Learning workflow** using **Scikit-Learn**.

Rather than focusing solely on prediction accuracy, the primary objective of this project is to understand how a typical machine learning regression project is structured—from loading the dataset to preprocessing, model training, and evaluation.

> **Note:** The dataset used in this project is **synthetic** and was created for educational purposes. Therefore, the poor evaluation metrics are expected and do not reflect the correctness of the implemented workflow.

---

# 🎯 Who is this project for?

This repository is intended for:

* Beginners learning Machine Learning with Scikit-Learn
* Students looking for an end-to-end ML workflow reference
* Anyone confused about the correct order of preprocessing steps
* Learners who want a simple notebook demonstrating EDA, preprocessing, pipelines, and model evaluation

---

# 📖 What You'll Learn

* Load and inspect a dataset
* Perform Exploratory Data Analysis (EDA)
* Analyze numerical and categorical features
* Perform Univariate, Bivariate and Multivariate Analysis
* Handle categorical variables using different encoding techniques
* Apply feature scaling
* Split data into training and testing sets
* Build preprocessing workflows using **ColumnTransformer**
* Create reusable Machine Learning Pipelines
* Train multiple regression models
* Evaluate model performance using standard regression metrics

---

# 🚀 Machine Learning Workflow Covered

```text
Load Dataset
      ↓
Exploratory Data Analysis (EDA)
      ↓
Feature Engineering
      ↓
Train-Test Split
      ↓
Feature Scaling
      ↓
Categorical Encoding
      ↓
ColumnTransformer
      ↓
Pipeline
      ↓
Model Training
      ↓
Prediction
      ↓
Model Evaluation
```

---

# 📊 Exploratory Data Analysis (EDA)

The notebook demonstrates several commonly used EDA techniques, including:

### Dataset Inspection

* Dataset overview
* Shape of the dataset
* Data types
* Summary statistics
* Random sampling

### Data Quality Checks

* Missing values
* Duplicate values

### Univariate Analysis

* Numerical feature distribution
* Categorical feature distribution
* Histograms
* KDE plots
* Box plots
* Count plots

### Bivariate Analysis

* Scatter plots
* Box plots
* Violin plots
* Bar plots
* Heatmaps
* Crosstabs
* Pivot Tables

### Multivariate Analysis

* Correlation Matrix
* Pair plots
* Heatmaps
* Multiple feature relationships

---

# ⚙️ Feature Engineering

The notebook demonstrates:

* Removing unnecessary features
* Train-Test Split
* Feature Scaling using **StandardScaler**
* Ordinal Encoding
* One-Hot Encoding
* ColumnTransformer
* Pipeline

---

# 🤖 Models Implemented

The following regression models are trained and evaluated:

* Linear Regression
* Random Forest Regressor
* Support Vector Regressor (SVR)
* K-Nearest Neighbors Regressor (KNN)

---

# 📈 Evaluation Metrics

The models are evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

Since the dataset is synthetic, low performance is expected across different regression models.

---

# 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

# 📂 Project Structure

```text
House-Price-Prediction/
│
├── eda.ipynb
├──traintest.ipynb
├── House Price Prediction Dataset.csv
├── README.md
└── requirements.txt
```

---

# 💡 Key Takeaways

Through this project, I gained hands-on experience with:

* Understanding the complete Machine Learning workflow
* Performing data preprocessing
* Applying different encoding techniques based on feature type
* Building reusable preprocessing pipelines
* Comparing multiple regression models
* Evaluating regression models using standard metrics
* Writing clean, structured, and reproducible Scikit-Learn code

---

# 🔮 Future Improvements

* Train the workflow on real-world housing datasets (e.g., Ames Housing or California Housing)
* Perform hyperparameter tuning using GridSearchCV
* Implement feature selection techniques
* Compare additional regression algorithms
* Deploy the trained model as a web application

---

## ⭐ If you found this project useful

If you're also learning Machine Learning, feel free to fork this repository, explore the notebook, and experiment with different preprocessing techniques and regression models.

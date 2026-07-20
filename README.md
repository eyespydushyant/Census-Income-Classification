# Adult Income Classification using Machine Learning

A machine learning project that predicts whether an individual's annual income exceeds **$50K** based on demographic and employment-related information. The project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis, feature engineering, model building, evaluation, and comparison.

---

## Project Overview

The Adult Income dataset, derived from the 1994 U.S. Census, contains demographic and work-related attributes such as age, education, occupation, marital status, work hours, and capital gain/loss.

The objective of this project is to build classification models that can accurately predict whether a person's annual income is:

- **<= 50K**
- **> 50K**

---

## Problem Statement

Income prediction plays an important role in understanding socio-economic trends. A reliable classification model can assist governments, researchers, and organizations in analyzing income distribution and identifying the factors associated with higher earnings.

This project applies machine learning techniques to build predictive models and compare their performance.

---

## Dataset Information

- **Dataset:** Adult Income Dataset
- **Source:** UCI Machine Learning Repository
- **Records:** ~48,000+
- **Features:** 14 input features
- **Target Variable:** Income

Target Classes:

- <=50K
- >50K

---

## Project Workflow

- Data Understanding
- Data Cleaning
- Missing Value Handling
- Duplicate Removal
- Feature Engineering
- Exploratory Data Analysis
- Feature Encoding
- Feature Scaling
- Model Training
- Hyperparameter Optimization
- Model Evaluation
- Model Comparison

---

## Exploratory Data Analysis

Several visualization techniques were used to better understand the dataset, including:

- Histograms
- Count Plots
- Box Plots
- Correlation Heatmap
- Word Clouds
- Treemap
- Sunburst Chart
- Sankey Diagram
- Andrew Curves
- Parallel Coordinates
- Interactive 3D Scatter Plot (Plotly)

These visualizations helped identify important relationships between demographic attributes and income levels.

---

## Machine Learning Models

The following supervised learning algorithms were implemented:

- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)

Different hyperparameter optimization techniques were applied to improve model performance.

---

## Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix
- ROC Curve
- Precision-Recall Curve
- Cross Validation

---

## Key Findings

- Random Forest produced the best overall performance.
- Education level, Capital Gain, Age, Marital Status, and Hours per Week were among the most influential features.
- Feature scaling improved the performance of distance-based algorithms.
- Hyperparameter tuning enhanced model accuracy and generalization.

---

## Technologies Used

**Programming Language**

- Python

**Libraries**

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- WordCloud
- Scikit-learn

**Machine Learning**

- Logistic Regression
- Random Forest
- Support Vector Machine
- GridSearchCV
- RandomizedSearchCV






## Results

Among the implemented models, **Random Forest Classifier** achieved the best overall performance by providing the highest accuracy and balanced evaluation metrics. Feature importance analysis also made the model more interpretable by identifying the variables that contributed most to the prediction.

---

## Future Improvements

- Experiment with XGBoost and LightGBM
- Perform advanced feature selection
- Deploy the model using Streamlit or Flask
- Build an interactive dashboard for income prediction
- Explore explainable AI techniques such as SHAP and LIME

---

## Author

**Dushyant Sharma**

Computer Science Student

Interested in Machine Learning, Data Science, and Full-Stack Development.

GitHub: https://github.com/eyespydushyant

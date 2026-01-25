# Student Outcome Classification

## Overview
This project builds and evaluates multiple supervised machine learning models to predict student success outcomes in higher education.  

The target variable represents whether a student **drops out**, **remains enrolled**, or **graduates**.

The project follows an end-to-end machine learning workflow including data preprocessing, exploratory data analysis (EDA), model training, model evaluation, and model comparison.

## Dataset
The dataset used in this project comes from Kaggle:

**Higher Education Predictors of Student Retention**  
https://www.kaggle.com/datasets/thedevastator/higher-education-predictors-of-student-retention

The raw dataset includes demographic, academic performance, and socioeconomic features related to student performance and retention of first-year college students.


## Project Structure
```
student-outcome-classification/
├── data/
│   ├── raw/
│   │   └── student_data_raw.csv                    # Original dataset from Kaggle
│   └── processed/
│       └── student_data_processed.csv              # Cleaned and preprocessed dataset
├── notebooks/
│   ├── 00_run_in_colab.ipynb                       # Interactive notebook for user execution. 
│   ├── 01_data_preprocessing_and_cleaning.ipynb    # Cleaned and preoprocessed the raw student dataset in preparation for modeling. 
│   ├── 02_exploratory_data_analysis.ipynb          # Performed EDA using a multiple linear regression model.
│   ├── 03_logistic_regression_model.ipynb          # Implements a multinomial logistic regression model. 
│   ├── 04_gradient_boosting_model.ipynb            # Implements a gradient boosting classifier model. 
│   └── 05_model_comparison_and_conclusions.ipynb   # Compares both models and summarizes findings. 
└── README.md
```

## Models Implemented
- Multiple Linear Regression (EDA only)
- Multinomial Logistic Regression
- Gradient Boosting Classifier

Models are evaluated using accuracy, classification reports, and confusion matrices.

## Technologies & Tools Used

**Programming & Environment**
- Python
- Jupyter Notebook
- Google Colab

**Data Analysis & Machine Learning**
- Pandas
- NumPy
- Scikit-learn
- SciPy
- Matplotlib
- Seaborn

**Models & Techniques**
- Gradient Boosting Classifier (Ensemble Learning)
- Multinomial Logistic Regression
- Exploratory Data Analysis (EDA)
- Multiple Linear Regression 
- Feature Scaling & Encoding
- Cross-Validation & Hyperparameter Tuning

**Interface**
- ipywidgets (interactive UI)

## How to Run
1. Open `00_run_in_colab.ipynb`
2. Follow the setup instructions
3. Run notebooks in numerical order



# Employee Salary Prediction using Machine Learning

This project predicts employee salaries based on various features using machine learning models. It was developed as part of the IBM Edunet Foundation SkillsBuild AI/ML Internship. The goal is to demonstrate the complete ML workflow from data preprocessing to model deployment.

## Project Overview

Salary prediction helps HR departments make data-driven decisions regarding compensation. This project uses demographic and work-related data to train a regression model capable of estimating an employee's salary.

Features used include:
- Age
- Education
- Workclass
- Hours per week
- Capital gain and loss
- Native country
- and more...

## Tech Stack

- Python 3
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Joblib (for model serialization)
- Jupyter Notebook
- (Optional: Streamlit for deployment)

## Repository Structure

salary-prediction-ibm/
│
├── model/
│ └── salary_prediction_model.pkl # Trained model file
│
├── notebooks/
│ └── prediction.ipynb # Model training and evaluation
│
├── app.py # Optional app for prediction interface
├── requirements.txt # Required Python libraries
├── README.md # Project description
└── .gitignore # Files to ignore in version control


## How to Run

1. Clone the repository:

git clone https://github.com/<your-username>/salary-prediction-ibm.git
cd salary-prediction-ibm


2. Install dependencies:

pip install -r requirements.txt


3. Launch the notebook:

jupyter notebook notebooks/prediction.ipynb


## Internship Information

This project was completed as part of the IBM Edunet SkillsBuild AI/ML Internship program. It reflects core concepts learned during the training, including supervised learning, data preprocessing, model evaluation, and deployment readiness.

## Author

J M Rahmaan  
IBM Edunet AI/ML Intern


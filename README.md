# Employee Salary Analysis and Prediction

Welcome to the Employee Salary Analysis and Prediction project! This project aims to analyze and predict the salaries of employees based on various features such as age, gender, education level, job title, and years of experience.

## Introduction

In this project, we aim to analyze and predict the salaries of employees based on various features such as age, gender, education level, job title, and years of experience. Understanding these factors can help in making informed decisions regarding salary structures and identifying potential disparities or trends within the company.

### Project Goals

1. **Data Exploration and Visualization**: Gain insights into the dataset by exploring and visualizing the distributions and relationships of different features.
2. **Data Preprocessing**: Prepare the data for machine learning by handling missing values, duplicates, and encoding categorical variables.
3. **Model Training and Evaluation**: Train multiple machine learning models to predict employee salaries and evaluate their performance.

## About the Dataset

This dataset contains information about the salaries of employees at a company. Each row represents a different employee, and the columns include information such as age, gender, education level, job title, years of experience, and salary. The dataset can be sourced from [Kaggle](https://www.kaggle.com/datasets/rkiattisak/salaly-prediction-for-beginer/data).

### Columns

- **Age**: Represents the age of each employee in years. The values in this column are numeric.
- **Gender**: Contains the gender of each employee, which can be either male or female. The values in this column are categorical.
- **Education Level**: Contains the educational level of each employee, which can be high school, bachelor's degree, master's degree, or PhD. The values in this column are categorical.
- **Job Title**: Contains the job title of each employee. The job titles can vary depending on the company and may include positions such as manager, analyst, engineer, or administrator. The values in this column are categorical.
- **Years of Experience**: Represents the number of years of work experience of each employee. The values in this column are numeric.
- **Salary**: Represents the annual salary of each employee in US dollars. The values in this column are numeric and can vary depending on factors such as job title, years of experience, and education level.

### Dataset Source

The dataset is available on Kaggle: [Salary Prediction for Beginners](https://www.kaggle.com/datasets/rkiattisak/salaly-prediction-for-beginer/data).

## Notebook

The code used for this analysis and prediction is available in the Jupyter Notebook: [salary.ipynb](salary.ipynb).

## Prediction App

I have developed a prediction app in Python that can be run locally. This app uses the trained model to predict employee salaries based on input features. You can find the code for the prediction app here: [prediction_app.py](https://github.com/ninogarcia/Employee-Salary-Analysis-and-Prediction/blob/main/prediction%20app.py).

Make sure that the `model.pkl` file is in the same folder as the prediction app. You can find the `model.pkl` file here: [model.pkl](https://github.com/ninogarcia/Employee-Salary-Analysis-and-Prediction/blob/main/model.pkl).

### Running the Prediction App Locally

To run the prediction app locally, execute the following command:

```bash
python prediction_app.py
```

## Acknowledgements

- Thanks to [Kaggle](https://www.kaggle.com/) for providing the dataset.



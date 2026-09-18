# Student Performance Predictor

## Overview

Student Performance Predictor is a simple machine learning project that predicts a student's exam score using four inputs:

- Study hours
- Sleep hours
- Attendance
- Phone usage

The project uses Linear Regression to learn the relationship between these inputs and the exam score.

## Objectives

- Load student data from a CSV file
- Select relevant features
- Split the data into training and testing sets
- Train a Linear Regression model
- Take student details as input
- Predict the expected exam score

## Technologies Used

- Python
- Pandas
- Scikit-learn
- GitHub

## Machine Learning Model

The project uses Linear Regression because the output being predicted is a numerical exam score.

### Input Features

| Feature | Description |
|---|---|
| study_hours | Study hours per day |
| sleep_hours | Sleep hours |
| attendance | Attendance percentage |
| phone_usage | Phone usage in hours |

### Target

`exam_score`

## How the Project Works

1. The program loads `data.csv`.
2. The input features and target value are selected.
3. The dataset is divided into training and testing data.
4. A Linear Regression model is trained.
5. The user enters student details.
6. The trained model predicts the exam score.
7. The predicted score is displayed.

## How to Run

Install the required libraries:

```bash
pip install pandas scikit-learn

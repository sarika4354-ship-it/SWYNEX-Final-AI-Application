# SWYNEX-Final-AI-Application

## Project Title
AI-Based Student Performance Risk Prediction

## Problem Statement
Students with low attendance, study hours, previous marks, or assignment scores may be at academic risk. This project uses AI to identify potential performance risk based on these factors.

## Objective
The objective is to develop a beginner-friendly AI application that predicts student performance risk using machine learning.

## Method
A Decision Tree Classifier is used to classify student performance based on:
- Study Hours
- Attendance
- Previous Mark
- Assignment Score

## How It Works
1. Student performance data is provided as input.
2. The required features are selected.
3. The Decision Tree model processes the input.
4. The system predicts the student's performance category.
5. Invalid inputs are handled with appropriate error messages.

## Demo
Example Input:
- Study Hours: 3
- Attendance: 65
- Previous Mark: 55
- Assignment Score: 60

Example Output:
- Prediction: Fail

## Evaluation
The model is evaluated using Accuracy Score on the provided dataset.

Example evaluation result:
- Model Accuracy: 100.0%

## Limitations
- The dataset is synthetic and limited in size.
- The model may not perform the same way on real-world student data.
- Prediction depends on the quality of the input data.

## Ethical Considerations
- Student data should be kept private and secure.
- AI predictions should support academic guidance and should not be used as the only basis for important decisions.
- The system should avoid unfair treatment based on predicted risk.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Decision Tree Classifier
- Google Colab

## Project Outcome
The project demonstrates a complete beginner-friendly AI application for student performance risk prediction with model evaluation, error handling, limitations, and ethical considerations.

## Internship
This project is completed as part of the **SWYNEX Technologies Internship – Task 4**.

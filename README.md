# AI-Semester-Project-Insurance
Flask-based ML model for Insurance Risk Prediction - Spring 2025

A Flask-based machine learning web application for predicting whether an insurance customer is **high risk** or **low risk** based on personal and vehicle data.

> Developed as the semester project for the Artificial Intelligence course (BS-F22), Spring 2025 – Assigned by *Mr. Mustajab Hussain*.


## 🔍 Project Overview

Insurance companies face challenges in fairly assessing driver risk. Using machine learning, we built a predictive model that classifies whether a customer is likely to file a claim. Our solution includes:

- Clean data preprocessing
- Multiple model comparisons (Random Forest, ANN)
- A beautiful and responsive web app built with Flask



## 📊 Features of the Web App

- **Page 1 – Data Analysis**: Summarizes the dataset structure, missing values, and feature breakdown.
- **Page 2 – Preprocessing**: Shows steps like missing value imputation, encoding, and class balancing.
- **Page 3 – Visualization**: Displays histograms, heatmaps, boxplots, correlation matrix, and more.
- **Page 4 – Prediction**:
  - Input form for new data
  - Output: High Risk / Low Risk
  - Model evaluation: accuracy
- **Page 5 – About Us**: Introduces the project team



## 🧠 ML Models Used

| Model           | Accuracy |
|----------------|----------|
| Random Forest  | 96.32%   |
| ANN (Neural Net)| 96.12%  |

 Random Forest outperformed others in our case.



## 📁 Folder Structure

project/
│
├── app.py               # Main Flask app
├── model/               # Contains trained models (.pkl)
├── static/              # CSS, JS, images
├── templates/           # HTML pages          
├── .gitignore
└── README.md

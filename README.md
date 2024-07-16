# Diabetes Prediction Project
# Overview
This project aims to predict whether a patient has diabetes based on various medical parameters. The dataset used is the PIMA Indian Diabetes dataset. We have explored the data, preprocessed it, and implemented multiple machine learning models to predict diabetes. The models used include Logistic Regression, K-Nearest Neighbors (KNN), and Support Vector Machine (SVM). We also compared the accuracy of these models.
# Table of Contents
     Installation
     Data
     Exploratory Data Analysis
     Preprocessing
     Modeling
     Logistic Regression
     K-Nearest Neighbors (KNN)
     Support Vector Machine (SVM)
     Model Comparison
     Results
     Contributing
     License
     Installation
# Navigate to the project directory:
     cd diabetes-prediction
     Install the required packages:
     pip install -r requirements.txt
# Data Description 
The dataset consists of  100000 observations with 9 attributes:
     Pregnancies
     Glucose
     Blood Pressure
     Skin Thickness
     Insulin
     BMI
     Diabetes Pedigree Function
     Age
     Outcome (0 or 1 indicating absence or presence of diabetes)
# Exploratory Data Analysis
     Display All Data: We loaded and displayed the dataset to get an initial understanding of the data.
     Data Shape: The dataset shape is (100000, 9).
     Data Visualization: We used various plots to understand the distribution and relationships between the features.
     Heatmap: A heatmap was used to visualize the correlation between the features.
     Preprocessing
     Label Encoding: We used label encoding to convert categorical features to numerical values.
     Data Splitting: The data was split into training and testing sets using an 80-20 split ratio.
# Modeling
   Logistic Regression
   
    Implemented Logistic Regression to predict diabetes. The model was trained and tested on the dataset.

K-Nearest Neighbors (KNN)

    Implemented K-Nearest Neighbors (KNN) algorithm. Various values of K were tested to find the optimal K value. 

Support Vector Machine (SVM)

    Implemented Support Vector Machine (SVM) to classify the data. Both linear and non-linear kernels were tested.

# Model Comparison
The accuracy of each model was compared to determine which model performs the best on the test dataset.

# Results
The following table summarizes the accuracy of each model:

# Model Accuracy
  # Logistic Regression  
       95%
  # K-Nearest Neighbors 
       95%
  # Support Vector Machine 
       96%
# Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

# License
This project is licensed under the MIT License. See the LICENSE file for details.


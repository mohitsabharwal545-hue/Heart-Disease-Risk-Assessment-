# Heart-Disease-Risk-Assessment

This project predicts the risk of heart disease using machine learning classification algorithms. It uses a Heart Disease dataset containing patient medical information to determine whether a patient is likely to have heart disease. The project compares the performance of Decision Tree and Random Forest classifiers and analyzes feature importance to identify the most influential risk factors.

## Objectives

* Predict the presence of heart disease.
* Train and evaluate Decision Tree and Random Forest models.
* Compare model accuracy.
* Identify the most and least important features using Random Forest.

## Dataset

The dataset contains patient health information, including:

* Age
* Sex
* Chest Pain Type (cp)
* Resting Blood Pressure (trestbps)
* Cholesterol (chol)
* Fasting Blood Sugar (fbs)
* Resting ECG (restecg)
* Maximum Heart Rate (thalach)
* Exercise-Induced Angina (exang)
* Oldpeak
* Slope
* Number of Major Vessels (ca)
* Thalassemia (thal)

**Target**

* 0 = No Heart Disease
* 1 = Heart Disease

## Technologies Used

* Python
* Pandas
* Scikit-learn

## Machine Learning Models

* Decision Tree Classifier
* Random Forest Classifier

## Workflow

1. Load the dataset.
2. Split the data into features (X) and target (y).
3. Divide the dataset into training and testing sets.
4. Train the Decision Tree model.
5. Train the Random Forest model.
6. Evaluate both models using accuracy.
7. Display feature importance from the Random Forest model.

## Results

* Decision Tree and Random Forest models are trained successfully.
* Model accuracy is calculated and compared.
* Feature importance is extracted to determine which medical attributes contribute most to heart disease prediction.

## Conclusion

Tree-based machine learning models provide an effective approach for predicting heart disease risk. Random Forest generally achieves better performance than a single Decision Tree because it combines multiple trees, improving accuracy and reducing overfitting. Feature importance also helps explain the model's predictions by highlighting the most significant health indicators.
  

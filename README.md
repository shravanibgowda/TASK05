Heart Disease Prediction using Decision Tree and Random Forest
This project applies machine learning techniques to predict the likelihood of heart disease based on health indicators from the BRFSS 2015 dataset.

Dataset
The dataset used is:

heart_disease_health_indicators_BRFSS2015.csv

It contains various health-related features such as BMI, smoking status, physical activity, and more, with the target variable:

HeartDiseaseorAttack (0 or 1)

Objective
To build and evaluate predictive models (Decision Tree and Random Forest) for classifying whether an individual has heart disease based on provided health indicators.

Tools and Libraries
Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

Methodology
Load and inspect the dataset.

Preprocess the data (drop target column, split into features and labels).

Train/Test split.

Train a Decision Tree and Random Forest Classifier.

Evaluate model performance using accuracy and classification report.

Visualize the decision tree.

Results
Models are evaluated using:

Accuracy Score

Classification Report

Tree Visualization

How to Run
Clone the repository.

Make sure the dataset path is correct.

Run the notebook: task5.ipynb

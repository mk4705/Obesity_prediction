Obesity Prediction

This notebook analyzes a dataset containing information related to obesity prediction. Using Python and ml model like random forest classifier it explores, preprocesses and models data to identify the key driving factors and predict obesity levels.

Main Steps in the Notebook

Data Loading & Overview:
The dataset contains 2,111 records with 17 columns, including demographic, lifestyle, and health-related variables (Gender, Age, Height, Weight, dietary habits, physical activities, Smoking, Alcohol Consumption, Family history, Mode of transportation and Obesity category).

Exploration & Inspection:The notebook displays information about data types and confirms there are no missing values.

Preprocessing:
One-hot encoding is performed to convert categorical features into a binary numerical format.
Target labels for obesity levels (Normal, Overweight, Obesity types I-III) are separated from features.

Splitting the Data:
A training/test split is applied (80% training, 20% test) for model evaluation.

Model Training:
A Random Forest Classifier is used with 150 trees and a maximum depth of 10.
The model is trained using the training set.

Prediction & Evaluation:
Predictions are made on the test set.
Accuracy, classification report (with precision, recall, f1-score), and confusion matrix are displayed.
Accuracy achieved: 86%
Detailed performance for each obesity category is included.

Feature Importance:
The most influential factors for obesity prediction are identified and visualized.
Top features include: Weight, Age, Height, Dietary habits (like Frequency of Vegetable Consumption), and Gender.

Visualization: Feature importances are shown via a bar plot for interpretability.

Key Findings:
The notebook demonstrates strong predictive performance for obesity classification using demographic and lifestyle data.
Weight is the most important predictor followed by Age, Height, and dietary habits.

Random Forests provide robust, interpretable feature importances and solid accuracy for this task.

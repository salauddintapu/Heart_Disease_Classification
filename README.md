# Heart_Disease_Classification
I have used several machine learning algorithms for classification of heart disease. I have performed hyperparameter tuning with the help of <b>Optuna</b>. No feature extraction was performed.

## Dataset
The original dataset is avaiable at: https://www.kaggle.com/sulianova/cardiovascular-disease-dataset    <br>
A cleaned version is avaiable at: https://www.kaggle.com/datasets/aiaiaidavid/cardio-data-dv13032020    <br>
Further cleaning was performed which is available in this repo, file named as <b>cleaned_data.csv</b>   <br>

Description of the features:    <br>
AGE:  integer (years of age)
HEIGHT: integer (cm) 
WEIGHT: integer (kg)
GENDER: categorical (1>Female, 2>Male)
AP_HIGH: systolic blood pressure, integer
AP_LOW: diastolic blood pressure, integer 
CHOLESTEROL: categorical (1>Normal, 2>Above normal, 3>Well above normal)
GLUCOSE: categorical (1>Normal, 2>Above normal, 3>Well above normal)
SMOKE: categorical (0>No, 1>Yes)
ALCOHOL: categorical (0>No, 1>Yes)
PHYSICAL_ACTIVITY: categorical (0>No, 1>Yes)
<br><br>

## Classifiers:
### Random Forest Classifier
<b>Accuracy:</b> 72.84%
<b>AUC:</b> 79.78%
<b>Precision:</b> 75.71%
<b>Recall:</b> 68.63%
<b>F1:</b> 72%
<b>CV:</b> 72.97%
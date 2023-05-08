# stroke-prediction
Python based ML project to develop a predictive model for stroke likelihood based on input parameters including gender, age, diseases, and smoking status.

KAGGLE DATASET LINK: https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

INTRODUCTION:
The Kaggle Stroke Prediction Dataset is a comprehensive collection of health-related data points that provide insights into the factors that may increase the risk of a stroke. The dataset contains demographic information, lifestyle choices, medical history, and various physical indicators of over 43,000 patients. This dataset is highly relevant to healthcare professionals, researchers, and data analysts who are interested in exploring the relationship between various factors and the likelihood of stroke. By analyzing this dataset, researchers can develop better prevention strategies, improve stroke diagnosis and treatment, and ultimately save lives.


ATTRIBUTE INFORMATION:
1) id: unique identifier
2) gender: "Male", "Female" or "Other"
3) age: age of the patient
4) hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
5) heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
6) ever_married: "No" or "Yes"
7) work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
8) Residence_type: "Rural" or "Urban"
9) avg_glucose_level: average glucose level in blood
10) bmi: body mass index
11) smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
12) stroke: 1 if the patient had a stroke or 0 if not
*Note: "Unknown" in smoking_status means that the information is unavailable for this patient

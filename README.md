# Heart-Attack-EDA-Prediction
Exploratory Data Analysis and Prediction of Heart Attack dataset


## Dataset:

https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset


## Task:
Data Analysis and Prediction of Heart Attack probability

## Description of Features:
age : age of the patient

sex: sex of patient (1 = female, 0 = male)

cp : type of chest pain (0: typical angina, 1: atypical angina, 2: non-anginal pain, 3: asymptomatic)

trtbps : resting blood pressure (in mm Hg)

fbs : fasting blood sugar > 120 mg/dl (1 = true, 0 = false)

chol : cholestoral in mg/dl fetched via BMI sensor

restecg : resting electrocardiographic results (0: normal, 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), 2: showing probable or definite left ventricular hypertrophy by Estes' criteria)

thalachh : maximum heart rate

exng : exercise induced angina (1 = yes, 0 = no)

oldpeak : previous peak

slp : slope

caa : number of major vessels (0-4)

thall : thalium stress test result(0-3)

output : target variable (0 = less chance of heart attack, 1= more chance of heart attack)

## Conlusion of EDA:
1. Total number of cases with typical angina chest pain approximately is equal to sum of the atypical angina, non-anginal pain and asymptomatic chest pain.

2. The dataset is more for age between 40-65.

3. The data consists of more than twice for females than males.

4. According to heatmap matrix, there might be correlation between output and cp, thalachh and slp.

5. The probability of heart attack between males is more than females.

6. People with typical angina chest pain has more chance of heart attack.

7. People who have Fasting blood sugar less than 120, have more chance of heart attack.

8. People with ST-T wave abnormality have more chance of heart attack.

9. People without exercise induced angina have more heart attack.

10. Cases with zero number of major vessels have more chance of heart attack.

11. People with thalium stress test result = 2 have higher risk of heart attack.

12. It seems that elder people might have higher chances of heart attack but it is evident that this isn't the true.

13. People with higher maximum heart rate have higher chances of heart attack.

14. People with lower pevious peak achieved have higher probability of heart attack.

## Conclusion of Prediction:

1. The best models are Logistic Regression and SVM (after hyperparameter tuning) with accuracy of 90%.

2. Accuracy of other models:

- Gradient Boosting 86%

- Random Forest: 83%

- Decision Tree / SVM without hyperparameter tuning 72%

# Final_codes_Gp10
<h2>BT4222 Machine Learning Project on Heart Disease Prediction</h2>

<h3> Contributors </h3> 
Mohammed Izhak @ Hein Htet <br/>
Lin Wen Jing  <br/>
Yap Hen Lit David <br/>
Chong Choon Han <br/>
Tan Wei Jie Ryan <br/>

<h3> Project Motivation </h3>
This project aims to predict the potential presence of heart related diseases in patients accurately based on other variables available such as the past medical histories, age, general physical and mental health, and more.
Key risk indicators of heart related diseases identified from the predictions can be used to raise awareness among the public such that they are able to practise their own form of preventive measures. 

<h3> Dataset Used </h3>
https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease <br/>
Cleaned data is in heart_2020_encoded.csv. We changed the multinomial classification data to binary classification for better handling by the models, and removed outliers for numerical data.

<h3> Models used </h3>
Using Logistic Regression, Linear SVC, XGB Classifier, 
Random Forest Classifier and Voting Class Ensemble on heart_2020_encoded.csv 
along with imbalanced data handling using SMOTE and SMOTEENN and Class Weighing. </br>
XGB Classifier is used as the final model for hyperparameter tuning.

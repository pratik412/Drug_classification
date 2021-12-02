# Drug-claification

This dataset contains information about drug classification based on patient general information and its diagnosis. Machine learning model is needed to predict the outcome of the drug-type that will be suitable for the patient. There are 6 variables in this data set 4 categorical variables, and 2 continuous variables and 200 records. The aim is to perform data exploration, visualization and build Machine Learning models that will help in predicting drug type. The data has variables like Age, Sex, Blood Pressure Level, Cholesterol Level, Sodium to potassium Ratio in Blood and Drug Type.

# Task Performed
1. Loaded and read the dataset and performed Exploratory data analysis to see the Trends.
2. Spitted the dataset into 70% training and 30% testing and performed Feature Engineering method that used is one hot encoding, which is transforming categorical variables into a form that could be provided to ML algorithms to do a better prediction.
3. Performed SMOTE Technique Since the number of 'DrugY' is more than other types of drugs, oversampling is carried out to avoid overfitting.
4. Developed the solution using a well-made machine learning model with high confidence in predicting. the drug type (A, B, C, X,Y) that should be given to a particular patient based on their characteristics and which drug type will suit them best and seen that performance of most of the ML models can reach up to 80% accuracy in predicting classification of drug type. Although Support Vector Machine (SVM) had the highest accuracy of 84.29%.
5. Transformed prediction in appropriate output format and generated output CSV file.

# Machine Learning models used:
1.Linear Regression
2.Logistic Regression
3. Naïve-Bayes: Gaussian NB, Categorical NB, 
4. Decision Tree
5. Random Forest
6. Random Forest Max 
7. K Neighbors Max.






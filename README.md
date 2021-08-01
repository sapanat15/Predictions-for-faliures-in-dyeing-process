# Predictions-for-faliures-in-dyeing-process
This notebook will help in evaluation of my coding skills.
This file contains all the codes and commands for Predictions for failures in dyeing process project. 
It will classify the data in passed and failed dyed batches. 
There is presentation also included as pdf which shows the outcome and findings of the project in brief.

# List of Libraries used in this project
Numpy
Pandas
Matplotlib
Seaborn
Missigno
IPython.display
Sklearn
sklearn.preprocessing : Standardscalar, LabelEncoder
sklearn.model_selection : train_test_split, StratifiedKFold, GridSearchCV
sklearn.linear_model : LogisticRegression
sklearn.metrics : r2_score, accuracy_score, roc_auc_score, f1_score, recall_score, precision_score, recall_score, confusion_matrix, roc_curve
sklearn.ensemble : RandomForestClassifier, AdaBoostClassifier
scipy.stats : kurtosis, skew, z-score
feature selection : model.feature_importances_

# Data Visualisation 
Countplot

Barplot

Distplot

Barh

Msno.bar

Msno.matrix

# Problem Statement

### Problem Statement:
In Apparel and Footwear Industry, colour matching is a critical factor. For example, when a Lead Designer of a major fashion brand has picked the colour for the season, he/she would want the exact colour on the produced garments. This means all hundreds of thousands of garments need to have the same colour. This is challenging because there are so many factors affecting colour: for example, different materials (e.g. cotton, polyester, leather) have different dye absorption rate; water properties (pH, purity, etc); ambient temperature; dyes concentration; chemical properties; etc.

I have been provided 1 year(2017) of dataset split in to training and test data. 

### About Data and Variables
It is all the data received during dyeing process at particular dyecenters with proper batch id and parent id numbers.Training data contains features has dye, fiber and substrate related information, test performed to check the colours and shade, weight and yarn related information, in total 67 features are present.


### Objective:
We want to build a model to predict probability of faliure (in dyeing exact colour) of the dyed batches and split them in to class "passed" and "failed". The probability score should be arrange in the descending order. 

The test data also contains the same features, which is what your model should predict.

### Evaluation Metric:
We will be using Area under the ROC curve to evaluate our model

                                         
                            
                             
                            

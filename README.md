# Pokemon-statistics

This repository contains the code that answers a number of statistical questions relating to Pokemon and their stats,
such as 'Which types appear the most when only looking at the strongest and weakest Pokemon (based on BST)?' and
'Does the average BST change with Generation?'.

Additionally, the directory 'poke_ML' contains notebooks that try to predict a single stat using the other stats as well as extra features.
This was initially done using the same data as for the statistical questions, for which the scripts are found in the 'first_data' directory.
There the 'data exploration' file looks for useful relations in the data, while the 'model XGBoost' file trains the actual model.
The 'model XGBoost fractions' file trains the model with extra features and methods to try and improve the model.

Later an extra dataset with an extra Generation of Pokemon was found, which was then also used to try and improve the model.
The data exploration and model training notebooks for this data are located in the 'expanded_data' directory.

Applied methods in this script are: manipulating data with numpy and pandas, visualizing data with matplotlib and seaborn, statistical tests with the Mann-Whitney U test, fitting with scipy (curve_fit), machine learning with XGBoost, feature engineering, and hyperparameter optimization (with GridSearchCV).

Data at: https://www.kaggle.com/datasets/abcsds/pokemon
Expanded data at: https://www.kaggle.com/datasets/rounakbanik/pokemon

machine learning model for stroke prediction

Here is a short FAQ about this repository

1) What is this repository about?

This repository contains a Machine Learning model for stroke prediction.

It includes the jupyter notebook (.ipynb), .csv file and a readme.

2) Which dataset has been used and where to find it?

The actual dataset used here is from kaggle 

3) What does the dataset contain?

This dataset contains 5110 entries and 12 attributes related to brain health.

4) Which type of ML model is it and what has been the approach to build it?

This is a classification type of ML model. Initially an EDA has been done to understand the features and later different ML algorithms have been applied to train the model. Top 2 algorithms with accuracy >75% were selected and the model has been cross-validated on these.

Next, as the dataset has some outliers for age attribute, these have been removed and the model has been trained & cross-validated with Random Forest Classifier to check if the model reliability can be improved.

5) Which tool and which libraries have been used in this project?

This project has been entirely completed in Jupyter IDE with Python 3.8.5 and the model has been trained using scikit-learn framework.

Libraries used: Pandas, NumPy, Matplotlib and Seaborn

# machine-learning-challenge

# Machine Learning Homework - Exoplanet Exploration

![exoplanets.jpg](Images/exoplanets.jpg)

### Before You Begin

1. Create a new repository for this project called `machine-learning-challenge`. **Do not add this homework to an existing repository**.

2. Clone the new repository to your computer.

3. Give each model you choose their own Jupyter notebook, **do not use more than one model per notebook.**

4. Save your best model to a file. This will be the model used to test your accuracy and used for grading.

5. Commit your Jupyter notebooks and model file and push them to GitHub.

## Note

Keep in mind that this homework is optional! However, you will gain a much greater understanding of testing and tuning different Classification models if you do complete it.

## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

To help process this data, you will create machine learning models capable of classifying candidate exoplanets from the raw dataset.

In this homework assignment, you will need to:

1. [Preprocess the raw data](#Preprocessing)
2. [Tune the models](#Tune-Model-Parameters)
3. [Compare two or more models](#Evaluate-Model-Performance)

- - -

## Instructions

### Preprocess the Data

* Preprocess the dataset prior to fitting the model.
* Perform feature selection and remove unnecessary features.
* Use `MinMaxScaler` to scale the numerical data.
* Separate the data into training and testing data.

### Tune Model Parameters

* Use `GridSearch` to tune model parameters.
* Tune and compare at least two different classifiers.


- - -

## Resources

* [Exoplanet Data Source](https://www.kaggle.com/nasa/kepler-exoplanet-search-results)

* [Scikit-Learn Tutorial Part 1](https://www.youtube.com/watch?v=4PXAztQtoTg)

* [Scikit-Learn Tutorial Part 2](https://www.youtube.com/watch?v=gK43gtGh49o&t=5858s)

* [Grid Search](https://scikit-learn.org/stable/modules/grid_search.html)

- - -

For this project I created Logistic Regeression, SVM, and Deep Learning models using the same feature inputs and output after cleaning through the data and finding the most important features. The Logistic Regression model is 87% accurate and the SVM model is similar at 86% with hypertuning to find the ideal paramaters using GridSearch. The Deep Learning model was the most accurate at about 90% largely due to to the extra hidden node layer that is not present with the other models. All of these models could be viable in making predictions in regard to possible exoplanets, however I would recommend always utilizing the Deep Learning model.

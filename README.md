# Machine Learning Assignment - Exoplanet Exploration

![exoplanets.jpg](Images/exoplanets.jpg)


## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

To help process this data,  machine learning models capable of classifying candidate exoplanets from the raw dataset were created.

## Requirements:

1. [Preprocess the raw data](#Preprocessing)
2. [Tune the models](#Tune-Model-Parameters)
3. [Compare two or more models](#Evaluate-Model-Performance)

- - -

### Preprocess the Data

* Preprocess the dataset prior to fitting the model.
* Perform feature selection and remove unnecessary features.
* Use `MinMaxScaler` to scale the numerical data.
* Separate the data into training and testing data.

### Tune Model Parameters

* Use `GridSearch` to tune model parameters.
* Tune and compare at least two different classifiers.

### Models used and results
SVC Model : 
Training Data Score: 0.8472248712569139
Testing Data Score: 0.852974828375286

Logistic Regression Model:  
Training Data Score: 0.8458897577722678
Testing Data Score: 0.8621281464530892

KNN (K Nearest Neighbors  K=9) Model: 
Training Data Score: 0.8739271409498379
Testing Data Score: 0.8295194508009154


### Reporting
Of the models created the scores looks good. As the Logistic regression and K nearest neighboursl have the highest accuracy these would be the best method to utilize for further research.



- - -

## Resources

* [Exoplanet Data Source](https://www.kaggle.com/nasa/kepler-exoplanet-search-results)

* [Scikit-Learn Tutorial Part 1](https://www.youtube.com/watch?v=4PXAztQtoTg)

* [Scikit-Learn Tutorial Part 2](https://www.youtube.com/watch?v=gK43gtGh49o&t=5858s)

* [Grid Search](https://scikit-learn.org/stable/modules/grid_search.html)

- - -


# Ad-Click-Classification Project
## Logistic-Regression-Practice-Project

## Project Overview
The aim of the project is to classify whether Internet user will click on the advertisement or not based on the Features in the data.

<img src="https://github.com/navi1910/Logistic-Regression-Practice-Project/blob/'master'/ad-img.png" height=50% width=50%>

Note: The data is fakely generated, just for Practice.

This data set contains the following features:

* 'Daily Time Spent on Site': consumer time on site in minutes
* 'Age': cutomer age in years
* 'Area Income': Avg. Income of geographical area of consumer
* 'Daily Internet Usage': Avg. minutes a day consumer is on the internet
* 'Ad Topic Line': Headline of the advertisement
* 'City': City of consumer
* 'Male': Whether or not consumer was male
* 'Country': Country of consumer
* 'Timestamp': Time at which consumer clicked on Ad or closed window
* 'Clicked on Ad': 0 or 1 indicated clicking on Ad

## Methods and Technologies used
* Python

    * Pandas
    * Numpy
    * Matplotlib
    * Seaborn
    * Scikit-learn

## Procedure
* Import the required python modules.
* Load the data.
* Check the basic information about the data such as obervstions' descriptive stats, null-values, etc.
* Check the Correlation between the numeric values in the fields.
* Exploratory Data Analysis is done using Visualizations of the data.

<img src="https://github.com/navi1910/Logistic-Regression-Practice-Project/blob/'master'/pairplot.png" height=50% width=50%>

## Model Building
* Separate the Features and Target variables.
* Split the data into Train set and Test set.
* Initialize the LogisticRegression model.
* Fit the model to the training data.
* Get predictions of the the test set from the model.

## Results
* Various metrics are used to evaluate the model performance.

<img src="https://github.com/navi1910/Logistic-Regression-Practice-Project/blob/'master'/results.png" height=50% width=50%>

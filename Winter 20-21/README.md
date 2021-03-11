# Crime-in-Philadelphia
## Capstone Project for DSCI 591, Winter 2020, Crime in Philadelphia
### Introduction

Our proposed solution is to create multiple models that can predict and classify the type of crime. This can also help provide community insights on how to make improvements to reduce the crime from occuring in the first place. Another solution we intend to work on is predicting which neighborhoods are likely to increase and decrease in crime rates. 

Philadelphia Crime/Weather Data and Philadelphia Parking Violation:
From last term, these Philadelphia Crime/Weather Data were cleansed and integrated. We will integrate Philadelphia Parking Violation based on location features such as lat and lon. From this we will be able to create zip codes for crime predictive analysis. 

The machine learning part of the project will be made up of three components: data transformation/normalization, data integration, and classification. For classification, we will do our best to implement all of the following model types: Logistic Regression, Decision Tree Classifier, Randomforest, Extra Trees, and KNN. In addition, for data transformation and normalization, we hope to perform at least one of the following: Dimensionality reduction (PCA as an example), Hyper-parameter tuning (for example gamma and C for SVM), and Feature Selection. 


# Table of Contents
1. [Team Members](#TEAM-MEMBERS)
1. [Datasets](#EXPLANATION-OF-DATASETS)
1. [Outline](#OUTLINE)
1. [Pitch Presentation](#PITCH-PRESENTATION)
1. [Pre-Processing](#DATA-PRE-PROCESSING)
1. [Analysis](#DATA-ANALYSIS)
1. [Exploratory Data Analytics Report](#EXPLORATORY-DATA-ANALYTICS)
1. [Predictive Modeling Report](#PREDICTIVE-MODELING)
1. [Final Presentation](#FINAL-PRESENTATION)


## TEAM MEMBERS

### Hong Son
- Education: BS/MS Data Science Drexel University (in-progress)
- Occupation: Student
- Skills: Data engineering, machine learning, and presenting. 

### Raj Patel
- Education: BS/MS Data Science Drexel University (in-progress)
- Occupation: Student
- Skills: Data cleansing, statistical analysis, and documentation. 

### Kunal Sharma
- Education: MS Data Science Drexel University (in-progress)
- Occupation: Student
- Skills: Data engineering, machine learning


## EXPLANATION OF DATASETS

## MAIN DATASETS
### Philadelphia Crime Data:
https://www.kaggle.com/mchirico/philadelphiacrimedata

For our project, we would like to conduct an analysis on a Philadelphia crime dataset published by OpenPhillyData. The dataset dates from 12-31-05 to 03-22-17 (majority of the dates are from 2006-2016). There are 14 total columns in this dataset. They include the district number, sector, dispatch date, dispatch time, location, general code, descriptions of the crime, and the district. This dataset was published to the public so people can assess the crimes happening in Philadelphia. For our exploratory data analysis, we will perform data cleansing, use data transformation to create new variables, and then create visualizations to answer the questions posed in this document


### SECONDARY DATASETS
#### Weather Data: 
http://www.climate.psu.edu/data/city_information/index.php?city=phl&page=dwa&type=big7

To assist in getting more out of our analysis, we will be scraping Philadelphia weather data for Philadelphia from 2007 to 2018. The dataset includes the temperatures in Fahrenheit, the max and min temperature, environment information, wind, and precipitation. The data was formatted into PDF files and a dataset was formed [~4,000 rows and 15 columns].


#### Parking Violations Data:
https://www.opendataphilly.org/dataset/parking-violations
	
We will be using the latitude and longitude points to map the zip codes in this dataset to the crime dataset. 



## OUTLINE

[Outline Report]
(https://github.com/hongson1218/Crime-in-Philadelphia/blob/master/Winter%2020-21/Report/Team%203%20-%20Project%20Outline_%20Crimes%20in%20Philadelphia.docx)


## PITCH PRESENTATION

[Pitch Presentation]
(https://github.com/hongson1218/Crime-in-Philadelphia/blob/master/Winter%2020-21/Presentation/DSCI%20592%20Pitch%20Presentation.pptx)


## DATA-PRE-PROCESSING

[Data Acquisition and Per-Processing Report]
(https://github.com/hongson1218/Crime-in-Philadelphia/blob/master/Reports/DSCI%20591%20Data%20Acquisition%20and%20Per-Processing%20Report.pdf)


## EXPLORATORY DATA ANALYTICS

[Exploratory Data Analytics Report]
(https://github.com/hongson1218/Crime-in-Philadelphia/blob/master/Winter%2020-21/Report/Team%203%20-DSCI%20591%20Exploratory%20Data%20Analytics%20Report.docx)


## PREDICTIVE MODELING
[Predictive Modeling Report]
(https://github.com/hongson1218/Crime-in-Philadelphia/blob/master/Winter%2020-21/Report/Team%203%20-%20DSCI%20592%20Predictive%20Modeling%20Report.docx)


## FINAL PRESENTATION
[Final Presentation]
(https://github.com/hongson1218/Crime-in-Philadelphia/blob/master/Winter%2020-21/Presentation/Final%20Presentation.pptx)

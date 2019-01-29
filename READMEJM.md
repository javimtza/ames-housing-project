# Project 2: Ames House Project
### Javier Martinez Abrego Cantu

---

## Executive Summary


### Contents:
- [Problem Statement](#Problem-Statement)
- [Data Dictionary](#2018-Data-Import-and-Cleaning)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)

---


## Problem Statement
Real estate is a business that changes year by year. Since there are uncountably many different variables that influence the price of a house, predicting the price of a house can be quite complicated. Using the Ames, Iowa housing dataset, can we create a model to predict house prices based on features that I believe highly influence the price of a house?


---

## Data Dictionary

Reference the [data description](http://jse.amstat.org/v19n3/decock/DataDocumentation.txt).

---

## Exploratory Data Analysis

In the Exploratory Data Analysis section I go through both the train dataset (which is the dataset I will use to train my regression model) and the test dataset (the dataset I want to map my predictions to). I identify outliers as well as getting a general idea of how my data looks and how I will engineer new data.

---

## Data Engineering

In this section I went thogutg the database filling in null values with appropriate values (when applicable) and either qantifying qualitative data or creating dummy variables for qualitative data.

---

## Data Modeling

Using Linear Regression, Ridge and Lasso models, I generate predictions for the test dataset. I apply the logarithmic function to scale the sale prices since it was rightskewed. Applying the logarithmic function to the sale prices makes residuals be more evenly distributed which is great in our case.

---

## Conclusions and Recomendations
In general, this was a fun project to complete. While at first, it was somewhat time consuming being able to get the regression models to work, it was fun to work through the data engineering and working with moving the dataset around. Even though this was my first actual data science problem, especially my first time working through a project involving regression, I am quite proud of the result of the project. I would have liked to have a bigger dataset so that I could engineer more columns that I thought were valuable, or make my columns more solid. For example in my train dataset, I created a column that categorized houses by average cost of houses in those neighborhoods. However there are certain neighborhoods that have less than 10 houses, so the average cost per house in those neighborhoods are not a great representation of the actual average, so more data in those neighborhoods would solidify the accuracy of my model to future data.
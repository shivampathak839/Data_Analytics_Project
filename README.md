# Data_Analytics_Project

Exploratory Data Analysis Of Flight data like price and other things
This project aims to predict flight ticket prices based on various features such as airline, flight, source and destination cities, travel duration, and time of departure and arrival. Using exploratory data analysis (EDA) and feature engineering techniques, the data was processed to uncover patterns and relationships for effective modeling and predictions.

Dataset
The dataset used for this project can be found on Kaggle. It contains cleaned flight data with features including the airline name, flight code, source and destination cities, travel duration, and ticket price.

Features
The dataset includes the following columns:

Airline: The airline company (categorical with 6 unique values).
Flight: Unique flight code (categorical).
Source City: The origin city of the flight (categorical with 6 unique values).
Departure Time: Categorical grouping of departure times.
Stops: The number of stops on the way to the destination (categorical with 3 unique values).
Arrival Time: Categorical grouping of arrival times.
Destination City: The destination city (categorical with 6 unique values).
Class: The seat class (either Business or Economy).
Duration: Travel time in hours (continuous).
Days Left: Days left between the booking date and the trip date.
Price: The target variable representing the ticket price.
Project Workflow
Exploratory Data Analysis (EDA):

Visualized various relationships in the data to gain insights.
Analyzed distribution and patterns of flight ticket prices across different airlines, routes, and travel classes.
Feature Engineering:

Extracted new features from existing columns, such as splitting the date into day, month, and year.
Created features for departure and arrival times in hours and minutes.
Mapped categorical features (such as stops) into numerical values.
Used one-hot encoding on categorical features (Airline, Source, Destination) for modeling purposes.
Data Preprocessing:

Handled missing values and transformed data types for efficient processing.
Standardized and cleaned features for model compatibility.
Encoding:

Applied one-hot encoding to categorical features to prepare data for machine learning models.
Code Structure
EDA and Feature Engineering: The primary analysis and transformation code is in the flight_price_prediction.ipynb or flight_price_prediction.py file.
Dataset: Import data directly from the Kaggle dataset or use the included dataset file (flight_price.xlsx).
Libraries Used: pandas, numpy, matplotlib, seaborn, sklearn.

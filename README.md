Uber Rides Data Analysis (Python Project)
📌 Project Overview

This project focuses on analyzing Uber ride data to uncover insights related to trip categories, purposes, booking times, popular routes, and ride distances.
The dataset used in this project was downloaded from Kaggle and cleaned, processed, and visualized using Python libraries such as NumPy, Pandas, Matplotlib, and Seaborn.

The goal of this project is to perform Exploratory Data Analysis (EDA) and answer key business questions for Uber.

📂 Dataset Information

The dataset contains 1156 rows and 7 columns:

START_DATE → Trip start date & time

END_DATE → Trip end date & time

CATEGORY → Category of trip (Business/Personal)

START → Starting location of the trip

STOP → Ending location of the trip

MILES → Distance traveled in miles

PURPOSE → Purpose of the trip (e.g., Meeting, Customer Visit, Meal/Entertainment, etc.)

🛠️ Project Workflow

Data Collection

Downloaded dataset from Kaggle.

Data Exploration

Explored dataset shape, column details, missing values, and statistics.

Data Cleaning

Removed duplicates and irrelevant rows.

Handled missing values (dropped unnecessary ones, filled where required).

Converted date columns into proper datetime formats.

Feature Engineering

Extracted hour, weekday, month from START_DATE.

Created new columns for better analysis.

Exploratory Data Analysis (EDA)

Answered business-related questions using SQL-like queries with Pandas.

Created data visualizations using Matplotlib & Seaborn.

❓ Key Business Questions Answered

In which category do people book the most Uber rides?

For which purpose do people book Uber rides the most?

At what time of the day do people book cabs the most?

In which months do people book Uber rides less frequently?

On which days of the week do people book Uber rides the most?

How many miles do people usually travel per ride?

📊 Tools & Technologies Used

Python → Data Cleaning, EDA, Analysis

Pandas → Data manipulation & transformation

NumPy → Numerical computations

Matplotlib & Seaborn → Data Visualization

Jupyter Notebook → Analysis & reporting

📈 Insights

🔹 Most rides were booked under the Business category.
🔹 The most common purpose for booking was Meetings and Customer Visits.
🔹 Rides are booked most frequently in the Evenings.
🔹 Ride demand is highest on weekdays, especially Thursday & Friday.

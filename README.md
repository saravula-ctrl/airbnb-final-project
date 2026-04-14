# Airbnb Listing Analysis & Prediction Project

## Overview
This project analyzes Airbnb listing data from Chicago, Boston, and Seattle to understand the factors that influence listing price and overall performance. The analysis combines exploratory data analysis (EDA) with machine learning models to identify key drivers of pricing across different markets.

The goal of this project is to:
- Identify key factors that influence Airbnb prices
- Compare pricing dynamics across cities
- Build models to predict listing price

---

## Dataset
The dataset includes Airbnb listings from:
- Chicago
- Boston
- Seattle

Key features include:
- Price
- Room type
- Property type
- Bedrooms, bathrooms, beds
- Review metrics
- Availability
- Host characteristics

---

## Project Structure

airbnb-final-project/
│
├── Project_Final_Code.ipynb
├── README.md
├── requirements.txt
├── .gitignore
│
├── data/
│   ├── listings_chicago.csv
│   ├── listings_boston.csv
│   └── listings_seattle.csv
│
└── final_project_outputs/

---

## Methodology

### Data Cleaning
- Handled missing values
- Converted price to numeric
- Standardized features across datasets

### Exploratory Data Analysis
- Price distributions
- Correlation analysis
- Feature comparisons across cities

### Modeling
- Linear Regression
- Random Forest Regressor
- Logistic Regression
- Random Forest Classifier

### Evaluation
- RMSE, MAE, R² (regression)
- Accuracy and confusion matrix (classification)

---

## How to Run

### 1. Clone the repository
git clone <your-repo-link>
cd airbnb-final-project

### 2. Install dependencies
pip install -r requirements.txt

### 3. Add data
Create a folder named `data` and place:
- listings_chicago.csv
- listings_boston.csv
- listings_seattle.csv

### 4. Run notebook
jupyter notebook

Open:
Project_Final_Code.ipynb

Run all cells.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Notes
- No absolute file paths required
- Notebook is fully runnable if data is placed correctly
- Designed for reproducibility

---

## Author
Sahil Ravula  
Indiana University

# House Prices Analysis Project

## Table of Contents
- [Overview](#overview)
- [Data](#data)
- [Analysis](#analysis)
  - [Data Exploration](#data-exploration)
  - [Pivot Tables](#pivot-tables)
  - [Correlation Analysis](#correlation-analysis)
  - [Regression Analysis](#regression-analysis)
  - [Extended Regression](#extended-regression)
  - [Sensitivity Analysis](#sensitivity-analysis)
- [Results](#results)
- [Conclusions](#conclusions)
- [How to Use](#how-to-use)
- [Contact](#contact)

## Overview

This project aims to analyze various factors that influence house prices. We leverage statistical and regression techniques to understand how different variables, such as building material, location, and home features, impact house prices and square footage. The analysis helps uncover patterns and relationships that are crucial for buyers, sellers, and real estate professionals.

## Data

The dataset used for this project includes information on house prices, square footage, number of bedrooms and bathrooms, and the number of offers received. Additional categorical variables include neighborhood and type of construction (brick or non-brick).

- **File:** `house-price-analysis.csv`
- **Variables:**
  - `Price` - Selling price of the house
  - `SqFt` - Square footage of the house
  - `Bedrooms` - Number of bedrooms
  - `Bathrooms` - Number of bathrooms
  - `Offers` - Number of offers received
  - `Neighborhood` - Geographic location (East, North, West)
  - `Brick` - Type of construction (Yes or No)

## Analysis

### Data Exploration

Initial exploration of the dataset includes summary statistics and visualizations to understand the distribution and variability of the data.

- **Descriptive Statistics:** Summary of key statistics for each variable.
- **Histograms and Box Plots:** Visualize the distribution of numeric variables.

### Pivot Tables

We created pivot tables to explore how average house prices and square footage vary by type of construction (brick vs. non-brick) and neighborhood.

- **Average Price by Construction and Neighborhood**
- **Average Square Footage by Construction and Neighborhood**

### Correlation Analysis

Correlation analysis was performed to determine the strength and direction of relationships between the quantitative variables.

- **Strongest Correlation:** Square footage and price (0.553)
- **Weakest Correlation:** Number of offers and number of bedrooms (0.114)
- **Negative Correlation:** Price and number of offers (-0.314)

### Regression Analysis

An initial regression analysis was conducted to understand the impact of different variables on house prices.

- **Significant Variables:** Square footage, number of bedrooms, number of bathrooms, number of offers
- **R-squared:** 70% of the variability in house prices is explained by the model

### Extended Regression

The regression model was extended to include dummy variables for the type of construction and neighborhood.

- **Significant Impact:** Homes in the East and North neighborhoods tend to decrease in value compared to the West.
- **R-squared:** 86% of the variability in house prices is explained by the model

### Sensitivity Analysis

A two-way sensitivity analysis was performed to predict the impact of changes in square footage and number of bedrooms on house prices. Conditional formatting highlights the results.

## Results

- **Brick homes** are generally more expensive than non-brick homes, regardless of the neighborhood.
- **Square footage** is a significant predictor of house prices.
- The number of **offers** received has a counterintuitive negative correlation with house prices, potentially due to the effect of time on the market.
- **Neighborhood** has a strong influence on house prices, with the West neighborhood generally commanding higher prices.

## Conclusions

- **Construction material** and **neighborhood** are crucial factors influencing house prices.
- **Square footage** consistently shows a strong positive relationship with price.
- Market dynamics, such as the timing and number of offers, can significantly impact pricing trends.

## How to Use

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/house-prices-analysis.git
   ```
2. **Run the Analysis:**
Open the house_prices_analysis.xlsx in Excel and run the cells to see the analysis step-by-step.

## Contact
For questions or feedback, please reach out to:
- Sean Deery
- Email: sdeery14@gmail.com
- LinkedIn: https://www.linkedin.com/in/sean-m-deery/
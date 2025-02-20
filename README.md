# Practical Application 3: Bank Marketing Campaign Analysis

## Overview
This repository contains a Jupyter Notebook for analyzing and modeling bank marketing campaign data. The objective of this project is to predict whether a customer will subscribe to a term deposit based on historical marketing data. The insights derived from this analysis help banks optimize future marketing campaigns and improve conversion rates.

## Objective
The goal of this project is to build a predictive model that determines whether a customer will subscribe to a term deposit. By understanding the key influencing factors, the bank can enhance its marketing strategy to target the right customers efficiently.

## Dataset
The dataset consists of historical marketing campaign data, including:
- **Numerical Features:** Economic indicators and customer-related attributes such as employment variation rate, consumer price index, duration of call, and Euribor 3-month rate.
- **Categorical Features:** Customer demographics and campaign-related attributes such as job type, marital status, education level, previous campaign outcome, and month of contact.

## Data Analysis
1. **Data Loading & Cleaning:**
   - Loaded the dataset into a Pandas DataFrame.
   - Removed duplicates and handled missing values.
   - Processed categorical variables for model training.

2. **Data Visualization:**
   - Used boxplots and countplots to explore numerical and categorical distributions.
   - Visualized the impact of features on the target variable.

3. **Feature Engineering & Selection:**
   - Identified numerical and categorical features.
   - Standardized numerical variables and encoded categorical variables.

## Model Development
- **Model Used:** Logistic Regression, Decision Tree, KNN, SVC

## **Key Findings:**
- **Top Positive Features from LR Model (Increase Subscription Probability):**
  - Duration of call
  - Contact month (March)
  - Success in previous campaigns
  - Higher consumer price index
  - Higher interest rates 

- **Top Negative Features from LR Model (Decrease Subscription Probability):**
  - High employment variation rate
  - Failure in previous campaigns
  - Contact months (May, June, November)

## Business Insights & Recommendations
- **Optimize Call Timings:** Prioritize outreach in March and reduce efforts in May, June, and November.
- **Focus on Engaged Customers:** Customers who previously subscribed are more likely to do so again.
- **Improve Call Strategy:** Longer call durations increase the likelihood of a positive outcome.
- **Consider Economic Indicators:** Employment variation and consumer price index trends impact customer decisions.

## Technologies Used
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn)
- Jupyter Notebook

## How to Run the Notebook
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-repo-url.git
   ```
2. Navigate to the project folder and launch Jupyter Notebook:  
   ```bash
   jupyter notebook
   ```
3. Open and run the notebook step by step.

## Future Improvements
- Implement additional models (Random Forest) for better accuracy.
- Deploy the model as a web application for real-time predictions.

## Author
Preeti Dubey

## License
This project is open-source and available under the MIT License.






# Open-Access Data Science & Advanced Analytics - energy company

A major gas and electricity utility that corporate, SME and residential customers. Tasked with diagnosing the source of churning SME customers. 

The hypotheses considered is that churn is driven by the customers’ price sensitivities and that it is possible to predict customers likely to churn using a predictive model.


Files attached include:
- Exploratory Data Analysis and Data Cleaning
- Feature Engineering
- Modelling and Evaluation

# Summary Model Solution
Data Science Problem – Hypothesis that customers are likely churn when there is a change in price.

The hypothesis under consideration is that churn is driven by the customers' price sensitivities and that it would be possible to predict customers likely to churn using a binary classification model as a predictive model.

From the data collected, Exploratory Data Analysis was conducted where the data was cleaned, visualised and transformed to prepare the data for modelling. Visualisations showed that:

* Within the SME division, customer churn was high as initally highlighted in business problem from client
* 9.9% of total customer base in the SME division had churned between January 2016 and March 2016
* For predictions, binary classification model was created using the XGBoost Model (XGBClassifier).

The model created was able to predict customer churn
The hypothesis was rejected as the model showed that customer price sensitivity is not the main driver of churn
Feature importance graph showed that yearly consumption, forecasted bill of meter over next 12 months, net margin and dates of last modification to products are the 4 largest drivers of customer churn

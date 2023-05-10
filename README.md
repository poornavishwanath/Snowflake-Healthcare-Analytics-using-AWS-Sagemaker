# Snowflake-Healthcare-Analytics-using-AWS-Sagemaker
In Healthcare analytics the process of using data and analytical methods to improve the delivery of
healthcare services and patient outcomes, one important area is the analysis of patient length of stay
(LOS), which refers to the amount of time a patient spends in a healthcare facility.
Length of stay is a critical metric in healthcare, as it can impact patient outcomes, healthcare costs, and
hospital capacity. By analyzing patient LOS data, healthcare providers can identify opportunities to
improve the delivery of care and reduce costs.
In addition to improving patient outcomes, the analysis of patient LOS can also help healthcare providers
to reduce costs. For example, by identifying patients who are at risk of extended LOS, providers can take
proactive steps to ensure they receive the care they need in a timely manner. Overall, the analysis of
patient length of stay helped the providers to improve patient outcomes and reduce costs. By leveraging
data and advanced analytical techniques, healthcare providers can gain a deeper understanding of
patient needs and identify opportunities to improve the delivery of care.

###Tools and technologies: 
Snowflake, Data preprocessing & Management, AWS Sagemaker and ML model
1. Snowflake Worksheet
2. EDA, Feature Engineering in Snowflake
3. AWS Sagemaker Setup and fetching the data from Snowflake using snowflake-connector-python, and
snowflake-sqlalchemy.
4. Data Preprocessing, Feature Selection, Model Building using AWS Sagemaker where we used models
such as - Linear Regression, Random Forest Regression, XGBoost Regression
5. Using predictive modelling inserted model predictions in Snowflake. Scored function deployment and
scheduling to send Status mail.

###Main Steps
1. Data Analysis in Snowflake
2. Build a Machine Learning model to predict the length of stay for
patients 
3. To schedule the AWS Sagemaker Notebook 
4. To perform live data scoring and inserting
predictions to Snowflake 
5. Send status mail

###Tech Stack 
AWS Sagemaker, Snowflake , Python Libraries: snowflake-connector-python, snowflakesqlalchemy, xgboost, pandas, numpy, scikit-learn

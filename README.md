# Churn-Classification-Project

I will work with a [dataset](https://github.com/serapumut/Churn_Classification_Project/blob/main/churn.xlsx) containing information from a fictional telco company that provided home phone and internet services to 7043 customers in California in Q3.

It indicates which customers have left, stayed, or signed up for their service. Multiple important demographics are included for each customer, as well as a Satisfaction Score, Churn Score, and Customer Lifetime Value (CLTV) index.

More information can be found [here](https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2019/07/11/telco-customer-churn-1113).

My goal is to create a model to predict whether or not a customer will churn.

I’m starting to project by loading packages and dataset.

After finding and cleaning missing values, I used visualization to identify the some patterns.

Since it a classification project, I selected three classification models respectively, Logistic Regression, Decision Tree Classifier and Random Forest.

After Hyperparameter Tuning, I did Cross Validation.

According to results with and without Cross Validation, Logistic Regression has highest AUC score.

As a conclusion, Logistic Regression performs reasonably well with the current parameters. The results are consistent, by using the model to make new predictions showing that The model is confident that this customer is likely to churn, with a high probability (79%).

#Task 1
**Label**
repeat_purchase_flag — This is the target variable because it directly indicates whether the customer made a repeat purchase within 30 days, which is exactly what the model is meant to predict.

**Data leakage feature**

discount_used_on_repeat_order — This would introduce leakage because it contains information about the repeat purchase event itself (which happens after the prediction point), making it unavailable at prediction time and artificially boosting model performance.

#Task 2

**Exploratory Data Analysis (EDA)**
This helps you understand the data distribution, detect missing values, outliers, and relationships between features and the target. Without EDA, you risk feeding poor-quality or misunderstood data into the model.

**Data preprocessing & baseline modeling**
Cleaning the data (handling missing values, encoding variables, scaling if needed) and building a simple baseline model (e.g., logistic regression) provides a reference point. This ensures your pipeline is correct and helps you judge whether a complex model is actually adding value.

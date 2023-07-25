# Lead Scoring Case Study

Tackle the problem of improving the lead conversion rate for education company named X Education sells online courses to industry professionals.

In order to address the problem of low lead conversion rate for X Education, we proposed building a logistic regression model to assign lead scores to each lead. The lead score ranges from 0 to 100, with higher scores representing a higher likelihood of conversion (hot data) and lower scores representing a lower likelihood of conversion (cold leads). This approach helps the sales team prioritize data with a higher probability of conversion, ultimately increasing the overall conversion rate.

To achieve this goal, we followed these steps:
1.	**Data Inspection**: We inspected the dataset to understand its structure, columns, and data types. We identified categorical variables with a level called 'Select', which is equivalent to a null value and needs to be handled.

2.	**Data Cleaning**: We filled missing values or dropped rows with missing values as needed. We converted categorical variables to dummy variables and removed unnecessary columns.

3.	**Exploratory Data Analysis (EDA)**: We performed a detailed EDA, including univariate and bivariate analysis for both categorical and continuous variables. We also created a correlation heatmap and pair plot for continuous variables.

4.	**Data Preparation**: We split the data into features (X) and target (y) variables and further divided it into training and testing sets. We also standardized the data using a StandardScaler.

5.	**Model Building**: We built a logistic regression model, fitted it to the training data, and made predictions on the test data.

6.	**Model Evaluation**: We evaluated the model using a confusion matrix, classification report, and accuracy score. We ensured that the model's performance met the company's target lead conversion rate of around 80%.

* **By following this approach, we successfully created a logistic regression model that assigns lead scores to each lead, helping the company target potential leads more efficiently. This model can be further fine-tuned and adapted to other algorithms if needed to improve its performance. Overall, this solution enables X Education to streamline their sales process and increase their lead conversion rate.**



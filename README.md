# telecom-churn
telecom_churn_data.zip: The dataset contains customer-level information for a span of four consecutive months - June, July, August and September which is encoded as 6,7,8 and 9 respectively.
Data Dictionary: The Data Dictionary contains meanings of the abbreviations used.

The objective is to predict the churn rate in the last (i.e. the ninth) month using the data (features) from the first three months and identify the important predictors of customer churn.

Some important considerations:

1.Churn prediction is usually more critical for prepaid customers as opposed to postpaid customers, as in case of the former model  customers who want to switch to another network can simply stop using the services without any notice, and it is hard to know whether someone has actually churned or is simply not using the services temporarily.

2.There are various ways to define churn like:
  a. Revenue based churn:Customers who have not utilised any revenue-generating facilities such as mobile internet, outgoing calls, SMS etc. over a given period of time.
  b. Usage based churn:Those customers with no usage i.e. no incoming or outgoing in terms of calls,internet etc. for a certain amount of time.
Here, we are using the usage based churn definition to predict churn.

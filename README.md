# Amazon_Vine_Analysis
## Overview of the analysis: 
Explain the purpose of this analysis.

The purpose of this project is to analyze Amazon written reviews by its members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. 

This project have  approximately 50 datasets and each one contains reviews of a specific product, from clothing apparel to wireless products. I had picked one of the datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, I use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. A summary of analysis is below for stakeholders to review.


## Resources & Tools: 

> * AWS RDS
> * pgAdmin
> * Visual Studio Code
> * Google Colab
> * Dataset link: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz

## Results: 

Customer Table
![](Resources/customer_table.png)

Products Table
![](Resources/products_table.png)

Review ID Table
![](Resources/review_id_table.png)

Vine Table
![](Resources/vine_table.png)


### How many Vine reviews and non-Vine reviews were there?


### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?


### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?


## Summary: 
In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
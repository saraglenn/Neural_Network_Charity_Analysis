# Neural_Network_Charity_Analysis

## Overview 

Alphabet Soup, an imaginary non-profit fundraising organization, is seeking to identify the potential success of candidates through funding. Utilizing neural networks and a range of methodologies, I endeavor to develop a Machine Learning module aimed at identifying the most suitable candidates. The dataset comprises 34,000 organizations that have been recipients of funding from Alphabet Soup throughout the years.

## Troubleshooting 



## Analysis 

The objective is to extract the data from the charity CSV file and load it into a Pandas dataframe. To enhance the overall feature data, two columns, namely 'EIN' and 'NAME', are excluded. The targeted columns for the machine learning module are 'IS_SUCCESSFUL'. Furthermore, some data cleansing is performed on the following two columns: 'CLASSIFICATION' and 'APPLICATION_TYPE'. The rationale behind these changes is the presence of numerous distinct values in each column. 'APPLICATION_TYPE' has 17 unique values, while 'CLASSIFICATION' has 71 categories. To utilize the OneHotEncoder effectively, it is necessary to reduce these lists to approximately 9 distinct values.


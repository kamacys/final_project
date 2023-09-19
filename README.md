# final_project
Title: Access to Computer Science in U.S. Public Schools: Methods in data collection and predicting future outcomes

Data used: Code.org national access data from 2018-2023, New Hampshire high schools access data from 2019-2022
Objectives: Use supervised machine learning to predict Computer Science access over time,
Use supervised machine learning to predict if a high school will teach Computer Science,
Automate the manual data retrieval process with web scraping

Methods: Linear regression model, K-nearest neighbors, static model, webscraping using Selenium 

Conclusion: I was successfull at accurately forcasting national cs access for the following year using linear regression,
The KNN model accuracy will allow me to accurately perdict if a hs will continue to teach computer science,
The automated data retrieval program has also been a success, and I will be using it next year when doing manual look-up. 

Repository contents:
Resource folder contains .csv files used in programming,
Retrieved Data folder contains the excel spreadsheet of the collected course catalogs retrieved through web-scraping,
automated_catalog_pull file contains the web-scraping program and pulls data from school_url.csv,
NAT_LR file contains the linear regression model and prediciton for 2023 and pulls from nat_yr.csv,
NAT_LR_PREDICT file contains the linear regression model and prediciton for 2024 and pulls from nat.csv,
NH_KNN file contains the KNN algorithym for predicting cs access in NH high schools and pulls from NH.csv

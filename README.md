# Movies-ETL

## Overview
In this Project we have  gathered data from both Wikipedia and Kaggle, combined them, and save them into a SQL database so that we have a nice, clean dataset to use. To do this, we followed the ETL process: extract the Wikipedia and Kaggle data from their respective files, transform the datasets by cleaning them up and joining them together, and load the cleaned dataset into a SQL database.
Here we have extracted scraped Wikipedia data stored as a JSON, and Kaggle data stored in CSVs.
We have used Python and Pandas to explore, document, and perform our data transformation and have loaded the data into relational database PostgreSQL.
As part of the challenge we are required to keep the data  updated on a daily basis. Hence we have created an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables.



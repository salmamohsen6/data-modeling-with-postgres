# data modeling 

## describion of prject 

A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analytics team is particularly interested in understanding what songs users are listening to. Currently, they don't have an easy way to query their data, which resides in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app.

They'd like a data engineer to create a Postgres database with tables designed to optimize queries on song play analysis, and bring you on the project. Your role is to create a database schema and ETL pipeline for this analysis. You'll be able to test your database and ETL pipeline by running queries given to you by the analytics team from Sparkify and compare your results with their expected results.


we are going to use PostgresSQL to create database with tables designed to optimize queries on song play analysis. creating a database schema and ETL pipeline.

## how to run scripts
in the terminal write the following codes 
```bash
python create_tables.py
```
```bash
python etl.py
```
```bash
python sql_quaries.py
```
## explanation of the files in the repository
the repository has five files:

1 sql_queries : contains all your sql queries, and they are used in the etl file and create tables file

2 create_tables :creates your postgres tables. 

3 etl :processes files from datasets (song_data and log_data) and insert them into your tables using the above quaries. 

4 etl notebook: do the same thing as the etl.py but for a single file int the dataset. this have clear instruction for the project

5 test notebook: tests if everything is done right


## Data Modeling
 
we used the star schema as shown in the pic
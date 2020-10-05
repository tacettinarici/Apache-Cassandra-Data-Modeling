# Apache-Cassandra-Data-Modeling


# Datasets
For this project, we'll be working with one dataset: event_data. The directory of CSV files partitioned by date. Here are examples of filepaths to two files in the dataset:

event_data/2018-11-08-events.csv
event_data/2018-11-09-events.csv

# Project Template
To get started with the project, go to the project template (a Jupyter notebook file).

### The project template includes one Jupyter Notebook file, in which:
we will process the event_datafile_new.csv dataset to create a denormalized dataset
we will model the data tables keeping in mind the queries we need to run
we have been provided queries that we will need to model our data tables for
we will load the data into tables we create in Apache Cassandra and run our queries

# Project Steps
Below are steps we can follow to complete each component of this project.

### Modeling your NoSQL database or Apache Cassandra database
Design tables to answer the queries outlined in the project template
Write Apache Cassandra CREATE KEYSPACE and SET KEYSPACE statements
Develop our CREATE statement for each of the tables to address each question
Load the data with INSERT statement for each of the tables
Include IF NOT EXISTS clauses in our CREATE statements to create tables only if the tables do not already exist. It is recommended also include DROP TABLE statement for each table, this way we can run drop and create tables whenever we want to reset our database and test our ETL pipeline
Test by running the proper select statements with the correct WHERE clause
### Build ETL Pipeline
Implement the logic in section Part I of the notebook template to iterate through each event file in event_data to process and create a new CSV file in Python
Make necessary edits to Part II of the notebook template to include Apache Cassandra CREATE and INSERT statements to load processed records into relevant tables in our data model
Test by running SELECT statements after running the queries on your database

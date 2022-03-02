# Data Modelling in NoSQL with _Cassandra_



### Project Structure

```
Data-Modelling-with-Cassandra
|
|__ event_data
|       |___ 2018-11-01-events.csv
|       |___  ...
|
|__ images
|       |___ image_event_datafile_new.jpg
|
|__ event_datafile_new.csv
|
|__ Project_template.ipynb
|
|__ README.md
```

### Objective

This project basically focuses on the Data Modelling in a NoSQL database. The data modelling in a NoSQL database must be
according to the query. Here we have 3 queries about the customer's listening data for our imaginary music app company 
called '**Sparkify**'.

The Jupyter Notebook has two parts. 
1. In the first part, we take all the event data present in the directory and create a new file called '**_event_datafile_new.csv_**'.
The Pandas library is used here to concat the CSV files and the resultant file is written to disk.
2. In the second part, we create a seperate table as per the query, insert the data present in the file, and 
run the query to check the result.

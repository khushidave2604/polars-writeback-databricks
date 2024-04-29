# polars-writeback-databricks
Using Polars library to manipulate data and write back to Azure databricks, by-passing the use of Spark server.

Here, in the git repository, we have the python code, which can be directly run after changing the name and path of the external_csv.csv. This file is just the local csv file that we will be using to merge with our original dataframe that we take from our storage account. 

The SQL code that needs to be added and run on the SQL Editor on our workspace on Azure databricks is also added here. The table name can be changed and manipulated as per requirements.

# CSV to SQL Server Importer

This project contains a Python script that automates the process of importing data from a CSV file into a SQL Server database. The script dynamically creates a table based on the columns in the CSV file and inserts the data into this table. Additionally, it includes functionality to change the primary key of the table if needed.

## Features

- **Dynamic Table Creation**: The script checks if the table exists in the database and creates it dynamically based on the CSV file's columns if it does not.
- **Data Insertion**: Inserts all rows from the CSV file into the created SQL Server table.
- **Primary Key Modification**: Allows the user to change the primary key of the table after insertion.

## Requirements

- Python 3.x
- Pandas
- pyodbc

You can install the necessary packages using pip:

```bash
pip install pandas pyodbc

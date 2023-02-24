# sql-challenge

All 6 of the following CSV files were reviewed to determine the best method for constructing the tables to house the data.

department.csv
dep_managers.csv
titles.csv
employees.csv
salaries.csv
dept_empy.csv

The review of how to connect the tables was performed using the QuickDB to create tables and an ERD. A junction table was used used to help with the Many-to-Many relationships of tables dept_emp and employees and tables dept_emp and departments. A Composite Key was used as a the primary key for the dept_emp. The composite key combines columns to create a primary key that is unique for each row. Also created foreign keys to the employees and departments tables. 

Once the ERD was created, the Postgres format of the QuickDBD-Data-Modeling-Employees.sql was exported. This file was then opened and pasted into the pgAdmin to create the database tables.

Each of the tables listed above were imported into the created tables using pgAdmin import.

Then each query was able to be perform successfully using select queries.
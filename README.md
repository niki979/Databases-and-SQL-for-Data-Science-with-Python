# Databases-and-SQL-for-Data-Science-with-Python
Course offered by IBM

Week 1:
Demonstrate how to write basic SQL statements
Describe SQL and Databases
Create and execute CREATE TABLE, SELECT, INSERT, and DELETE SQL statements with a live database

Week 2:
Compose and execute CREATE TABLE, ALTER, DROP, and TRUNCATE statements hands-on on a live database.
Create a database instance on the Cloud.
Describe basic relational database concepts including tables, primary keys and foreign keys.
Compare and contrast Data Definition Language and Data Manipulation Language.
Develop ALTER, DROP and TRUNCATE statements.
Explain the syntax of the CREATE TABLE statement.

Week 3:
Group data into result sets.
Use string patterns and ranges in SQL queries.
Demonstrate how to use string patterns and ranges in SQL queries
Sort and order result sets.
Compose sub-queries and nested select statements.

Week 4:
Access databases from Python using SQL magic.
Describe concepts related to accessing Databases using Python.
Create tables and insert data using Python.
Connect to a database using ibm_db Python library.
Analyze a data set using SQL and Python.

Week 5:
Invoke SQL queries using Python.
Retrieve SQL query results and analyze data.
Interpret and translate data analysis questions into SQL queries.

These are the assignment queries that I have solved successfully
Problem 1: Find the total number of crimes recorded in the CRIME table.
Problem 2: List community areas with per capita income less than 11000.
Problem 3: List all case numbers for crimes  involving minors?(children are not considered minors for the purposes of crime analysis)
Problem 4: List all kidnapping crimes involving a child?
Problem 5: What kind of crimes were recorded at schools?
Problem 6: List the average safety score for all types of schools.
Problem 7: List 5 community areas with highest % of households below poverty line.
Problem 8: Which community area(number) is most crime prone?
Problem 9: Use a sub-query to find the name of the community area with highest hardship index.
Problem 10: Use a sub-query to determine the Community Area Name with most number of crimes?


Week 6:
Generate joins to query data from multiple tables.
Create stored procedures and invoke them from other code.
Describe the significance of ACID transactions.
Implement transactions in SQL statements.
Compare and contrast the benefits and disadvantages of using stored procedures.
Define views and describe the benefits they provide.
Compare and contrast the different JOIN operators.
Create and query a view.

These are the assignment queries that I have solved successfully:
Exercise 1, Question 1:Write and execute a SQL query to list the school names, community names and average attendance for communities with a hardship index of 98. 
Exercise 1, Question 2: 
Write and execute a SQL query to list all crimes that took place at a school. Include case number, crime type and community name.
Exercise 2, Question 1: 
Write and execute a SQL statement that returns just the school name and leaders’ icon from the view. 
Exercise 3, Question 1: 
Write the structure of a query to create or replace a stored procedure called UPDATE_LEADERS_SCORE that takes a in_School_ID parameter as an integer and a in_Leader_Score parameter as an integer. Don't forget to use the #SET TERMINATOR statement to use the @ for the CREATE statement terminator. 
Exercise 3, Question 2: 
Inside your stored procedure, write a SQL statement to update the Leaders_Score field in the CHICAGO_PUBLIC_SCHOOLS table for the school identified by in_School_ID to the value in the in_Leader_Score parameter. 
Exercise 3, Question 3: 
Inside your stored procedure, write a SQL IF statement to update the Leaders_Icon field in the CHICAGO_PUBLIC_SCHOOLS table for the school identified by in_School_ID using the following information. 
Exercise 3, Question 4: 
Run your code to create the stored procedure.
Exercise 4, Question 1: 
Update your stored procedure definition. Add a generic ELSE clause to the IF statement that rolls back the current work if the score did not fit any of the preceding categories. 
Exercise 4, Question 2: 
Update your stored procedure definition again. Add a statement to commit the current unit of work at the end of the procedure. 



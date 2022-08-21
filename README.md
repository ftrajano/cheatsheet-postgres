# cheatsheet-postgres
A cheatsheet to register useful postgres commands and tips


**Command to initiate the postgress in terminal (if your postgres is on /Library)**
>> /Library/PostgreSQL/14/scripts/runpsql.sh

**Useful postgres commands**

\l - list your databases
\dt - list tables in your database
\d+ table_name - list details of columns of the table_name 


## Basic SQL commands
SELECT COUNT(DISTINCT table_column) FROM table_name; - Select the distinct values of the table column

## Inner Joins
Keep in the "right" table the rows that match with the "left" the items used to compare them.
SELECT *

FROM left_table

INNER JOIN right_table

ON left_table.left_column_name = right_table.right_column_name 

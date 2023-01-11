## About SQL

###### SQL Statement
> SELECT * FROM Countries WHERE Countinet = 'Europe';
clause & logical expression

###### Fundamental Functions CRUD
- Create (INSERT)
- Read (SELECT)
- Update (UPDATE)
- Delete (DELETE)



## The SELECT statement

> SELECT Name, LifeExpentancy AS "Life Expectancy" FROM Country ORDERBY Name;

AS keyword can be emitted

single quotes are used for a literal string, 
double quotes are used for most other things.




## --- Selecting rows ---

> e.g. SELECT Name, Continent. Region FROM Country WHERE Continent = 'Europe' ORDER BY Name LIMIT 5;
LIMIT is used to select the first x rows in the table.
In this case, only show the first 5 rows.

e.g. SELECT Name, Continent. Region FROM Country WHERE Continent = 'Europe' ORDER BY Name LIMIT 5 OFFSET 5;
OFFSET is used to ignore the the first x rows in the table, and do the other.
In this case, show the 6 row to the 10 row.

ORDER BY clause has to be after the WHERE clause, 
LIMIT and OFFSET clauses has be to the last.

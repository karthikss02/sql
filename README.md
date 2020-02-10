# Learn SQL

## Table of Contents

- [What is SQL?](#what-is-sql)
- [What is Schema?](#what-is-schema)
- [What is a Table?](#what-is-a-table)
- [What is a Column?](#what-is-a-column)
- [What is a Row?](#what-is-a-row)
- [What is a Primary Key?](#what-is-a-primary-key)
  - [Why do we need a Primary Key?](#why-do-we-need-a-primary-key)
- [What is a Clause?](#what-is-a-clause)
- [What is the SELECT keyword?](#what-is-the-select-keyword)
- [What is the DISTINCT keyword?](#what-is-the-distinct-keyword)
- [What is the LIMIT keyword?](#what-is-the-limit-keyword)
- [What is the OFFSET keyword?](#what-is-the-offset-keyword)
- [What is the ORDER BY clause?](#what-is-the-order-by-clause)
- [What is the WHERE clause?](#what-is-the-where-clause)
- [What is the WHERE LIKE Statement?](#what-is-the-where-like-statement)
- [What is the AS keyword?](#what-is-the-as-keyword)
- [What are Aggregate Functions?](#what-are-aggregate-functions)
- [What is the GROUP BY Clause?](#what-is-the-group-by-clause)
- [What is the HAVING Clause?](#what-is-the-having-clause)
- [What is INNER JOIN?](#what-is-inner-join)
- [What is LEFT JOIN?](#what-is-left-join)
- [What is RIGHT JOIN?](#what-is-right-join)
- [What is FULL JOIN:](#what-is-full-join)
- [What is UNION Clause:](#what-is-union-clause)

## What is SQL?

SQL is an abbreviation for Structured Query Language. SQL is a language designed specifically for communicating with databases.

**[⬆ Back to Top](#sql)**

## What is Schema?

Information about database and table layout and properties.

**[⬆ Back to Top](#sql)**

## What is a Table?

A structured list of data of a specific type.

**[⬆ Back to Top](#sql)**

## What is a Column?

A single field in a table.

**[⬆ Back to Top](#sql)**

## What is a Row?

A record in a table.

**[⬆ Back to Top](#sql)**

## What is a Primary Key?

A column (or set of columns) whose values uniquely identify every row in a table.

### Why do we need a Primary Key?

Without a primary key, updating or deleting specific rows in a table becomes extremely difficult as there is no guaranteed safe way to refer to just the rows to be affected.

**[⬆ Back to Top](#sql)**

## What is a Clause?

SQL statements are made up of clauses, some required and some optional. A clause usually consists of a keyword and supplied data. An example of this is the `SELECT` statement’s `FROM` clause.

**[⬆ Back to Top](#sql)**

## What is the SELECT keyword?

`SELECT` statement is used to retrieve one or more columns of data from a table.

**[⬆ Back to Top](#sql)**

## What is the DISTINCT keyword?

- `SELECT DISTINCT` returns only distinct (different) values.

**[⬆ Back to Top](#sql)**

## What is the LIMIT keyword?

`LIMIT` keyword specifies the number of rows to return.

**[⬆ Back to Top](#sql)**

## What is the OFFSET keyword?

`OFFSET` keyword specifies where to start from.

**[⬆ Back to Top](#sql)**

## What is the ORDER BY clause?

- `SELECT` returns records in no particular order.
- To ensure a specific order use the `ORDER` BY clause.
- `ORDER` BY allows sorting by one or more columns.
- Records can be returned in ascending or descending order.

**[⬆ Back to Top](#sql)**

## What is the WHERE clause?

The `WHERE` clause is used to specify a condition while fetching the data from a single table or by joining with multiple tables.

**[⬆ Back to Top](#sql)**

## What is the WHERE LIKE Statement?

- `WHERE LIKE` determines if a character string matches a pattern.
- `WHERE LIKE` supports two wildcard match options: % and _.

**[⬆ Back to Top](#sql)**

## What is the AS keyword?

The `AS` keyword is used to rename a column or table with an alias.

**[⬆ Back to Top](#sql)**

## What are Aggregate Functions?

Functions that operate on a set of rows to calculate and return a single value.

1. `AVG()`
2. `COUNT()`
3. `MAX()`
4. `MIN()`
5. `SUM()`

**[⬆ Back to Top](#sql)**

## What is the GROUP BY Clause?

- The `GROUP BY` clause groups records into summary rows.
- `GROUP BY` typically also involves aggregates: `COUNT`, `MAX`, `SUM`, `AVG`, etc.

**[⬆ Back to Top](#sql)**

## What is the HAVING Clause?

- `HAVING` filters records that work on summarized `GROUP BY` results.
- `HAVING` applies to summarized group records, whereas `WHERE` applies to individual records.

**[⬆ Back to Top](#sql)**

## What is INNER JOIN?

Select records that have matching values in both tables.

**[⬆ Back to Top](#sql)**

## What is LEFT JOIN?

LEFT JOIN performs a join starting with the first (left-most) table and then any matching second (right-most) table records.

**[⬆ Back to Top](#sql)**

## What is RIGHT JOIN?

RIGHT JOIN performs a join starting with the second (right-most) table and then any matching first (left-most) table records.

**[⬆ Back to Top](#sql)**

## What is FULL JOIN:

FULL JOIN returns all matching records from both tables whether the other table matches or not.

![](https://user-images.githubusercontent.com/11765228/74197422-716f1000-4c9a-11ea-80c5-8c968fb8c879.png)

**[⬆ Back to Top](#sql)**

## What is UNION Clause:

- UNION combines the result sets of two queries.
- Column data types in the two queries must match.

![](https://user-images.githubusercontent.com/11765228/74197415-6d42f280-4c9a-11ea-9510-b7f643bc8d1e.png)

**[⬆ Back to Top](#sql)**



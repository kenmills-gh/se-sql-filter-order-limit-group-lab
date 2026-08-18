# Lab: Filtering, Ordering, Limiting, and Grouping Data with SQL

## Overview
This project involves performing advanced SQL data analysis on three distinct datasets:
1. `planets.db`: Solar system planet statistics.
2. `dogs.db`: Fictional dog characters and their attributes.
3. `babe_ruth.db`: Historical baseball performance metrics for Babe Ruth.

## Objective
The goal was to demonstrate proficiency in:
*   Filtering datasets using `WHERE` clauses and operators.
*   Applying aggregate functions (`SUM`, `COUNT`, `AVG`).
*   Ordering and limiting result sets.
*   Grouping data for relational aggregation.

## Technologies Used
*   Python 3.x
*   Pandas
*   SQLite3
*   pytest (for testing)

## Known Issues / Test Status
As of this submission, the project passes 4 out of 5 unit tests. The test `test_ordering_and_limiting` is failing due to a data type mismatch between Pandas `NaN` values and expected Python `None` values in the `dogs` dataset query. Despite attempts to cast the column, the testing environment continues to identify the missing name as `nan`. All other data logic and SQL queries have been verified as correct.

# SQL

This repository covers key SQL topics with clear notes and solved examples for better understanding.

Comprehensive SQL Guide for Interviews and Real-World Applications

1.Core SQL Concepts
i)SQL Command Categories:
DDL: CREATE, ALTER, DROP
DML: INSERT, UPDATE, DELETE
DCL: GRANT, REVOKE
TCL: COMMIT, ROLLBACK
DQL: SELECT

ii)Joins:
INNER JOIN
OUTER JOIN (LEFT, RIGHT, FULL)
SELF JOIN
CROSS JOIN

iii)Subqueries
Single-row and Multi-row
Multi-column
Correlated and Nested

iv)Constraints:
PRIMARY KEY
FOREIGN KEY
COMPOSITE KEY
UNIQUE
NOT NULL
CHECK

v)Filterations & Orders 
where, having, in/not in, exists/not exists, between, like, is null, is not null, group by, group by rollup, order by, union/union all, interset, except/minus


2)Database Design and Optimization

i)Normalization: 1NF, 2NF, 3NF, and higher forms to reduce redundancy and ensure data integrity.
ii)Indexing: Clustered and Non-clustered indexes , Impact on read/write performance
iii)Query Optimization:
  * Using execution plans (EXPLAIN/EXPLAIN PLAN)
  * Indexing strategies and use of hints
  * Avoiding unnecessary joins and subqueries
  * Efficient use of bulk operations (`BULK INSERT`)



3)Advanced SQL Features
i)Window Functions: ROW_NUMBER(), RANK(), DENSE_RANK(), NTILE()
ii)Aggregate Functions:COUNT(), SUM(), AVG(), MAX(), MIN()
iii)Usage with GROUP BY and HAVING

4)Views :Creating reusable query logic through views

5)Stored Procedures & Functions: Encapsulation of complex logic into reusable blocks

6)Triggers: Automating tasks on INSERT, UPDATE, DELETE events

7)Dynamic SQL: Writing flexible queries using runtime parameters

8)Transactions: COMMIT, ROLLBACK, and SAVEPOINT usage

9)ACID properties (Atomicity, Consistency, Isolation, Durability)
  
10)Error Handling: TRY-CATCH blocks (SQL Server) and equivalent constructs

11)Familiarity with MySQL, PostgreSQL, Oracle Database, SQL Server & their unique features. Best suitable usecase

12)Security and Compliance
i)SQL Injection Prevention:
ii)Use of parameterized queries and stored procedures
iii)Access Control:
*Role-Based Access Control (RBAC), GRANT/REVOKE
* Column-level and Row-level security (RLS)

13)Encryption:
  * Column-level (e.g., Always Encrypted)
  * Transparent Data Encryption (TDE)

14)Regulatory Compliance: GDPR, HIPAA, PCI DSS data handling requirements

15)Execution and Performance Tuning
Query Lifecycle: Parsing → Optimization → Execution → Fetching
Execution Plans: Reading and interpreting plans to find bottlenecks
Locking and Concurrency: Shared, Exclusive, and Intent Locks, Deadlock prevention (`NOWAIT`, `SKIP LOCKED`)

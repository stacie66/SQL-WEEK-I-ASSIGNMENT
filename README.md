SQL Assignment Week 1
1. Components of a DBMS
A Database Management System (DBMS) consists of:

Hardware: Physical storage (servers, disks)

Software: The DBMS application (e.g., MySQL, PostgreSQL)

Data: The stored information (tables, records)

Procedures: Rules for database design and usage

Users:

End Users (interact via apps)

Database Administrators (DBAs) (manage/optimize DB)

Query Processor: Translates SQL queries into actions

Storage Engine: Manages how data is stored/retrieved

2. Relational Database
A database that organizes data into tables with rows/columns and establishes relationships between them using keys.

Examples:

MySQL (open-source, web apps)

PostgreSQL (advanced features, open-source)

Oracle Database (enterprise-grade)

Microsoft SQL Server (Windows ecosystem)

3. Classifications of SQL
DDL (Data Definition Language): Defines structure

CREATE, ALTER, DROP tables

DML (Data Manipulation Language): Manages data

INSERT, UPDATE, DELETE records

DCL (Data Control Language): Manages access

GRANT, REVOKE permissions

4. Primary Key vs. Foreign Key
Primary Key:

Uniquely identifies a record in its table

Ensures no duplicates/null values

Example: user_id in Users

Foreign Key:

References a primary key in another table

Ensures referential integrity

Example: user_id in Orders linking to Users

5. Entity-Relationship Diagram (ERD)
A visual representation of:

Entities (tables, e.g., Student, Course)

Attributes (columns, e.g., student_id, course_name)

Relationships (lines showing connections, e.g., "enrolls in")

6. Advantages of Relational Databases
Data Integrity: ACID compliance (Atomicity, Consistency, Isolation, Durability)

Flexibility: Complex queries with SQL

Scalability: Handles large datasets efficiently

Security: User access controls

7. Data Types for Tables
INTEGER (whole numbers, e.g., age)

VARCHAR (variable-length text, e.g., username)

BOOLEAN (true/false, e.g., is_active)

DATE (dates, e.g., birthdate)

8. Purpose of a DBMS
Centralize data for efficient access

Ensure security (authentication, encryption)

Maintain integrity (avoid duplicates/corruption)

Enable concurrent access (multiple users/apps)

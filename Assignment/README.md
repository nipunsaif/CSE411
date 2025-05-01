# CSE411, Spring 2025

# Assignment equivalent to one quiz

# Full Marks 20

## Part – 1 (ORDBMS)

## Marks: 10

### Title: ORDBMS Database Design, Implementation and Query

### Objective: The objectives of this assignment are:

* to acquire knowledge about database design for Object-Relational DBMS (ORDBMS) model,
* to implement a database in an ORDBMS like Oracle,
* *o insert sample data and run different queries on the database.


### Problem definition

The following attributes describe a student in University Student Information System database: </br>

1. ID: Unique identifier for each entry.
2. Name:
    1. First Name
    2. Middle Name
    3. Last Name
3. Date of Birth
4. CGPA
5. Total Credits
6. Department
7. Address:
    1. Present Address:
       1. House Number
       2. Street
       3. Thana
       4. District
    2. Permanent
       1. House Number
       2. Street
       3. Thana
       4. District
8. Mandatory Fields (Multi-valued):
    1. Phone Number(s)
    2. Email Address(es)
9. Optional Fields (Multi-valued):
       1. Research Interests: Fields of research interest.
       2. Programming Knowledge: Specify languages known (e.g., C, Java).
       3. Educational Qualifications: Structure a record to store academic qualifications (degree, institution, and year of graduation).
10. Family tree
    1. Father and father of father
    2. Mother and mother of mother
11. A student can be player (game, score), organizer (club name, start date, end date).

### Tasks:

Using oracle OORDBMS features and documentations, perform the following: </br>

1. Define types and inheritance
2. Create tables using the types
3. Insert sample data
4. Write queries (2/3) on the data

## Part – 2 (NoSQL DBMS)

## Marks: 10

* Task 1: Using MongoDB NoSQL DBMS, define collection for students and create 5 documents to store the data of 5 students and show some queries on the documents.

* Task 2: For optional fields, data become sparse because of many null values in Relational or Object-Relational model. But in NoSQL model, it does not happen. Describe this from your implementation. 
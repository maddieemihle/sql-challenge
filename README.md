# **SQL-Challenge**

## Background
The fictional company Pewlett Hackard has tasked its new data engineer with a research project involving data modeling, data engineering, and data analysis. The project involves creating a database of employees hired at Pewlett Hackard in the 1980s and 1990s. 

In this assignment, I was tasked with inspecting CSV files and sketching out data using an Entity Relationship Diagram (ERD) of the tables. The tables were then designed to hold the data in the CSVs, imported into the PostgreSQL database, and analyzed. 

## Challenge 

### Part 1: Data Modeling
The CSV files given were inspected and then formatted in a physical schema [text file](https://github.com/maddieemihle/SQL-challenge/blob/main/EmployeeSQL/Employee%20Physical%20Schema.txt). This was then used to sketch an Entity Relationship Diagram table using the took [QuickDBD](https://app.quickdatabasediagrams.com/#/). Like to schema here: [Employee ERD]( https://app.quickdatabasediagrams.com/#/d/ad16ga).

All data was uploaded to pgAdmin using PostgreSQL to engineer into tables.

### Part 2: Data Engineering 
Using the provided information, a [table schema](https://github.com/maddieemihle/SQL-challenge/blob/main/EmployeeSQL/Schema.sql) was created for each of the six CSV files. Data types, Primary Keys, Foreign Keys, and other constraints were added. Next, after the tables were properly created, each CSV file was imported to the corresponding SQL table. 

### Part 3: Data Analysis 
For the data analysis part, each section was broken down into eight parts using PostgreSQL [queries](https://github.com/maddieemihle/SQL-challenge/blob/main/EmployeeSQL/Queries.sql). All questions were answered and tested. 

1. List the employee number, last name, first name, sex, and salary of each employee.

2. List the first name, last name, and hire date for the employees who were hired in 1986.

3. List the manager of each department along with their department number, department name, employee number, last name, and first name.

4. List the department number for each employee along with that employee's employee number, last name, first name, and department name. 

5. List the first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

6. List each employee in the Sales Department, including their employee number, last name, and first name. 

7. List each employee in the Sales and Development Departments, including their employee number, last name, first name, and department name. 
    
8. List the frequency counts, in descending order, or all the employee last names (i.e. how many employees share each last name).

## Methods Used 
* Data engineering 
* Data modeling
* Data analysis 
* SQL 
* ERD 
* Primary keys, Foreign keys, Constraints

## Software Used 
Coding was performed via pgAdmin using PostgreSQL. Entity Relationship Diagram (ERD) was conjured using QuickDBD. Text and visualization was organized by using VSCode. 

## References 
Data for this dataset was given by _edX Book Camp LLC,_ and generated by _Mockaroo, LLC (2022)_ and is intended for educational purposes only. 

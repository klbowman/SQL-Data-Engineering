# Data Engineering  

Data engineering and analysis using SQL. 

## Description

This repository is designed to create a table schema for a SQL database that holds human resources information. Six CSV files that contain 10 years of employee information (i.e., salary, department, titles, management) are stored in the **Data** directory (access from the EmployeeSQL directory). The employee.sql file is queried to create tables outlined in the Entity Relationship Diagram pictured below:  

![image](https://user-images.githubusercontent.com/74067302/146289873-058937a9-cb19-46aa-9586-7a9a9729367d.png)

Once the data is loaded in a SQL database, the DataAnalysis.sql file is queried to list the following information: 
- Details of each employee: employee number, last name, first name, sex, and salary.
- First name, last name, and hire date for employees who were hired in 1986.
- Manager of each department with the following information: department number, department name, the manager's employee number, last name, first name. 
- Department of each employee with the following information: employee number, last name, first name, and department name.
- First name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."
- All employees in the Sales department, including their employee number, last name, first name, and department name.
- All employees in the Sales and Development departments, including their employee number, last name, first name, and department name.
- In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.

## Getting Started

### Technologies Used 

* PostgreSQL

### Installing

* Clone this repository to your desktop.
* Create a new SQL database in PostgreSQL.
* Open and query employee.sql (from the EmployeeSQL directory).
* Open and query DataAnalysis.sql (from the EmployeeSQL directory).

## Data Sources
* Mockaroo, LLC. (2021). Realistic Data Generator. https://www.mockaroo.com/

## Author

Katlin Bowman, PhD

E: klbowman@ucsc.edu

[LinkedIn](https://www.linkedin.com/in/katlin-bowman/)

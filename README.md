## Project Overview

The task was to design a relational database to track users and their favorite books for a start-up that realized that saving information in .csv format will not meet their needs as they grow. The project was divided into three parts:

1. Design an ERD
2. Create the database in Python
3. Export the database and commit to GitHub

In Part 1, an ERD was created to represent a database that tracks users and their favorite books. It was assumed that each book only has one author, but the same author may have written multiple books. Each user should have a first name, last name, and email. Each book should have a title and an author.

In Part 2, a connection was created using PyMySQL, and four tables were added to the database using .csv files that had already been transformed to appropriate normalized tables. The four tables are users, books, authors, and favorites. A query was written to list the titles of all of John Doe's favorite books.

In Part 3, the database was exported as an .SQL file, and both the Jupyter Notebook and the exported .SQL file were committed to GitHub.

## Files in the Repository

- `ERD.png`: An image of the ERD created in Part 1.
- `database_project.ipynb`: Jupyter Notebook containing the code for Part 2.
- `database_export.sql`: SQL file exported from MySQL Workbench in Part 3.

## How to Run the Code

To run the code in the Jupyter Notebook, make sure you have the necessary libraries installed, such as PyMySQL and SQLAlchemy. Then, open the `database_project.ipynb` file in Jupyter Notebook and run each cell in order.

To test the database, run the "SHOW TABLES;" query in the Jupyter Notebook after creating the tables. To list the titles of all of John Doe's favorite books, run the SQL query provided in the notebook.

## Future Improvements

- Normalize the tables further to reduce redundancy and improve efficiency.
- Add more tables to track additional information, such as book genres and user ratings.
 

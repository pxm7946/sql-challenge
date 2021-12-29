# sql-challenge


For this homework assignment, we were asked to take a look at the employees' records of a specific corporation over the span of ten years, which included the department in which they worked in, the employees in that department, as well as the managers, salaries, and titles of each employee. SQL was used to analyze these files. Six (6) CSV files were used, and each of them were imported by using the "SELECT " function. This is an efficient method to load excessive amounts of data entries, and organize them as needed.

 First and foremost, tables from each of the CSV files had to be created by using the "CREATE TABLES" function. The reason for this is to make the files readable, rather than have each entry only be separated by commas. The name of the CSV file was placed after the function. With this, SQL knew which CSV file was retrieved. Each column was imported according the type of information that it carried. Once a table was created for each CSV file with its' according columns, a merged dataframe needed to be created with specific information from each table. An "INNER JOIN" was the function that was used the most in order to retrieve a specific column from a specific table, and add it to a new dataframe. The following are the dataframes that were created:
 
        1. Salary by employee
        2. Employees hired in 1986 
        3. Manager of each department
        4. Department of each employee
        5. Retrieval of employee information based on first name 
        6. Employees in the Sales department
        7. Employees in Sales and Development departments 
        8. Frequency of employee last names 
        
**The creation of each dataframe can be found in the "queries.sql" document.**

As a way to refresh the Matplotlib skills that I have previously learned, I decided to create a histogram and a bar chart to take a closer look at certain factors and view the relationship between them.

In conclusion, SQL is a good tool to load excessive amounts of data onto them and efficiently organize them. The creation of each dataframe was not difficult due to the fact that one is able to type in everything without having to run each line first. Once everything was typed up, each line did have to be ran to successfully create them. An ERD image has been uploaded to view this as well. 

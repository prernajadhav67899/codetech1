Name: Prerna Jadhav                                                                                                                                                            
Company: CODTECH IT SOLUTION                     
ID: CT08DS7660  
Domain: Structured Query Language                                                                                                                                                   
Duration: Sept to Oct 2024  



  
Overwiew of the Projects : - 

___________________________________________________________________________________________________________________________________________________________________________________________

 - TASK 1

Project : Create database library and write queries to insert , update , delete and retrieve data.

Objective :                                                                                                                                                                                
 The Objective of this project is to perform given queries that is data inserting , updating and deleting using proper syntax . The Aim is to maintain a comprehensive database of Library Management System will include table that store and organize information about books , users/students and transaction.  
 
Queries :                                                                                                                                                                                    
 1 . Insert :  This Query writes new rows of data into a table.                                                                                                                            
 2 . Update : This Query changes the data of one or more records in a table .                                                                                                                 
 3 . Delete :This query used to delete existing records from a table.                                                                                                                            
 4 . Retrieve Data : This query is used to specify the columns you want to retrieve from the database.

Technologies Used : 
- My Structured Query Language (MYSQL)

  
Detailed Information : 

 In this task, we will follow a structured process to create and manage a library database.                                                                                                
 The steps include:

Create the Database:                                                                                                                                                                     
 We will begin by creating a database named library and then select it for use.

Create the Members Table:                                                                                                                                                             
 Next, we will create a table called members to store information about library members including their id , names , emails and phone numbers.
 We will then insert several records into this table and display the information.

Create the Books Table:                                                                                                                                                           
 Following that, we will create a table named books to keep track of the books available in the library, including titles, authors and available copies.
 Again, we will insert data into this table and display the records.

Create the Borrowings Table:                                                                                                                                                               
 We will then establish a borrowings table to record which members have borrowed which books, along with the dates of borrowing and returning.
 We will insert relevant data and show the entries.

Perform Update and Delete Operations:                                                                                                                                              
 Finally, we will demonstrate how to update existing records (such as member details or book availability) and delete records when necessary.  

___________________________________________________________________________________________________________________________________________________________________________________________


- TASK 2

Project :  create database and implement different joins to combine data from multiple tables . 

Objective :                                                                                                                                                                             
 The primary objective of this project is to demonstrate and implement various types of JOIN operations in a relational database. This will allow for the effective combination of data from multiple tables, showcasing the relationships and dependencies between different datasets.

JOINS : 
1. INNER JOIN : Retrieves records that have matching values in both tables. It’s useful when you only want data that exists in both tables.
2.  LEFT JOIN (LEFT OUTER JOIN) : Returns all records from the left table and matched records from the right table. If there’s no match, NULL values are returned for columns from the right table.
3.  RIGHT JOIN (RIGHT OUTER JOIN) : Returns all records from the right table and matched records from the left table. If there’s no match, NULL values are returned for columns from the left table.
4.  FULL OUTER JOIN :  Combines results from both left and right tables, returning all records with matching values where available, and NULL for non-matching records.


Technologies Used :                                                                                                                                                                        
 -  My Stuctured Query Language (MYSQL)


Detiled Information : 

1 . Create Students Table:                                                                                                                                                                 
    Define a table to store student information, including ID , name , division , and Phone . 

2 . Create Courses Table:                                                                                                                                                               
    Define a table for course details including ID, name and fees .

3 . Create Enrollments Table:                                                                                                                                                        
    Define a linking table that connects students and courses including foreign keys for student and course IDs.

4 . Insert Sample Data:                                                                                                                                                            
   Populate each table with sample records for students, courses, and enrollments.

5 . Perform JOINS:                                                                                                                                                                    
    INNER JOIN: Retrieve students enrolled in courses.                                                                                                                                   
    LEFT JOIN: Get all students and their courses, including those not enrolled.                                                                                                        
    RIGHT JOIN: Get all courses and their enrolled students.

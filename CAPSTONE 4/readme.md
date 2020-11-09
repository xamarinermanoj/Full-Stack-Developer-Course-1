# Capstone Project #4  <br/>ASP&#46;NET CORE 


## Problem Statement

The management at Contoso University would now like you to design the web application using the front-end you designed during the **Capstone Project #1 - (HTML5, JS, CSS3, BootStrap, jQuery, AJAX)**, and the Database Schema you derived during the **Capstone Project #2 - (SQL Server)**.  

You are expected to create one single ASP&#46;NET CORE project to showcase your understanding of the C# language and ASP.NET CORE (Razor Pages and Razor Views), along with  Entity Framework Core and SignalR concepts learnt during your training so far.

Ensure that:
- The application should come with a pre-seeded Account for the University Principal.
- Students can directly Register on the Contoso University Portal 
- Departments, Subjects and Teachers would be added by the University Principal.
- The Principal would assign Subjects and Departments to the Teacher.
- Registered Students would be mapped to the Subjects by the Teacher.


## Data to Manage

 1. Teachers
 2. Students
 3. Subjects
 4. Departments
 
- Each Teacher may or may not have multiple Students.
- Each Department would have one or more Teachers, and one or more Subjects.
- Each Teacher may or may not teach multiple Subjects.  The Subjects should belong to only those Departments that the Teacher is registered into.
- Each Student would be registered to study one or more Subjects.

Create the needed database, with these Tables, enforcing proper relationships.



## Stake holders to the application

1. University Principal *(The Admin)*
2. Management - consisting of Teachers, Department Heads and Admin Staff
3. Students

All (Teacher, Student, The University Principal and Administrative Staff) would have access to the application, and would be controlled by Access Permission Grants, configured within the application.



## Task - Day #01


1. Create a New ASP&#46;NET CORE Project choosing ___Website Template___ and ___Individual User Accounts___).

2. Scaffold the ___Identity Templates___, so that you can customize the UI.

3. Register and Configure the ___Email Sender___ Service

4. Register and Configure the ___Logging___ Service

5. Customize the Identity Models for ___USER___ and ___ROLE___ 

6. Generate the ___Migration Scripts___ and seed the database.

7. Configure ___LibMan___ for the needed CSS and JavaScript libraries

8. Configure ___BundleConfig___ for bundling and minification of CSS and JavaScript files.

9. Customize the Page Layouts, and Templates to leverage upon the updated UI Libraries.


## Task - Day #02 and Day #03

10. Add the Models needed for managing the data 

11. Generate the ___Migration Scripts___ to seed the database

12. Add an ___Area___ called *ALLUSERS* consisting of a Dashboard for the application, to display a customized dashboard depending upon the user.    This would be accessible to all the types of users of the application.

13. Add an ___Area___ called *ADMIN* to handle the add / edit / delete / view / list operations for Teachers, Departments and Subjects.  This would be accessible to the Prinicipal, Department Head and Management Users.

14. Add an __Area__ called *MANAGE* to manage Students, like mapping the subjects to the Student, Viewing Reports, etc.  This would be accessible to the Department Head, Management Users, and Teachers.

15. Add the various Reports as documented during the **Capstone Project #2 - (SQL Server)**


## Task - Day #04

16. Design and Configure a Chat Application using **SignalR** to allow students of a particular subject to interact with each other.


## Task - Day #05

17. Provision a **SQL Azure Shared Instance** for the application, and run the SQL Scripts to prepare the Cloud Database for the portal.

18. Tweak the application, especially:
- Implementing **Output Caching** where needed
- **Disable Output Caching** in secured pages
- Ensure **CDN  and fallback Static Content** is configured, along with **Bundling and Minifcation Services** for optimized content delivery
- Ensure **Debugging and Logging Services** are duly configured, as best suited to the deployment environments.  
- Configure the correct Database Connection Strings

19. Publish this application on to the Azure Platform as a **WebApp** Service.

---

All the very best :thumbsup: !!

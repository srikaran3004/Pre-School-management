Pre-School Enrollment System
The Pre-School Enrollment System is a web-based application designed to streamline the process of pre-school enrollment. This system enables parents to check pre-school information, schedule school visits, and fill out enrollment forms online. The project is built using PHP and MySQL and features three modules: User, Admin, and Sub-Admin.

Features
User Module
Home Page: Displays a welcome page with brief information about the pre-school.
About Us: Provides detailed information about the pre-school.
Classes: Displays information about the available classes.
Contact Us: Provides contact details of the pre-school.
Schedule a Visit: Allows parents to schedule school visits.
Enroll Now: Enables parents to fill out the enrollment form for their child.

Admin Module
Dashboard: Overview of total sub-admins, classes, teachers, enrollments, and visitor data.
Sub-Admins: Add, edit, delete, and reset passwords for sub-admins.
Teachers: Manage teachers by adding, updating, or deleting their details.
Classes: Add, edit, or delete class information.
Enrollments: View and manage new, approved, or rejected enrollments.
Visits: Track and manage scheduled visits.
Pages: Update content for the "About Us" and "Contact Us" pages.
Account Settings: Update admin profile and change passwords.
Password Recovery: Allows admin to recover lost passwords.

Sub-Admin Module
All features of the Admin Module except Sub-Admin creation.

Technologies Used
Backend Language: PHP (5.6, 7.x)
Database: MySQL (5.x)
Frontend: HTML, AJAX, jQuery, JavaScript
Web Browsers Supported: Google Chrome, Mozilla Firefox, Internet Explorer 8+, Opera
Software Requirements: XAMPP / WAMP / MAMP / LAMP

Project Setup Instructions
Steps to Run the Project
Download the Project
Download the project zip file from the repository.

Extract Files
Extract the zip file and copy the preschool folder.

Place in Root Directory
Paste the folder in your server’s root directory:

For XAMPP: xampp/htdocs
For WAMP: wamp/www
For LAMP: var/www/html
Create Database

Open PHPMyAdmin in your browser.
Create a database named preschooldb.
Import Database

Locate the SQL file inside the project folder (preschool/sql/preschooldb.sql).
Import it into the preschooldb database.
Run the Project

Open your browser and visit: http://localhost/preschool
Screenshots
1. Home Page


2. New Enrollment


3. Admin Dashboard


4. Admin New Enrollments

Contributions
Feel free to fork this repository and contribute to the project. Pull requests are welcome!

Author
Srikaran
Contact Information:
Email: srikaran2230@gmail.com


Let me know if you need any changes! 😊

🎓 Student Marks Calculation System

1. ✅ Project Overview

The Student Marks Calculation System is a web application designed to simplify the recording, calculating, and presentation of student academic results. Faculty members can log in to enter internal marks from three midterm exams as well as external exam scores. Meanwhile, students have access to view their final grades and report cards. This system is ideal for schools, colleges, and universities and supports both faculty and student user roles.

2. 💻 Project Structure

Key files and components included in the project:

* app.py: The main backend server application
* index.html`: The landing page featuring login and registration forms
* student-dashboard.html`: Student panel for viewing marks and reports
* faculty-dashboard.html`: Faculty panel for entering student marks
* `report-card.html`: Page showing final grades and detailed marks
* `student\_mark.sql`: SQL script managing the database schema and queries

 3. 🔧 Technologies Used

Frontend: HTML, CSS, JavaScript
Backend: Python with Flask framework
Database: MySQL
API:** RESTful services for handling faculty and student interactions
Session Storage: Utilizes localStorage for managing logged-in user sessions

4. 📝 System Description

Features of the system include:

* Faculty members can log in and input internal marks from three midterm exams (Mid1, Mid2, Mid3) and external exam marks.
* The system calculates internal marks by taking the best two midterm scores and averaging them (maximum 25 marks each).
* Final marks are calculated by adding the averaged internal marks and external marks (externals are out of 75).
* Grades are assigned according to the final total marks.
* Students logging in can:

 * View subject-wise internal, external, and final marks breakdown
 * See their assigned grades per subject
 * Check overall totals and average marks
* Faculty users can:

 * Enter internal and external marks for students
 * View external marks of all students
 * Access information about all students assigned to them

 5. 📊 Screenshots & Output

![Screenshot 2025-05-26 210310 (1)](https://github.com/user-attachments/assets/1b4b809f-16b5-4868-8744-8fae1d514178)
![Uploading Screenshot 2025-05-26 210219 (1).png…]()
![Screenshot 2025-05-26 210022 (1)](https://github.com/user-attachments/assets/09b3961e-2fcf-4bd7-8d82-838146fc9c16)




 6. 🔍 Future Enhancements

* Add functionality to export report cards as PDF documents
* Replace localStorage with JWT-based authentication for improved security
* Integrate analytics and charts for tracking academic progress
* Make the user interface fully responsive for mobile devices
* Implement a feedback system where students can submit remarks for each subject


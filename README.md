

# Quizller - Quiz System
<table>
  <tr>
    <td>
       Quizller is a php based open source web application to create and manage online quiz, test, exam. 
    </td>
  </tr>
</table>

## Table of contents

* [Features](#features)
* [ScreenShots](#screenshots)
  - [User Side](#user-side)
  - [Admin Side](#admin-side)
* [Steps to install](#steps)
* [Project Overview](#project-overview)
* [Technology Stack](#technology-stack)


### Features
- Fully Functional Admin Panel
- Quiz Website with awesome UI
- Admin (teacher) can add class and students from admin panel
- Admin can create new quiz tests and add quiz questions in the test
- Option to add the Quiz questions from a spreadsheet (.xls, .xslx, .ods)
- Admin can view the statistics of the tests such as score of the students and quiz questions tests
- Generate run-time random passwords for users to give test
- Generate pdf option so that admin can directly print the student login credentials for the test

### ScreenShots
#### User Side
<table>
  <tr>
    <td>
      <p><b>Login Page</b></p>
      <p>The Login Page of the website for student</p>
      <img src="http://iamrohitsuthar.000webhostapp.com/android/github/quizller/student_login.png"/>
    </td>
    <td>
      <p><b>Dashboard Page</b></p>
      <p>List of tests for student</p>
      <img src="http://iamrohitsuthar.000webhostapp.com/android/github/quizller/student_dashboard.png"/>
    </td>
  </tr>
  
  <tr>
    <td>
      <p><b>Quiz</b></p>
      <p>Here student have to select the one option from the four options of the Quiz question</p>
      <img src="http://iamrohitsuthar.000webhostapp.com/android/github/quizller/student_quiz.png"/>
    </td>
    <td>
      <p><b>Quiz Done</b></p>
      <p>Logout message page displayed when the user finished with the quiz test</p>
      <img src="http://iamrohitsuthar.000webhostapp.com/android/github/quizller/student_test_finish.png"/>
    </td>
  </tr>
</table>

#### Admin Side
<table>
  <tr>
    <td>
      <p><b>Login Page</b></p>
      <p>The Login Page of the website for Admin (Teachers) </p>
      <img src="http://iamrohitsuthar.000webhostapp.com/android/github/quizller/admin_login.png"/>
    </td>
    <td>
      <p><b>Dashboard Page</b></p>
      <p>List of pending tests created by the admin</p>
      <img src="http://iamrohitsuthar.000webhostapp.com/android/github/quizller/admin_dashbaord.png"/>
    </td>
  </tr>
  
  <tr>
    <td>
      <p><b>Create New Test</b></p>
      <p>Admin can create new quiz test</p>
      <img src="http://iamrohitsuthar.000webhostapp.com/android/github/quizller/admin_new_test.png"/>
    </td>
    <td>
      <p><b>Test Details</b></p>
      <p>Here admin can change the test details</p>
      <img src="http://iamrohitsuthar.000webhostapp.com/android/github/quizller/admin_test_details.png"/>
    </td>
  </tr>
  <tr>
  <td>
    <p><b>Add Question</b></p>
    <p>Admin can add new question to the test</p>
    <img src="http://iamrohitsuthar.000webhostapp.com/android/github/quizller/admin_add_question.png"/>
  </td>
  <td>
    <p><b>Add Question</b></p>
    <p>Admin can add the question into quiz from a spreadsheet</p>
    <img src="http://iamrohitsuthar.000webhostapp.com/android/github/quizller/admin_excel.png"/>
  </td>
</tr>
<tr>
<td>
  <p><b>Add Class / Add Students</b></p>
  <p>Admin can add new class and new students to the existing class</p>
  <img src="http://iamrohitsuthar.000webhostapp.com/android/github/quizller/admin_class_student.png"/>
</td>
<td>
  <p><b>View Class Data</b></p>
  <p>Admin can see the list of students present in the class</p>
  <img src="http://iamrohitsuthar.000webhostapp.com/android/github/quizller/admin_view_data.png"/>
</td>
</tr>
<tr>
<td>
  <p><b>Test Questions</b></p>
  <p>Admin can add see the quiz test questions</p>
  <img src="http://iamrohitsuthar.000webhostapp.com/android/github/quizller/admin_questions.png"/>
</td>
<td>
  <p><b>Students test data</b></p>
  <p>Admin can print the student roll number and random password list</p>
  <img src="http://iamrohitsuthar.000webhostapp.com/android/github/quizller/admin_test_cred.png"/>
</td>
</tr>
</table>

### Steps
1. Copy the whole project into your WAMP/LAMP/XAMPP folder.
2. Now create the database and import the script.sql file present in the database folder.
    1. If you want some sample data run the import the sampleData.sql file instead.
    2. Sample admin username:password for sampleData is admin:nimda
3. Modify the database credentials config.php file present in the database folder.
4. Now run the project to enjoy the Awesome Quiz System.

### Project Overview
**The website generates random passwords for students for each test.**
1. Dashboard
    1. Create new tests
    2. See previously created tests
2. New Test ( Needs class data first )
    1. Create new test for a class
    2. Test status:
      2.1 Pending - test won't be shown to students
      2.2 Running - test will be shown and students can give test
3. Add class / student
    1. Add a new class
    2. Add a new student to the class
4. View Data
    1. Shows student user id / roll numbers given a class
5. Test Details ( on clicking a previously created test from dashboard )
    1. Change status of Quiz ( PENDING / RUNNING )
    2. Complete / delete test
    3. Add new student explicitly for the test
    4. Add questions to the test

### Technology Stack
- HTML, CSS, BOOTSTRAP (Front-end)
- PHP (Backend)
- MYSQL Database
  


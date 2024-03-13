A web portal which helps to understand the placement scenario and ease of conducting it. It will contain two separate logins for student and and the HR. After logging in a student will have the choices like see the different aspects and information about different companies. Even a company HR will be provided with some filters to filter the students according to his criteria and requirement of the post. The website frontend has been made using Html, Css,Javascript and Bootstrap. As our website will be having adatabase to store the data related to enitity types in ourplacement cell portal, we have made our database using MySQL in PhpMyAdmin. The frontend connection with the database has been made using php. We have used XAMPP server to run our website on localhost.






DATABASE
MySQL Database is used to store the data related to enitity types in our placement cell portal, we have made our database in PhpMyAdmin.The frontend connection with the database has been made using php.




SIGNUP FOR HR AND STUDENT
Hr signup: For hr signup a form is created containing fields - (Id, Name, Department, Email, Company). When the form is submitted the information will get stored in the database.
Code File for hr signup frontend - signuphr.php
Code File for pushing hr singup values in database - hrprocess.php

For student signup a form is created for students to enter their information. Resume needs to be uploaded by the student(type - pdf,docx). When the form is submitted the information will get stored in the database. The resume file is pushed into a folder named uploads and its filename will be stored in the database
Code File for student signup frontend - signupstud.php
Code File for pushing student singup values in database - studprocess.php

 


LOGIN FOR HR AND STUDENT
A form has been created to enter the login credenitals for Hr and Student. The login information will be validated by comparing the data in the database.
Hrlogin frontend page code file : loginhr.php
Hrlogin validating code file : processhrlog.php

Student login frontend page code file : loginstud.php
Student login validating code file : processtudlog.php


 

FILTERS FOR HR
After login the HR will be having multiple choices and filters to view the students according to the choices he selects.
The following filters are available to the HR:
1.He can select a particular branch he wants the student to have bachelor’s degree in.
2.Select min cgpa a student must have.
3.Select the post for which he wants to hire and view students who applied for that post.
4.Select the university you want to hire from.
Code for frontend of this page : finalhr.php
Code for processing data from frontend form : processfinalhr.php



Displaying information based on HR filters
Suppose HR wants to have students having:
Degree in Information Technology
Minimum cgpa of 8.5
Applied for web developer
College - VIT VELLORE


FILTERS FOR STUDENT
After login the student will have filters to view the information about the companies post and hr according to the choices he/she selects.
Filters for student:
1.Select company and see the posts they are hiring from.
2.Enter the minimum salary you expect and see the companies offering more salary than that.
3.Select post and see the HR information who is going to hire you.



Displaying information based on student filters.
Suppose student wants to see the posts amazon is hiring for. The stduent selects amazon in the first filter.



CONCLUSION
We have successfully developed a web application which helps the students as well as Hr during the placement season. Instead of filling the google forms multiple times for different companies, it will require the students to just enter their details and resume one time and also keep them updated with the companies coming to the campus and the posts and ctc they are offering. Similarly the HR will not need to sort students manually, our portal will provide the HR with several filters he can apply and sort out the students and then view their resumes separately which makes this process easy and time efficient.

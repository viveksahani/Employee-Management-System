# Employee-Management-System
A fully responsive with database connection employee management system developed for windows form application using .net c#

<b>Note:</b>
<br>Instruction to setup :-</b>

<b>Step 1: </b>
create a database named 'ems' inside it create a table named 'employee' with following details exactlly-

create table employee (id int primary key, 
name varchar(100) not null,
address varchar(255) not null,
contact varchar(10) not null,
email varchar(100) not null,
designation varchar(100) not null,
department varchar(100) not null,
joinDate varchar(10) not null,
wageRate int not null,
workedHour int not null
);

<b>Step 2: </b>
Copy your SQL server name and paste at Data Source name present in 'AddEmployee.cs', 'Form1.cs' and 'Form2.cs' files

<b>That's all enjoy</b>


This is the main page:

![Screenshot (27)](https://github.com/viveksahani/Employee-Management-System/assets/94420688/4d03baa7-bd10-4ef7-a936-c8fb1a33d59f)



Once you click on add employee icon this dialog box appear to enter employee details. This is fully responsive and validated so that you can not be able to enter inapprpriate data. ID no is pre entered and you can not edit basically this field is blocked to edit, this id field is getting it's data on the basis of maximum id no present in the database of employee. 

![Screenshot (29)](https://github.com/viveksahani/Employee-Management-System/assets/94420688/f4e4052d-46c9-4d42-a257-7b80378bcc56)



Now click on refresh button, you see that data has been added in in the database.

![Screenshot (30)](https://github.com/viveksahani/Employee-Management-System/assets/94420688/63464848-1501-479e-b2c5-feaacd383e77)



Now click on edit button to edit the info of employee, a little box will appear to enter employee id which you want to edit.

![Screenshot (31)](https://github.com/viveksahani/Employee-Management-System/assets/94420688/df9a2e67-45ab-4a6d-be12-d663cea4ce93)




Now this dialog box will appear to edit the details of employee of id entered by you.

![Screenshot (32)](https://github.com/viveksahani/Employee-Management-System/assets/94420688/ae0395df-4bd1-4554-bde6-62c6cedb1706)




now you can data has been updated in the database.

![Screenshot (33)](https://github.com/viveksahani/Employee-Management-System/assets/94420688/8ebee381-70e3-46bc-b81e-39425f3aaf45)




Now click on delete icon, this box will apper to enter id of employee which you want to delete.

![Screenshot (34)](https://github.com/viveksahani/Employee-Management-System/assets/94420688/7c8d9d72-6ab7-48dc-894f-0aabee25041b)




Now this dialog box apper to the details of employee which you are going to delete. And all fields are blocked to edit the info. Once you click on delete button, employee will be deleted from the database.

![Screenshot (35)](https://github.com/viveksahani/Employee-Management-System/assets/94420688/c4859063-1ea1-4a68-b451-f6b86dbd14fc)




here you can see data has been deleted from the database.

![Screenshot (36)](https://github.com/viveksahani/Employee-Management-System/assets/94420688/9c6a1a52-0eb9-47ab-bb5d-00d10b2d75d9)




Now come to importing data from .csv file. Click on import icon (open folder like icon) to open the .csv file present in your system.

![Screenshot (37)](https://github.com/viveksahani/Employee-Management-System/assets/94420688/76488b6a-4350-492d-a3ad-da2e3f2e88a7)




Once you opened the .csv file and no error detected in selected file then a small dialog box will show data has been imported successfully, click on Ok then all data will be reflected in the database also.

![Screenshot (38)](https://github.com/viveksahani/Employee-Management-System/assets/94420688/4faa1452-0980-4c4e-85e9-e21a41d57b9a)





Now if you want to see the report of all different department and their wage collection then click on graph icon will display this pie chart with suitable colors.

![Screenshot (39)](https://github.com/viveksahani/Employee-Management-System/assets/94420688/7a6dc4c5-fcb1-490c-80b4-01f274c5221d)








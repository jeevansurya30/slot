# Ex03 Time Table
01.10.23
## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## CODE
html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - Jeevansurya  (212222040061)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
<th bgcolor="yellow">Saturday</th>
</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>
<td>DPSD</td>
<td>FWAD</td>
<td>DBMS</td>
<td>DPSD</td>
<td>MAT</td>
<td>OS</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>FREE SLOT</td>
<td>COM</td>
<td>SE</td>
<td>SNLT</td>
<td>DPSD</td>
<td>FREE SLOT</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="6" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>MAT</td>
<td>COM</td>
<td>FREE SLOT</td>
<td>DBMS</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>OS</td>
<td>FWAD</td>
<td>DBMS</td>
<td>FWAD</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development (FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19EC307</td>
<td>Comunication Engineering (COM)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19EC303</td>
<td>Digital Principles And System Design (DPSD)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19EY703</td>
<td>System of Numerical and Logical Terminologies (SNLT)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19CS404</td>
<td>Database Management System and its Applications (DBMS)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19CS408</td>
<td>Software Engineering (SE)</td>
</tr>
</tr>
<td align="center">7.</td>
<td align="center">19MA212</td>
<td>Algebra and Number Theory (MAT)</td>
</tr>
</tr>
<td align="center">8.</td>
<td align="center">19CS405</td>
<td>Operating System (OS)</td>
</tr>
</table>
</body>
</html>

## OUTPUT
![Screenshot 2023-11-06 201002](https://github.com/jeevansurya30/slot/assets/129417865/9bcdc06a-7be5-46a4-abdd-634035620a60)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

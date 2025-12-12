# Ex03 Time Table
## Date: 05.12.2025
## ref no: 25003567
## Name:Roshan.p        

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

## PROGRAM
~~~

<<html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - ROSHAN P (25003567)</b></caption>
<tr align="center">
<th bgcolor="white">Day/Time</th>
<th bgcolor="white">Monday</th>
<th bgcolor="white">Tuesday</th>
<th bgcolor="white">Wednesday</th>
<th bgcolor="white">Thursday</th>
<th bgcolor="white">Friday</th>
<th bgcolor="white">saturday</th>
</tr>
<tr align="center">
<th bgcolor="green">8-10</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>FREE SLOT</td>
<td>python programming</td>
</tr>
<tr align="center">
<th bgcolor="red">10-12</th>
<td></td>
<td>PYTHON PROGRAMMING</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<th colspan="5" align="center">L U N C H</th>
</tr>
<tr align="center">
<th bgcolor="green">1-3</th>
<td>FREE SLOT</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>MENTOR MEET</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>COMMUNICATIVE ENGLISH</td>
</tr>
<tr align="center">
<th bgcolor="red">3-5</th>
<td>FREE SLOT</td>
<td>PYTHON PROGRAMMING</td>
<td>PYTHON PROGRAMMING</td>
<td>PYTHON PROGRAMMING</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>FREE SLOT</td>
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
<td align="center">19AI301</td>
<td>PYTHON PROGRAMMING (PYTHON PROGRAM)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19EN101</td>
<td>COMMUNICATIVE ENGLISH (COM ENG)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">ECA-M</td>
<td>MENTOR MEET (MENTOR)</td>
</tr>
<tr>
</table>
</body>
</html>

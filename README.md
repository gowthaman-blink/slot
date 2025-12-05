# Ex03 Time Table
## Date:28/11/2025
# NAME : a k gowthaman
# reg no: 25017622

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
<html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="grey">
<caption><b>SLOT TIME TABLE - a.k gowthaman (25017622)</b></caption>
<tr align="center">
<th bgcolor="blue">Day/Time</th>
<th bgcolor="red">Monday</th>
<th bgcolor="green">Tuesday</th>
<th bgcolor="white">Wednesday</th>
<th bgcolor="purple">Thursday</th>
<th bgcolor="cyan">Friday</th>
</tr>
<tr align="center">
<th bgcolor="pink">8-10</th>
<td>free slot</td>
<td>python programming</td>
<td>python programming</td>
<td>free slot</td>
<td>Free slot</td>
</tr>
<tr align="center">
<th bgcolor="lavander">10-12</th>
<td>FREE SLOT</td>
<td>python programming</td>
<td>web development</td>
<td>web development</td>
<td>web development</td>
</tr>
<tr>
<th bgcolor="olive green">12-1</th>
<td colspan="5" align="center"bgcolor="yellow">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="purple">1-3</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>mentor meet</td>
<td>python programming</td>
<td>free slot</td>
</tr>
<tr align="center">
<th bgcolor="violet">3-5</th>
<td>python programming</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>web development</td>
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
<td bgcolor="green" align="center">1.</td>
<td bgcolor="green"="center">19AI414</td>
<td bgcolor="green">Web Application Development </td>
</tr>
<tr>
<td bgcolor="cyan"="center">2.</td>
<td bgcolor="cyan"center">19AI301</td>
<td bgcolor="cyan">python PROGRAM</td>

<tr>
<td bgcolor="red" align="center">4.</td>
<td bgcolor="red"="center"></td>
<td bgcolor="red">mentor meet</td>
</tr>
<tr>

~~~

## OUTPUT
![alt text](<Screenshot 2025-12-05 110751.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

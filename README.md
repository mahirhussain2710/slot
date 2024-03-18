# Ex03 Time Table
## Date:14-3-2024

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
```
<html>
	<head>
		<title>Mahir Hussain Time Table</title>
	</head>
	<body align="center">
        <img src="logo.png" height="200" width="800" >
	<table border="2" cellspacing="5" cellpadding="5" width="800" height="50" align="center">
        <caption> SLOT TIME TABLE-Mahir Hussain S(212223040109)</caption>
		<tr bgcolor="pink" align="center">
			<th>Day/Time</th>
			<th>Monday</th>
			<th>Tuesday</th>
            <th>Wednesday</th>
			<th>Thursday</th>
			<th>Friday</th>
		</tr>
		<tr bgcolor="gold" align="center">
			<th bgcolor="pink">8-10</th>
			<td>FREE SLOT</td>
			<td>DE</td>
			<td>BEEE</td>
			<td>DE</td>
			<td>WEB</td>
		</tr>
		<tr bgcolor="gold" align="center">
			<th bgcolor="pink">10-12</th>
			<td>Calculus</td>
			<td>C Prog</td>
			<td>FREE SLOT</td>
			<td>C Prog</td>
			<td>Calculus</td>
		</tr>
		<tr bgcolor="gold" align="center">
			<th bgcolor="pink">12-1</th>
			<td colspan="5" align="center">LUNCH</td>
		</tr>
		<tr bgcolor="gold" align="center">
			<th bgcolor="pink">1-3</th>
			<td>BEEE</td>
			<td>WEB</td>
			<td>CSFC</td>
			<td>WEB</td>
			<td>FREE SLOT</td>
		</tr>
		<tr bgcolor="gold" align="center">
			<th bgcolor="pink">3-5</th>
			<td colspan="5" align="center">FREE SLOT</td>
	</table>
    <br>
    <table border="2" cellspacing="5" cellpadding="5" width="800" height="50" align="center">
        <tr bgcolor="pink" align="center">
            <th>S.No</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr bgcolor="gold" align="center">
            <th bgcolor="pink">1.</th>
            <td>19AI304</td>
            <td>Fundamentals of C Programming(C prog)</td>
        </tr align="center">
        <tr bgcolor="gold" align="center">
            <th bgcolor="pink">2.</th>
            <td>19AI414</td>
            <td>Fundamentals of Web application Development(FWAD)</td>
        </tr>
        <tr bgcolor="gold" align="center">
            <th bgcolor="pink">3.</th>
            <td>19EE305</td>
            <td>BEEE</td>
        </tr>
        <tr bgcolor="gold" align="center">
            <th bgcolor="pink">4.</th>
            <td>19EE404</td>
            <td>Digital Electronics(DE)</td>
        </tr>
        <tr bgcolor="gold" align="center">
            <th bgcolor="pink">5.</th>
            <td>19EY702</td>
            <td>Creative skills for communications(CSFC)</td>
        </tr>
        <tr bgcolor="gold" align="center">
            <th bgcolor="pink">6.</th>
            <td>19MA201</td>
            <td>Calculus and Matrix Algebra(Calculus)</td>
        </tr>
    </table>
	</body>
</html>-
```
## OUTPUT
![alt text](<Screenshot (6).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

# Ex03 Time Table
## Date:20.03.2024

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
</html>

<!DOCTYPE html>
<html>
    <head>
        <title>Timetable</title>
    </head>
    <body>
        <center>
            <img src="logo.png" height="200" width="500">
        </center>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="4" bgcolor="pink">
<caption><b>SLOT TIME TABLE -   JESU SMARTIA A NC(212223110016)</b></caption>
<tr align="center">
<th bgcolor="lightgreen">Day/Time</th>
<th bgcolor="lightgreen">8-10</th>
<th bgcolor="lightgreen">10-12</th>
<th bgcolor="lightgreen">12-1</th>
<th bgcolor="lightgreen">1-3</th>
<th bgcolor="lightgreen">3-5</th>
<th bgcolor="lightgreen">5-7</th>
</tr>

<tr align="center">
<th bgcolor="lightgreen">Monday</th>
<th bgcolor="pink">PHY</th>
<th bgcolor="pink">BEE</th>
<th bgcolor="pink" rowspan="6" align="center">LUNCH BREAK</th>
<th bgcolor="pink">WEB</th>
<th bgcolor="pink">C</th>
<th bgcolor="pink">EMPD</th>

</tr>

<tr align="center">
<th bgcolor="lightgreen">TuesdaY</th>
<th bgcolor="pink">FREE SLOT</th>
<th bgcolor="pink">WEB</th>
<th bgcolor="pink">FREE SLOT</th>
<th bgcolor="pink">FREE SLOT</th>
</tr>

<tr align="center">
<th bgcolor="lightgreen">Wednesday</th>
<th bgcolor="pink">WEB</th>
<th bgcolor="pink">FREE SLOT</th>
<th bgcolor="pink">STAT</th>
<th bgcolor="pink">CN</th>
</tr>

<tr align="center">
<th bgcolor="lightgreen">Thrusday</th>
<th bgcolor="pink">PHY</th>
<th bgcolor="pink">CREATIVE</th>
<th bgcolor="pink">BEE</th>
<th bgcolor="pink">EDM</th>
<th bgcolor="pink">EMPD</th>

</tr>

<tr align="center">
<th bgcolor="lightgreen">Friday</th>
<th bgcolor="pink">EDM</th>
<th bgcolor="pink">C</th>
<th bgcolor="pink">CN</th>
<th bgcolor="pink">FREE SLOT</th>
</tr>

<tr align="center">
<th bgcolor="lightgreen">Saturday</th>
<th bgcolor="pink">FREE SLOT</th>
<th bgcolor="pink">FREE SLOT</th>
<th bgcolor="pink">STAT</th>
<th bgcolor="pink">FREE SLOT</th>
</tr>

</table>

<br>
<table align="center" cellspacing="2" cellpadding="4" border="4">
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
<td align="center">19EE305</td>
<td>Basic Electric And Electronic Measurement(BEE)</td>
</tr>

<tr>
<td align="center">3.</td>
<td align="center">19CS406</td>
<td>Computer Networks(CN)</td>
</tr>

<tr>
<td align="center">4.</td>
<td align="center">19AI302</td>
<td>Engineering Design and Modeling (EDM)</td>
</tr>

<tr>
<td align="center">5.</td>
<td align="center">19AI304</td>
<td>Fundamentals of C Programming(C)</td>
</tr>

<tr>
<td align="center">6.</td>
<td align="center">19AI303</td>
<td>Engineering Mechanics and Product Development(EMPD)</td>
</tr>

<tr>
<td align="center">7.</td>
<td align="center">19EY702</td>
<td>Creative Skills (CREATIVE)</td>
</tr>

<tr>
<td align="center">8.</td>
<td align="center">19MA211</td>
<td>Statistics and Numerical Methods (STAT)</td>
</tr>
<tr>
    <td align="center">9.</td>
    <td align="'center">19PH214</td>
    <td>Physics for Quantum computing (PHY)</td>
</tr>
</table>
</body>
</html>
```

## OUTPUT

![Screenshot 2024-03-20 084920](https://github.com/jesu-smartia05/slot/assets/148514819/ff45da06-3f0c-4ba0-b291-09b92856a9fa)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

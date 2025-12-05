# Ex03 Time Table
## Date: 5.12.2025
## Reference number:25012447

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
<html>
    <head>
        <title>Slot Timetable</title>
    </head>
    <body>
        <center>
            <img src="/static/logo.png" height="100" width="540">
        </center>
        <br>
        <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="pink">
            <caption><b>SLOT TIME TABLE - SHUNMATHI S S (25012447)</b></caption>
            <tr align="center">
                <th bgcolor="grey">Day/Time</th>
                <th bgcolor="grey">Monday</th>
                <th bgcolor="grey">Tuesday</th>
                <th bgcolor="grey">Wednesday</th>
                <th bgcolor="grey">Thursday</th>
                <th bgcolor="grey">Friday</th>
                <th bgcolor="grey">Saturday</th>
            </tr>
            <tr align="center">
                <th bgcolor="lightblue">8-10</th>
                <td >FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>COMMUNICATIVE ENGLISH</td>
                <td>FREE SLOT</td>
                <td>FUNDAMENTALS OF C PROGRAMMING</td>
                <td>FREE SLOT</td>
            </tr>
            <tr align="center">
            <th bgcolor="lightblue">10-12</th>
            <td>COMMUNICATIVE ENGLISH</td>
            <td>FREE SLOT</td>
            <td>FUNDAMENTALS OF WEB APPLICATIONS</td>
            <td>FUNDAMENTALS OF WEB APPLICATIONS</td>
            <td>FUNDAMENTALS OF WEB APPLICATIONS</td>
            <td>FUNDAMENTALS OF WEB APPLICATIONS</td>
            </tr>
            <tr>
                <th bgcolor="lightblue">12-1</th>
                <td colspan="5" align="center">L U N C H</td>
            </tr>
            <tr align="center">
            <th bgcolor="yellow">1-3</th>
            <td>FREE SLOT</td>
            <td>COMMUNICATIVE ENGLISH</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>COMMUNICATIVE ENGLISH</td>
            </tr>
            <tr align="center">
            <th bgcolor="lightblue">3-5</th>
            <td>FUNDAMENTALS OF C PROGRAMMING</td>
            <td>FUNDAMENTALS OF C PROGRAMMING</td>
            <td>FUNDAMENTALS OF C PROGRAMMING</td>
            <td>FUNDAMENTALS OF C PROGRAMMING</td>
            <td>FUNDAMENTALS OF WEB APPLICATIONS</td>
            <td>FREE SLOT</td>
            </tr>
         </table>
         <br>
         <table align="center"  cellspacing="2" cellpadding="4" border="2">
          <tr align="center">
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Code</th>
          </tr>
          <tr> 
          <td align="center">1.</td> 
          <td align="center">19AI414</td>
          <td> Fundamentals of Web Application Development (FWAD)</td>
          </tr>
          <tr> 
          <td align="center">2.</td> 
          <td align="center">19AI302</td>
          <td> Fundamentals of C Programming (C Program)</td>
          </tr>
          <tr> 
          <td align="center">3.</td> 
          <td align="center">19EN101</td>
          <td> Communicative English (CE)</td>
          </tr>
        </table>
    </body>
    </html>
                   

## OUTPUT
![alt text](<screenshot web ex02 slot.png>)
![alt text](<Screenshot 2 web ex02 slot.png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

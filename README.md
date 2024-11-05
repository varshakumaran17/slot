# Ex03 Time Table
## Date: 05-11-2024

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
<!DOCTYPE html>
<html>
<head>
    <title>Slot Timetable</title>
    <style>
        .free-slot {
            background-color: bisque;
        }
    </style>
</head>
<body>
    <center>
        <img src="https://www.saveetha.ac.in/images/WEB_LOGO-01.png" alt="College Logo" height="100" width="540">
    </center>
    <br>
    <table align="center" width="540" cellspacing="2" cellpadding="4" border="4" bgcolor="aqua">
        <caption><b>SLOT TIMETABLE - VARSHA K (212223040177)</b></caption>
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
            <td>Training</td>
            <td>Employment Enrichment Skills</td>
            <td>Training</td>
            <td>Company Specific</td>
            <td>Training</td>
            <td>Fundamentals of Web Application</td>
        </tr>
        <tr align="center">
            <th bgcolor="yellow">10-12</th>
            <td>Training</td>
            <td>Training</td>
            <td>Training</td>
            <td>Fundamentals of Web Application</td>
            <td>Training</td>
            <td>Training</td>
        </tr>
        <tr>
            <th bgcolor="yellow">12-1</th>
            <td colspan="6" align="center">L U N C H   B R E A K</td>
        </tr>
        <tr align="center">
            <th bgcolor="yellow">1-3</th>
            <td>Cyber Law and Compliance</td>
            <td>Software Project Management</td>
            <td>Mentor Meet</td>
            <td>Cyber Law and Compliance</td>
            <td>Training</td>
            <td>Training</td>
        </tr>
        <tr align="center">
            <th bgcolor="yellow">3-5</th>
            <td>Fundamentals of Web Application</td>
            <td class="free-slot">Free</td>
            <td class="free-slot">Free</td>
            <td>Software Project Management</td>
            <td class="free-slot">Free</td>
            <td class="free-slot">Free</td>
        </tr>
    </table>
    <br>
    <table align="center" cellspacing="2" cellpadding="4" border="2">
        <tr align="center">
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr align="center">
            <td>1.</td>
            <td>19EY712</td>
            <td>Employment Enrichment Skills</td>
        </tr>
        <tr align="center">
            <td>2.</td>
            <td>19CS504</td>
            <td>Software Project Management</td>
        </tr>
        <tr align="center">
            <td>3.</td>
            <td>19EY706</td>
            <td>Company Specific</td>
        </tr>
        <tr align="center">
            <td>4.</td>
            <td>19CS418</td>
            <td>Cyber Law and Compliance</td>
        </tr>
        <tr align="center">
            <td>5.</td>
            <td>ECA-M</td>
            <td>Mentor Meet</td>
        </tr>
        <tr align="center">
            <td>6.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application</td>
        </tr>
    </table>
</body>
</html>

```

## OUTPUT

![Screenshot (27)](https://github.com/user-attachments/assets/e8b16c38-3d2e-4ba9-b052-cd1c622c0dac)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

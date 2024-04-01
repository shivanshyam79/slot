# Ex03 Time Table
## Date: 31/03/2024

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
        <title> MY SLOT </title>
    </head>
    <body >
        <center><img src="logo.png" width="700" height="100"> </center> 
    <center>
        <br>
        <CAPTION align="above"><b>SLOT TIMETABLE- SHYAM .R(212223040200)</b></CAPTION><br>
        <table border="5"  width="540"  cellspacing="5" cellpadding="10" >
            <tr align="center"  style="background-color: yellow;">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr align="center" style="background-color:aquamarine;">
                <th>8-10 </th>
                <th></th>
                <th></th>
                <th>CH</th>
                <th></th>
                <th>FWAD</th>
                <th>OS</th>
            </tr>
            <tr style="background-color: chartreuse;">
                <th align="center">10-12 </th>
                <th align="center">BEEE</th>
                <th align="center">FWAD</th>
                <th align="center">PH</th>
                <th align="center"></th>
                <th align="center">C</th>
                <th align="center">ML</th>
            </tr>
            <tr ALIGN="center" style="background-color: cyan;">
                <th>12-1 </th>
                <td colspan="6">LUNCH BREAK</td>
            </tr>
            <tr style="background-color: lawngreen;">
                <th align="center">1-3 </th>
                <th align="center">ML</th>
                <th align="center">CH</th>
                <th align="center">HRM</th>
                <th align="center">BEEE</th>
                <th align="center">HRM</th>
                <th align="center"></th>
            </tr>
            <tr style="background-color:blue;">
                <th align="center">3-5</th>
                <th align="center">C</th>
                <th align="center">PH</th>
                <th align="center">FWAD</th>
                <th align="center">OS</th>
                <th align="center"></th>
                <th align="center"></th>
            </tr>
        </table>
        <br>
        <table border="5"  cellspacing="2" cellpadding="4"  >
           <b><tr >
                <th>S.NO.</th>
                <th>Subject Code</th>
                <th>subject Name</th>
            </tr>
            <tr align="center">
                <th>1</th>
                <th>19AI414</th>
                <th style="color:red">Fundamentals of Web Application Development(FWAD)</th>
            </tr>
            <tr align="center">
                <th>2</th>
                <th>19AI410</th>
                <th style="color:blue">Introduction To Machine Learning(ML)</th>
            </tr>
            <tr align="center">
                <th>3</th>
                <th>19PH214</th>
                <th style="color:green">PHYSICS FOR QUANTUM COMPUTING(PH)</th>
            </tr>
            <tr align="center">
                <th>4</th>
                <th>19CS405</th>
                <th style="color:crimson">Operating System(OS)</th>
            </tr>
            <tr align="center">
                <th>5</th>
                <th>19EE305</th>
                <th style="color:maroon">Basic Electrical,Electronics and Measurement Engineering(BEEE)</th>
            </tr>
            <tr align="center">
                <th>6</th>
                <th>19AI302</th>
                <th style="color:sienna">FUNDAMENTAL OF C PROGRAMMING(C)</th>
            </tr>
            <tr align="center">
                <th>7</th>
                <th>19MS956</th>
                <th style="color:navy">HUMAN RESOURCE(HRM)</th>
            </tr>
            <tr align="center">
                <th>8</th>
                <th>19CY205</th>
                <th style="color:gold">CHEMISTRY(CH)</th>
            </b></tr>

        </table>
    </center>
    </body>
</html>
```

## OUTPUT

![alt text](image.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

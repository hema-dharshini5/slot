# Ex03 Time Table
## Date:30.12.2023

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
        <title>My Schedule</title>
        <style>
            .indextitle{
                background-color: peachpuff;
            }
            .firstrow{
                background-color: rgb(210, 210, 247);
            }
            .secondrow{
                background-color: rgb(210, 210, 247);
            }

            .thirdrow{
                background-color: rgb(210, 210, 247);
            }
            .fourthrow{
                background-color: rgb(210, 210, 247);
            }
            .fifthrow{
                background-color: rgb(210, 210, 247);
            }
            .sixthrow{
                background-color: rgb(210, 210, 247);
            }
        </style>
        </head>
    <body>
        <center>
        <img src="/static/logo.png" width="500px" height="100px" background-color="rgb(210, 210, 247)">
        <table border="6px" cellspacing="2px" cellpading="4px" width="700px" height="300px" >
        <h3 class="subtitle">SLOT TIMETABLE-Hema Dharshini</h3>
            <tr class="indextitle">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
            </tr>
            <tr class="firstrow">
                <td bgcolor="peachpuff">8-10</td>
                <td>Free</td>
                <td>Communicative English</td>
                <td>Free</td>
                <td>Free</td>
                <td>Fundamentals of web application</td>
            </tr>
            <tr class="secondrow">
                <td bgcolor="peachpuff">10-11</td>
                <td>Free</td>
                <td>Calcus matrix and algebra</td>
                <td>Fundamentals of web application</td>
                <td>Free</td>
                <td>Free</td>
            </tr>
            <tr class="thirdrow">
                <td bgcolor="peachpuff">11-12</td>
                <td>Free</td>
                <td>Calcus matrix and algebra</td>
                <td>Fundamentals of web application</td>
                <td>Free</td>
                <td>Physics for quantum computing</td>
            </tr>
            <tr class="fourthrow">
                <td bgcolor="peachpuff">12-1</td>
                <td colspan="5" align="center">LUNCH</td>
            </tr>
            <tr class="fifthrow">
                <td bgcolor="peachpuff">1-3</td>
                <td>Calcus matrix and algebra</td>
                <td>Free</td>
                <td>Free</td>
                <td>Communicative english</td>
                <td>Free</td>
            </tr>
            <tr class="sixthrow">
                <td bgcolor="peachpuff">1-5</td>
                <td>Physics for quantum computing</td>
                <td>Free</td>
                <td>Free</td>
                <td>Fundamentals of web application</td>
                <td>Soft skills</td>
            </tr>
        </table>
        <br>
        <table border="4px" cellspacing="2px" cellpadding="4px">
            <tr>
                <th>s.no</th>
                <th>Subject code</th>
                <th>Subject name</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI414</td>
                <td>Fundamental of web application</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19PH214</td>
                <td>Physics for quantum computing</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19EN101</td>
                <td>Communicative english</td>
            </tr>
            <tr>
                <td>4</td>
                <td>19PH214</td>
                <td>Physics for quantum computing</td>
            </tr>
            <tr>
                <td>5
                </td>
                <td>19MA210</td>
                <td>Calcus matrix and algebra</td>
            </tr>
        </table>
        </center>


    </body>
</html>
```
## OUTPUT


![Screenshot 2023-12-30 053620](https://github.com/hema-dharshini5/slot/assets/147117728/99fc89bf-f7b1-48a3-bbd1-b1a6b1691579)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

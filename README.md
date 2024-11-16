# Ex03 Time Table
## Date:15-11-24

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
<body>
    <img src="logo.png" width="1000px" height="150px" style="margin-left: 250px;">
    <br>
    <br>
    <br>
    <table border="2" cellspacing="10" cellpadding="5" align="center">
        <caption><b>TIME TABLE SHARAN-24010956</b></caption>
        <tr>
            <th>Days</th>
            <th>8-10</th>
            <th>10-12</th>
            <th>12-1</th>
            <th>1-3</th>
            <th>3-5</th>
        </tr>
        <tr>
            <th>MONDAY</th>
            <td style="color:aqua;background-color: black;">FREE SLOT</td>
            <td>MATH</td>
            <th>L</th>
            <td>C PROG</td>
            <td style="color: aqua; background-color: black;">FREE SLOT</td>
        </tr>
        <tr>
            <th>TUESDAY</th>
            <td>WEB</td>
            <td style="color: aqua;background-color: black;">FREE SLOT</td>
            <th>U</th>
            <td>MATH</td>
            <td>DE</td>
        </tr>
        <tr>
            <th>WEDNESDAY</th>
            <td style="color: aqua; background-color: black;">FREE SLOT</td>
            <td>CHE</td>
            <th>N</th>
            <td>MEN MEET</td>
            <td style="color: aqua; background-color: black;">FREE SLOT</td>
        </tr>
        <tr>
            <th>THURSDAY</th>
            <td>HV</td>
            <td>CDS</td>
            <th>C</th>
            <td>DE</td>
            <td style="color: aqua; background-color: black;">FREE SLOT</td>
        </tr>
        <tr>
            <th>FRIDAY</th>
            <td style="color: aqua; background-color: black;">FREE SLOT</td>
            <td>CHE</td>
            <th>H</th>
            <td>WEB</td>
            <td style="color: aqua;background-color: black;">FREE SLOT</td>
        </tr>
        <tr>
            <th>SATURDAY</th>
            <td style="color: aqua; background-color: black;">FREE SLOT</td>
            <td>C PROG</td>
            <td>  -</td>
            <td>WEB</td>
            <td style="color: aqua;background-color: black;">FREE SLOT</td>
        </tr>
    </table>
    <br>
    <table border="2" cellspacing="2" cellpadding="2" align="center">
        <caption><b>COURSE NAME</b></caption>
        <tr >
            <th>S.NO</th>
            <th>COURSE COAD</th>
            <th>COURSE NAME</th>
        </tr>
        <tr>
            <td>1</td>
            <td>19AI304</td>
            <td>FUNDAMENTAL of C PROGRAMMING</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19AI414</td>
            <td>FUNDAMENTAL of WEB APPLICATION</td>
        </tr>
        <tr>
            <td>3</td>
            <td>19CY205</td>
            <td>PRINCIPLES of CHEMISTRY</td>
        </tr>
        <tr>
            <td>4</td>
            <td>19EE404</td>
            <td>DIGITAL ELECTRONICS</td>
        </tr>
        <tr>
            <td>5</td>
            <td>19EY708</td>
            <td>CAREER DEVELOPMENT SKILLS</td>
        </tr>
        <tr>
            <td>6</td>
            <td>19MA201</td>
            <td>CALCULUS AND MATRIX ALGEBRA</td>
        </tr>
        <tr>
            <td>7</td>
            <td>SH7801</td>
            <td>HUMAN VALUES</td>
        </tr>
        <tr>
            <td>8</td>
            <td>ECA-M SCOFT</td>
            <td>MENTOR MEET</td>
        </tr>
    </table>

</body>
</html>
```
## OUTPUT

![alt text](<Screenshot (13).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

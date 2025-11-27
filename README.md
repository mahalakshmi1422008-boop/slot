# Ex02 Time Table
## Date:27/11/25

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```

<html >
<head>
  <title>Slot Time Table</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin: 20px;
    }
    h2 {
      margin-bottom: 5px;
    }
    table {
      border-collapse: separate;
      margin: 20px auto;
      width: 80%;
    }
    th, td {
      font-weight: bold;
      border: 1px solid rgba(0, 0, 0, 0.458);
      padding: 10px;
      text-align: center;
    }
  </style>
</head>
    <img src="./logo.png" alt="Background Image" style="width:600px; margin-bottom:50px;">
    <h2>SLOT TIME TABLE - Mahalakshmi(25018377)</h2>
  
  <table>
    <tr bgcolor="pink">
      <th>Day/Time</th>
      <th>Monday</th>
      <th>Tuesday</th>
      <th>Wednesday</th>
      <th>Thursday</th>
      <th>Friday</th>
      <th>Saturday</th>
    </tr>
    <tr bgcolor="cyan">
      <td bgcolor="pink">8-10</td>
      <td colspan="2">CE</td>
      <td>FWAD</td>
      <td>C PROGRAM</td>
      <td>FREE SLOT</td>
      <td>FWAD</td>
       
     
    </tr>
    <tr bgcolor="cyan">
      <td bgcolor="pink">10-12</td>
      <td colspan="3">FWAD</td>
      <td>C PROGRAM</td>
      <td>FREE SLOT</td>
      <td>CE</td>
    </tr>
    <tr bgcolor="cyan">
      <td bgcolor="pink">12-1</td>
      <td colspan="6" >L U N C H</td>
    </tr>
    <tr bgcolor="cyan">
      <td bgcolor="pink">1-3</td>
      <td >C PROGRAM</td>
      <td >FREE SLOT</td>
      <td >MENTOR</td>
      <td >CE</td>
      <td colspan="2">FREE SLOT</td>
    </tr>
    <tr bgcolor="cyan">
      <td bgcolor="pink">3-5</td>
      <td colspan="2">FREE SLOT</td>
      <td >C PROGRAM</td>
      <td colspan="2">FREE SLOT</td>
      <td>C PROGRAM</td>
    </tr>
  </table>      
      
<table>
    <tr>
      <th>S. No.</th>
      <th>Subject Code</th>
      <th>Subject Name</th>
    </tr>
    <tr>
      <td>1.</td>
      <td>19AI414</td>
      <td>Fundamentals of Web Application Development (FWAD)</td>
    </tr>
    <tr>
      <td>2.</td>
      <td>19EN101</td>
      <td>Communicative English(CE)</td>
    </tr>
    <tr>
      <td>3.</td>
      <td>19AI304</td>
      <td>Fundamentals Of C Programming(C PROGRAM)</td>
    </tr>
     
  </table>
</html>
```


## OUTPUT


![alt text](<Screenshot (34).png>)




## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

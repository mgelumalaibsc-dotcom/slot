# Ex03 Time Table
## Date:

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple ![ *]```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Time Table With Logo</title>
<style>
    body {
        font-family: Arial, sans-serif;
        background: #f6f6f6;
        margin: 0;
        padding: 0;
    }
    .container {
        max-width: 900px;
        background: #fff;
        margin: 30px auto;
        padding: 20px;
        border-radius: 10px;
        box-shadow: 0 0 12px rgba(0,0,0,0.1);
    }
    .header {
        display: flex;
        align-items: center;
        gap: 15px;
        margin-bottom: 20px;
    }
    .header img {
        width: 80px;
        height: 80px;
        object-fit: contain;
    }
    .header h2 {
        margin: 0;
    }
    table {
        width: 100%;
        border-collapse: collapse;
        text-align: center;
        font-size: 15px;
    }
    th, td {
        border: 1px solid #ddd;
        padding: 12px;
    }
    th {
        background: #0078d7;
        color: white;
    }
    tr:nth-child(even) {
        background: #f2f2f2;
    }
</style>
</head>

<body>
<div class="container">

    <!-- LOGO & HEADING -->
    <div class="header">
        <img src="logo.png" alt="Logo"> <!-- Replace logo.png with your image -->
        <h2>Weekly Time Table</h2>
    </div>

    <!-- TIME TABLE -->
    <table>
        <tr>
            <th>Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
        <tr>
            <td>08:30 - 09:30</td>
            <td>Math</td>
            <td>English</td>
            <td>Physics</td>
            <td>Science</td>
            <td>Computer</td>
        </tr>
        <tr>
            <td>09:35 - 10:35</td>
            <td>English</td>
            <td>Math</td>
            <td>Chemistry</td>
            <td>Physics</td>
            <td>PE</td>
        </tr>
        <tr>
            <td>10:40 - 11:40</td>
            <td>Science</td>
            <td>PE</td>
            <td>Math</td>
            <td>Computer</td>
            <td>Biology</td>
        </tr>
        <tr>
            <td>11:45 - 12:45</td>
            <td>Computer</td>
            <td>Science</td>
            <td>English</td>
            <td>Chemistry</td>
            <td>Library</td>
        </tr>
    </table>

</div>
</body>
</html>



## OUTPUT
![alt text](<Screenshot 2025-11-25 180958-1.png>)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag
### STEP 2
Add header row using th tag
### STEP 3
Add your timetable
### STEP 4
Execute the program

# CODE
```
<!DOCTYPE html>
<html>
<head>
    <title>Document</title>
    <style>
        table, th, td {
            border: 1px solid black;
            border-collapse: collapse;
            
        }
    </style>
</head>
<body>

    <div align="center">
        <img src="logo.png" height="100" width="1000" align="center">
    </div>

    <h4 align="center" width="700">SLOT TIME TABLE - NIJEESH NJ (23010565)</h4>
    <table bgcolor="cyan" align="center" height="200">
        <tr bgcolor="Yellow">
            <th width="100">Day/Time</th>
            <th width="100">Monday</th>
            <th width="100">Tuesday</th>
            <th width="100">Wednesday</th>
            <th width="100">Thursday</th>
            <th width="100">Friday</th>
        </tr>
        <tr align="center">
            <td bgcolor="Yellow">8-10</td>
            <td colspan="3">FREE SLOT</td>
            <td>PHY</td>
            <td>CHE</td>
        </tr>
        <tr align="center">
            <td bgcolor="Yellow">10-12</td>
            <td>GER</td>
            <td>FREE SLOT</td>
            <td>FWAD</td>
            <td>FWAD</td>
            <td>PHY</td>
        </tr>
        <tr align="center">
            <td bgcolor="Yellow">12-1</td>
            <td colspan="5">LUNCH</td>
        </tr>
        <tr align="center">
            <td bgcolor="Yellow">1-3</td>
            <td colspan="2">FREE SLOT</td>
            <td>MAT</td>
            <td>MAT</td>
            <td>SS</td>
        </tr>
        <tr align="center">
            <td bgcolor="Yellow">3-5</td>
            <td colspan="2">FREE SLOT</td>
            <td>GER</td>
            <td>CHE</td>
            <td>FWAD</td>
        </tr>
    </table>

    <br>

    <table align="center" height="200">
        <tr align="center">
            <th width="100">S.No.</th>
            <th width="100">Subject Code</th>
            <th width="300">Subject Name</th>
        </tr>
        <tr>
            <td align="center">1.</td>
            <td align="center">19AI414</td>
            <td width="500">Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td align="center">2.</td>
            <td align="center">19EN612</td>
            <td width="500">German Basic (GER)</td>

        </tr>
        <tr >
            <td align="center">3.</td>
            <td align="center">19PH206</td>
            <td>Physics for Information Technology(PHY)</td>
        </tr>
        <tr >
            <td align="center">4.</td>
            <td align="center">19CY205</td>
            <td>Principles of Chemistry in Engineering (CHE)</td>
        </tr>
        <tr>
            <td align="center">5.</td>
            <td  align="center">19MA201</td>
            <td>Calculus and Matrix Algebra (MAT)</td>
        </tr>
        <tr>
            <td  align="center">6.</td>
            <td  align="center">19EY701</td>
            <td>Soft Skills(SS)</td>
        </tr>
    </table>
</body>
</html>
```
# OUPUT
![timetable](https://github.com/Nijeesh-bit/timetable/assets/89188014/f67e7756-8231-4c62-9ff4-f591f1ee16b7)

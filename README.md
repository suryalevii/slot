# Ex03 Time Table
## Date:10/6/25

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
            
<title>Google <div class="Timetable"></div></title>
    <body> 
     <center> 
     <img src="/static/logo.png" height="150" width="800">
     </center>
      <h3 align="center">  SLOT TIME TABLE - STUDENT NAME ( ROLL NO. ) </h3>
        <table align="center" border="5" cellpadding="6" cellspacing="2" bgcolor="cyan">
        <tr>
          <th bgcolor="yellow">Day</th>    
          <th bgcolor="yellow">8-10</th>
          <th bgcolor="yellow">10-12</th>
          <th bgcolor="yellow">12-1</th>
          <th bgcolor="yellow">1-3</th>
          <th bgcolor="yellow">3-5</th>
        </tr>
        <tr>
           <th bgcolor="yellow">MONDAY </th>
           <td>FREE SLOT  </td>
           <td>FREE SLOT    </td>
           <td rowspan="6">L<br>U<br>N<br>C<br>H </td>
           <td>FREE SLOT    </td>
           <td>WEB DEVELOPMENT  </td>
        </tr>
        <tr>
            <th bgcolor="yellow">TUESDAY  </th>
            <td>WEB DEVELOPMENT </td>
            <td>FREE SLOT</td>
            <td>FREE SLOT </td>
            <td>WEB DEVELOPMENT </td>
         </tr> 
         <tr>
            <th bgcolor="yellow">WEDNESDAY </th>
            <td>WEB DEVELOPMENT </td>
            <td>FREE SLOT </td>
            <td>MENTOR    </td>
            <td>PYTHON </td>
         </tr> 
         <tr>
            <th bgcolor="yellow">THURSDAY  </th>
            <td>FREE SLOT </td>
            <td>PYTHON</td>
            <td>FREE SLOT   </td>
            <td>FREE SLOT </td>
         </tr>
          <tr>
            <th bgcolor="yellow">FRIDAY    </th>
            <td>WEB DEVELOPMENT   </td>
            <td>PYTHON    </td>
            <td>PYTHON  </td>
            <td>FREE SLOT </td>
         </tr>
         <tr>
            <th bgcolor="yellow">SATURDAY  </th>
            <td>FREE SLOT</td>
            <td>FREE SLOT  </td>
            <td>FREE SLOT </td>
            <td>FREE SLOT </td>
         </tr>
        </table>
        <br> 
        <table border="5" cellpadding="7" cellspacing="2" align="center">
         <tr>
           <th><h4>S.NO</h4></th>    
           <th><h4>SUBJECT CODE </h4></th>
           <th><h4>SUBJECT NAME </h4></th>
         </tr>
         <tr>
            <th>1.</th>
            <td>4S3-1</td>
            <td>PYTHON PROGRAMMING  </td>
         </tr>
         <tr>
             <th>2.</th>
             <td>4V1-2</td>
             <td>COMMUNICATION ENGLISH  </td>
          </tr> 
          <tr>
             <th>3.</th>
             <td>4I3-1</td>
             <td>INTRODUCTION TO MACHINE LEARNING  </td>
          </tr> 
          <tr>
             <th>4.</th>
             <td>4L1-1</td>
             <td>FUNDAMENDALS OF C PROGRAMMING  </td>
          </tr>
           <tr>
             <th>5.</th>
             <td>4M3-1</td>
             <td>STATISTICS AND NUMERICALS METHODS  </td>
          </tr>
          <tr>
             <th>6.</th>
             <td>6J1-1</td>
             <td>FUNDAMENDALS OF WEB APPLICATION DEVELOPMENT   </td>
          </tr>
         </table>   
    </body>
</html>


## OUTPUT
<img width="1919" height="1079" alt="Screenshot 2025-10-06 165649" src="https://github.com/user-attachments/assets/c9b13847-8ae6-4cbf-ad7e-e0ec7f239eaf" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

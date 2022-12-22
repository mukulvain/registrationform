<!DOCTYPE htnm>
<html lang="en">
<head>

<title>registrationform</title>

</head>
<body>
    <form>
        <table border="1" cellspacing="0"> 
   <tr>
      <th colspan="2"> <h3>Registration Form</h3></th>
   </tr> 
   <tr>
       <th>First Name:</th>
       <th><input type="text" id="fname" name="fname"></th>
   </tr>
   <tr>
    <th>Last Name:</th>
    <th><input type="text" id="lname" name="lname"></th>
   </tr>
   <tr>
    <th>Gender</th>
    <th>
        <ul type="dics">
        <li>Male :<input type="radio" name="My_gender"><br></li>
        <li>Female:<input type="radio" name="My_gender"><br></li>
        <li>other :<input type="radio" name="My_gender"></li>
        </ul>
    </th>
   </tr>
   <tr>
     <th>Date of Birth :</th>
     <th><input type="date" name="dateofbirth" id="date"></th>
   </tr>
   <tr>
   <th>Contact No:<br><br>Email ID:</th>
   <th>
     <input type="number" name="contact no"><br><br>
     <input type="email" name="email address">
   </th>



   </tr>
   <tr>
   <th>Qualification:</th>
       <th>
           <select name="standard " id="standard">
             <option value="select">select</option>
             <option value="B.Tech">B.Tech</option>
             <option value="M.Tech">M.Tech</option>
             <option value="B.SC">B.Sc</option>
             <option value="m.sc">M.Sc</option>
             <option value="Ph.D">Ph.D</option>
        </select>
        </th>
   </tr>
   <tr>
    <th>Semester:</th>
        <th>
            <select name="Semester" id="Semester">
              <option value="select">select</option>
              <option value="1st">1st</option>
              <option value="2nd">2nd</option>
              <option value="3rd">3rd</option>
              <option value="4th">4th</option>
              <option value="5th">5th</option>
              <option value="6th">6th</option>
              <option value="7th">7th</option>
              <option value="8th">8th</option>
         </select>
         </th>
    </tr>
   <tr>
    <th>Address:</th>
    <th>
        <textarea rows="10" cols="60"></textarea>
    </th>
   </tr>
   <tr>
    <th>Upload Your Photo</th>
    <th>
    <form action="/action_page.php">
    </form><input type="file" id="myfile" name="filename">
     <input type="submit">
    <input type="reset">
    </th>
   </tr>
    <tr>
        <th>Above  given information<br> are correct ?<br>(if yes tick this checkbox)</th>
        <th><input type="checkbox" name="all imformation are correct"></th>
    </tr> 
    <tr>

      <th></th>
      <th> <input type="submit" value="submit form"><br>
          <input type="reset" value="Reset form">
          </th>
    </tr>
</form>
</body>



</html>

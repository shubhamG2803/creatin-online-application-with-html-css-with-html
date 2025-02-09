# online application using html,css
HTML CODE
<html>
<head>
    <title>Student Form</title>
    <link rel="stylesheet" href="wt2.css">

    
    <style>
        .center {
                    margin: auto;
                    width: 50%;
                    border: 3px solid white;
                    padding: 10px;
                    color: aquamarine;
                }
                input[name="Gender"] 
                {
	            accent-color: green;
                }

        h1 {text-align: center;}
        .a
        {
           color: brown;
        }
        
    </style>
</head>
<body>
    
    <form>
        <div class="center">
            <h1 style="color:rgb(0, 174, 255);"!important>Form</h1>
    Student Name:
    <input type="text" id="sname" name="Student_Name"><br><br>
    Mobile Number:
    <input type="text" id="mbno" name="Mobile_Number"><br><br>
    
    <div class="a">
        Gender:
        <input type="radio"  name="Gender" id="Male" value="Male"> Male
        <input type="radio" name="Gender" id="Female" value="Female">Female<br><br>
    </div>
   
    
    Class:
    <select name="Class" id="class">
        <option value="First Year">First Year</option>
        <option value="Second Year">Second Year</option>
        <option value="Third Year">Third Year</option>
        <option value="Fourth Year">Fourth Year</option>
    </select><br><br>
    <input type="submit" value="Submit">
    <input type="reset" value="Reset">
</div>
</form>
</body>
</html>

CSS CODE
body{
    background-image: url('https://img.freepik.com/free-vector/overlapping-forms-wallpaper-concept_52683-46442.jpg');
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: 100% 100%;
}
 

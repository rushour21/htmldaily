<!DOCTYPE html>
<html lang="en">
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Job Application Form</title>

        <style>
            body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
            }
            .container {
            max-width: 750px;
            background-color: white;
            padding: 20px;
            margin: 40px auto;
            border-radius: 30px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
            }
            label {
                display: block;
                margin: 15px 0 5px;
            }
            h1{
                text-align: center;
            }
            div{
                margin: 15px 0 5px;
            }
            input[type="text"],
        input[type="email"],
        input[type="tel"],
        input[type="date"],
        input[type="number"],
        input[list="major"],
        select,
        textarea {
            width: 100%;
            padding: 10px;
            margin: 5px 0 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
            box-sizing: border-box;
        }
        input[type="submit"] 
        {
            width: 100%;
            height: 50px;
            border: none;
            font-size: 1.35pc;
            color: white;
            background-color: deepskyblue;
            border-radius: 30px;
        }
        </style>
    </head>
    <body>
        <div class="container">
        <h1>Job Application Form</h1>
        <form>
            <label for="first name">First Name</label>
            <input type="text" id="first name" name="First Name" placeholder="First Name" required>
            <label for="last name">Last Name</label>
            <input type="text" id="last name" name="Last Name" placeholder="Last Name " required>
            <label for="email">Email</label> 
            <input type="email"  id="email" name="Email" placeholder="Enter Email" required>
            <label for="phone">Phone Number</label> 
            <input type="tel" minlength="10" maxlength="10" id="phone" name="Phone" required>
            <label for="education">Highest Level of Education:</label>
        <select id="education" list="education" name="Education" required>
            <option value="" disabled selected>Select your education level</option>
            <option value="high_school">High School</option>
            <option value="bachelor">Bachelor's Degree</option>
            <option value="master">Master's Degree</option>
            <option value="phd">PhD</option>
        </select>
        <label for="institute">Institute Name</label>
        <input type="text" id="institute" name="Institute" placeholder="Add your Institute" required>
        <label for="major">Major</label>
        <input list="major" name="Major" >
       <datalist id="major">
         <option value="Computer Science">
         <option value="Information technology">
         <option value="Electronics">
         <option value="Mechanical">
         <option value="Chemical">
         <option value="Electrical">
         <option value="Civil">
       </datalist>
       <label for="DOB">Date of Birth</label>
        <input type="date" id="DOB" name="DOB" required>
        <label for="experience">Experience</label>
        <input type="number" max="20" min="0" id="experience" name="Experience">
        <label for="resume">Upload Resume</label>
        <input type="file" id="resume" name="Resume">
        <label for="">Select Your Gender: </label> 
        <input type="radio" name="gender" value="M">Male
        <input type="radio" name="gender" value="F">Female
        <input type="radio" name="gender" value="O">Other


        <label for="msg">Message For HR: </label>
        <textarea name="Message" id="msg" rows="10" cols="50"></textarea>

        <div class="t&c">
            <input type="checkbox" name="T&C" id="t&c" required>
            <label for="t&c">I agree to term and codition <P>Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis, delectus debitis qui culpa necessitatibus cum hic sit eius veniam assumenda sed. Autem architecto cumque dolor nulla ipsum excepturi inventore doloremque.</P></label>
            </div>

            <br><br> <input type="submit" value="Next">
        
        </form>
    </div>
    </body>
</html>
    

# form

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form</title>
</head>
<style>
    label {
        display: inline-block;
        width: 150px;
    }
</style>

<body style="background-color: aquamarine;">
    <h1 style="text-align: center;">Student Registation Form</h1>
    <form action="https://formspree.io/f/xbdzodaz" method="POST">
        <table>
            <tr>
                <td>
                    <label for="Reg. No.">Reg. No. :</label>
                    <input type="tel" name="Reg. No." placeholder="Enter Your Reg. No." maxlength="11">

                </td>
            </tr>
            <tr>
                <td>
                    <label for="Name">Student Name :</label>
                    <input type="text" name="Student Name" placeholder="First Name">
                    <input type="text" name="Student Name" placeholder="Last Name">
                </td>
            </tr>
            <tr>
                <td>
                    <label for="name">Father's Name :</label>
                    <input type="text" name="Father's Name" placeholder="Enter Your Father's Name">
                </td>
            </tr>
            <tr>
                <td>
                    <label for="DOB">Date Of Birth :</label>
                    <input type="date" name="DOB">
                </td>
            </tr>
            <tr>
                <td>
                    <label for="MOB">Mobile No. :</label>
                    <input type="tel" name="MOB" maxlength="10">
                </td>
            </tr>
            <tr>
                <td>
                    <label for="email">Email Id :</label>
                    <input type="email" name="Email">
                </td>
            </tr>
            <tr>
                <td>
                    <label for="password">Password :</label>
                    <input type="password" name="Password">
                </td>
            </tr>
            <tr>
                <td>
                    <label for="text">Gender :</label>
                    <input type="radio" id="Male" name="Gender" value="Male">
                    <label for="male">Male</label>
                    <input type="radio" id="Female" name="Gender" value="Female">
                    <label for="radio">Female</label>
                </td>
            </tr>
            <tr>
                <td>
                    <label for="text">Department :</label>
                    <input type="checkbox" name="CSE" value="CSE">
                    <label for="text">CSE</label>
                    <input type="checkbox" name="AIML" value="AIML">
                    <label for="text">AIML</label>
                    <input type="checkbox" name="EEE" value="EEE">
                    <label for="text">EEE</label>
                    <input type="checkbox" name="Mechanical" value="Mechanical">
                    <label for="text">Mechanical</label>
                    <input type="checkbox" name="Civil" value="Civil">
                    <label for="text">Civil</label>
                    <input type="checkbox" name="CWCA" value="CWCA">
                    <label for="text">CWCA</label>
                </td>
            </tr>
            <tr>
                <td>
                    <label for="text">Course :</label>
                    <select name="course" id="courses">
                        <option value="none">Select Courses</option>
                        <option value="B.Tech">B.Tech</option>
                        <option value="B.E">B.E</option>
                        <option value="B.sc">B.sc</option>
                        <option value="B.Arch">B.Arch</option>
                    </select>
                </td>
            </tr>
            <tr>
                <td>
                    <label for="text">City :</label>
                    <input type="city" name="City" placeholder="Enter your city">
                </td>
            </tr>
            <tr>
                <td>
                    <label for="text">Address</label>
                    <input type="Address" name="Adderess" placeholder="Enter Your Full Address">
                </td>
            </tr>
            <tr>
                <td align="center">
                    <input type="Submit" width="200px" name="Register">
                </td>
            </tr>
        </table>

    </form>
</body>

</html>

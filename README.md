#html form
<html>
<head>
    <style>
    form{
        background-color: rgb(214, 135, 17);
        text-align: center;
        justify-content: center;
        width: 30%;
        height: auto;
        display: flex;
        border-radius: 32px 64px;
        border: 8px inset black;
    }
    </style>
</head>
<center>
<u>
<b>
<font size="5">
Registration Form
</font>
</b>
</u>
<br><br>
Student Deatails
 
<body bgcolor="lawngreen">
<bgcolor="yellow">
<form> <table>
                <tr>
                        <th>Name:</th>
                        <td><input type="text" placeholder="NAME"></td>
                    </tr>
                    <tr>
                        <th>DOB:</th><td><input type="date" placeholder="DOB"></td>
                  </tr>
                  <tr>
                      <th>Gender:</th> 
                      	<td>male<input type="radio" name="radio" value=" ">
                        Female<input type="radio" name="radio" value=" ">
                        Other<input type="radio" name="radio" value=" "></td>

                    </tr>
                    <tr>
                    <th>State:</th>
                    <td><input type="state" placeholder="STATE"></td>
                    </tr>
                    <tr>
                       <th>Week:</th><td><input type="week"></td>
                       </tr>
                     <tr>
                     <th>color:</th>
                     <td><input type="color"></td>
                     </tr>

                    <tr>
                        <th>E-Mail:</th>
                        <td><input type="email" placeholder="Email@"></td>
                   </tr>
                    <tr>
                        <th>Password:</th>
                        <td><input type="password" placeholder="Password" ></td>
                        </tr>
                     <tr>
                       	<td><input type="reset"></td>
                        <td><input type="submit"></td>
                    </tr>
            </table>
</form>
</body>
</html>

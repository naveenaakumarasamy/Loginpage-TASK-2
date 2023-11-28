# Loginpage-TASK-2

## Create a login page for a website or app complete with input validation and password hashing.

## code:

### index.html:
```
 <html>
 <head>
  <title>
      navenaa
  </title>
  <link rel ="stylesheet" type ="text/css" href ="myil.css">
 </head>
 <body>
	
		
		
	
	<div id ="container">		
		<h1>Sign in</h1>
		<div id = "rytbx"></div>  
		<fieldset id="userlog">
			<legend>User Login</legend>
			<form>
				<table id="User_table" >
					<tr>
						<td>User Name</td>
						<td><input type="text"></td>
					
					</tr>
					<tr>
						<td>Password</td>
						<td><input type="password"></td>
					
					</tr>
					<tr>
						<td><input type="Submit" id="sb" value="Login"></td>
						<td><input type="Reset" id="rb" value="Clear"></td>
					
					</tr>
					<tr>
						<td><a href="#">Forget Password?</a></td>
						<td><a href="new.php">New User Registration</a></td>
					
					</tr>

				</table>
			</form>
		</fieldset>		
	</div>
   	
 </body>
</html>
```
### myil.css
```
*{
margin : 0px;
padding : 0px;
}
html{
background : silver;
}
body{
background : #176E7A;
height : 90px;
width : 800px;
margin : 10px auto;
}
#container{
background :#ADB1FF;
height : 640px;
width : 100%;
}
h1{
color:#2D8581;
text-align:center;
padding-top:25px;
font-family:Sitka Small Semibold;
font-size : 50px;
}
#userlog{
min-height:200px;
width:600px;
margin-left:100px;
margin-top:25px;
border-radius:5px;
border:1px solid #5F1666;
}
#userlog legend{
margin-left:30px;
font-size:30px;
color:#515378;
}
#User_table{
margin:40px;
font-size:20px;
}
#User_table tr td{
padding-top:7px;
padding-left:8px;
}
#User_table a{
color:#7C2D8C;
text-decoration:none;
}
#User_table a:hover{
color:#47F6FF;
text-decoration:underline;
}
#User_table input[type="text"],#User_table input[type="password"],select,#User_table input[type="email"]	{
width:180px;
height:30px;
border-radius:5px;
font-size=30px;
color:#BA2364;
}
#User_table input[type="Submit"],#User_table input[type="Reset"]{
width:100px;
height:30px;
border-radius:5px;
font-size=30px;
color:#BA2364;
}
#sb{
background:#B5B5B5;
border:3px solid #3A0603;
}
#rb{
background:#FF7390;
border:3px solid #3A0603;
}
#sb:hover{
background:#808080;
border:3px solid #3A0603;
}
#rb:hover{
background:#C4596F;
border:3px solid #3A0603;
}
```
### new.html

```
<html>
 <head>
  <title>
      navenaa
  </title>
  <link rel ="stylesheet" type ="text/css" href ="myil.css" >
 </head>
 <body>

	<div id ="container">		
		<h1>New User Registration</h1>
		<div id = "rytbx"></div>  
		<fieldset id="userlog">
			<legend>New User </legend>
			<form>
				<table id="User_table" >
					<tr>
						<td>Name </td>
						<td><input type="text" required></td>
					
					</tr>
					<tr>
						<td>User Name</td>
						<td><input type="text" required></td>
					
					</tr>
				        <tr>
						<td>Email id</td>
						<td><input type="email" required></td>
					
					</tr>
					<tr>
						<td>Password</td>
						<td><input type="password" required></td>
					
					</tr>
					<tr>
						<td>Confirm Password</td>
						<td><input type="password" required></td>
					
					</tr>
					<tr>
						<td>Security Question</td>
						<td>
							<select>
								<option>What is your pet name ?</option>
								<option>What is your favourite food ?</option>
								<option>What is your favourite fruite ?</option>
							<select>
						</td>
					
					</tr>
					<tr>
						<td>Your Answer</td>
						<td><input type="text" required></td>
					</tr>
					<tr>
						<td><input type="Submit" id="sb" value="Save"></td>
						<td><input type="Reset" id="rb" value="Clear"></td>
					
					</tr>
					<tr>
						<td><a href="index.php">Already a User ?</a></td>
					
					</tr>

				</table>
			</form>
		</fieldset>		
	</div>
 </body>
</html>
```
## Output:

![image](https://github.com/naveenaakumarasamy/Loginpage-TASK-2/assets/113497406/416a7ae1-8cc5-4ed2-b48b-895d0b605536)

![image](https://github.com/naveenaakumarasamy/Loginpage-TASK-2/assets/113497406/f919c638-43b7-4c76-878b-98dd8d17acfd)

![image](https://github.com/naveenaakumarasamy/Loginpage-TASK-2/assets/113497406/f30c9acc-8b3e-48b4-8a1a-f2fe5958dc8c)

![image](https://github.com/naveenaakumarasamy/Loginpage-TASK-2/assets/113497406/53f594d7-7dca-4b6d-85ef-0ebe6cf343e1)

![image](https://github.com/naveenaakumarasamy/Loginpage-TASK-2/assets/113497406/de5814aa-7bf9-44c9-8a8a-f6fdbccb9db8)

![image](https://github.com/naveenaakumarasamy/Loginpage-TASK-2/assets/113497406/3e8ace06-80fe-4e01-ad62-562a26c8de1c)

![image](https://github.com/naveenaakumarasamy/Loginpage-TASK-2/assets/113497406/6f29fec3-a403-438e-83e4-0cf17c693609)

![image](https://github.com/naveenaakumarasamy/Loginpage-TASK-2/assets/113497406/270e99c0-31aa-4ffe-9a2a-c594aefe8374)




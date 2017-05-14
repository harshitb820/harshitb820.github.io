# harshitb820.github.io
<!DOCTYPE html>
<html>
<style>

form {
    border: 3px solid #f1f1f1;
}

body{

    background-color:  #f7d06e;
}

input[type=text], input[type=password] {
    width: 100%;
    padding: 12px 20px;
    margin: 8px 0;
    display: inline-block;
    border: 1px solid #ccc;
    box-sizing: border-box;
}

button {
    background-color: #4CAF50;
    color: white;
    padding: 14px 20px;
    margin: 8px 0;
    border: none;
    cursor: pointer;
    width: 100%;
}

button:hover {
    opacity: 0.8;
}

.cancelbtn {
    width: auto;
    padding: 10px 18px;
    background-color: #f44336;
}

.imgcontainer {
    text-align: center;
    margin: 24px 0 12px 0;
    background-color: #f2b926;
}

.new{

    style="color:#f5c13d";
}

img.avatar {
    width: 40%;
    border-radius: 50%;
}

.container {
    padding: 16px;
    background-color: #f4c857;
}

span.psw {
    float: right;
    padding-top: 16px;
}

@media screen and (max-width: 300px) {
    span.psw {
       display: block;
       float: none;
    }
    .cancelbtn {
       width: 100%;
    }
}
</style>

<head>
<title> Login </title>
</head>

<body >

<div class="new">
<h2><em>LOGIN</em></h2>
</div>
<form action="/action_page.php">
  <div class="imgcontainer">
    <img src="http://geniusbeauty.com/wp-content/uploads/2008/09/1222274863huqpvl1.jpg" alt="Avatar" class="avatar">
  </div>

  <div class="container">
    <label><b>Username</b></label>
    <input type="text" placeholder="Enter your Username" name="uname" required>

    <label><b>Password</b></label>
    <input type="password" placeholder="Enter the Password" name="psw" required>
        
    <button type="submit">Login</button>
    <input type="checkbox" checked="checked"> Remember me
    
    <br />
    <br />
    <br />
    <a href="sign_up.html"><em>You Are New Here( Don't Have An Account)!!</em> </a>  
  </div>

  <div class="container" style="background-color:#f1f1f1">
    <button type="button" class="cancelbtn">Cancel</button>
    <span class="psw">Forgot <a href="#">password?</a></span>
  </div>
</form>

</body>
</html>

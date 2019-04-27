<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Form Styling</title>
    <link
      href="https://fonts.googleapis.com/css?family=Raleway"
      rel="stylesheet"
    />
    <style>
      * {

        /* 
        -May want to add "border-box for "box-sizing so padding does not affect width
        -Reset margin and padding 
       */
       box-sizing:border-box;
       margin:0;
       padding:0;
      }

      body {
        font-family:'Raleway',san-self;
        
        Background-color:#344a72;
        color:#fff;
        line-height:1.8;
        
      }

      a {
       
       text-decoration:none;
      }

      #container {
       
        max-width:400px;
        margin:30px auto;
        padding:20pax;

   
        
      }

      .form-wrap {
       
        background:white;
        padding:15px 25px;
        color:#333;
        border-radius:20px;

      }

      .form-wrap h1,
      .form-wrap p {

        text-align:center;
       
      }

      .form-wrap .form-group {
        margin-top:15px;


       
      }

      .form-wrap .form-group label {
        display:block;
        color:#666;

        
      }

      .form-wrap .form-group input {
        width:100%;
        padding:10px;
        border:#ddd 1px solid;
        border-radius:5px;

       
      }

      .form-wrap button {
        display: block;
        background:#49c1a2;
        width:100%
        
      }

      .form-wrap button:hover {
        background:#37a08e;


       
      }

      .form-wrap .bottom-text {
        font-size:13px;
        margin-top:20px;
        
      }

      .btn{
        height:50px;
        border-radius:10px;
        margin-top:50px;
        font-size:26px;
        color:white;

      }

      footer {
        text-align:center;
        margin-top:10px;
       
      }

      footer a {
       color:#49c1a2;
      }
    </style>
  </head>
  <body>
    <div id="container">
      <div class="form-wrap">
        <h1>Sign Up</h1>
        <p>It's free and only takes a minute</p>
        <form>
          <div class="form-group">
            <label for="first-name">First Name</label><br>
            <input type="text" name="firstName" id="first-name" />
          </div>
          <div class="form-group">
            <label for="last-name">Last Name</label><br>
            <input type="text" name="lastName" id="last-name" />
          </div>
          <div class="form-group">
            <label for="email">Email</label><br>
            <input type="email" name="email" id="email" />
          </div>
          <div class="form-group">
            <label for="password">Password</label><br>
            <input type="password" name="password" id="password" />
          </div>
          <div class="form-group">
            <label for="password2">Confirm Password</label><br>
            <input type="password" name="pasword2" id="password2" />
          </div>
          <button type="submit" class="btn">Sign Up</button>
          <p class="bottom-text">
            By clicking the Sign Up button, you agree  to our
            <a href="#">Terms & Conditions</a> and
            <a href="#">Privacy Policy</a>
          </p>
        </form>
      </div>
      <footer>
        <p>Already have an account? <a href="#">Login Here</a></p>
      </footer>
    </div>
  </body>
</html>

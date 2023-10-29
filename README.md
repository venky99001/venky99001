<!DOCTYPE html>   
<html>   
<head>  
<meta name="viewport" content="width=device-width, initial-scale=1">  
<title>AJ Tele-Health</title>  
<style>   
Body {  
  font-family: italic, Helvetica, sans-serif;  

  background-image: url(https://wallpaperaccess.com/full/960602.jpg);
  background-repeat: no-repeat;
  background-size: 100%;
}  
button {   

    
       background-color: #f6610a;   
       width: 50;  
        color: rgb(4, 255, 0);   
        padding: 10px;   
        margin: 1px 0px;   
        border: none;   
        cursor: pointer;   
         }   
 form {  
      border: 3px solid #f1f1f1;  
        width:50%;
        
    }   
 input[type=text], input[type=password] {   
        width: 50%;   
        margin: 8px 0;  
        padding: 12px 20px;   
        display: inline-block;   
        border: 2px solid green;   
        box-sizing: border-box;   
    }  
 button:hover {   
        opacity: 0.7;   
    }   
  .cancelbtn {   
        width: auto;   
        padding: 10px 18px;  
        margin: 10px 5px;  
    }   
        
     
 .container {   
        padding: 10px;   
  
    }   
</style>   
</head>    
<body>    
    <center><b> <h1>AJ Tele-Health</h1></b>  
    <form>  
        <div class="container">   
           <br> <label>Username : </label>   
            <input type="text" placeholder="Enter Username" name="username" required></br>
            <br><label>Password : </label>   
            <input type="password" placeholder="Enter Password" name="password" required ></br>  
            <button type="submit">Login</button>   
            <input type="checkbox" checked="checked"> Remember me   
            <button type="button" class="cancelbtn"> Cancel</button>   
            Forgot <a href="#"> password? </a>   </center>
        </div>   
    </form>     
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Babhanbara fitness</title>
</head> 

<link href="https://fonts.googleapis.com/css2?family=Baloo+2&family=Roboto+Mono:wght@100&display=swap" rel="stylesheet">
<link rel="stylesheet" href="">
<Style>
    body{
        color: white;
        margin: 0px;
        padding: 0px;
        background:url(photo.jpg.jpg);
       background-size: 1000px;
    }
    .left{
        position: absolute;
        left: 34px;
        top: 22px;
      width:67px ;
        display:block;
 <!-- border:2px solid green; -->
    }
    .left img{
        width: 70px;
        filter:invert(100%)
    }
    .left div{
        text-align: center;
        fontt-size: 26px;
        <!-- border: 2px solid green; -->
    }
    .mid{
        display: block;
        width: 37%;
        margin: 20px auto;
 <!-- border: 2px solid red; -->
    }
    .right{
        
        position: absolute;
        right: -226px;
        top: 23px;
        display: inline block;
        width:37% ;
    padding: 11px 22px;
    
  <!-- border: 2px solid rgb(69, 194, 41);  -->
    }
  .right:hover{
      
        text-emphasis-color: rgb(33, 194, 41);
    } -->

    .btn{
    
        margin: 105px 174px;
        background-color: rgb(191, 135, 52);
        color: white;
        padding: 11px 133px;
        border: 5px solid rgb(17, 17, 18);
        border-radius: 26px;
        font-size: 13px;
        cursor: pointer;
      }
    
    .call:hover{
        background-color: rgb(207, 207, 222) ;
        text-emphasis-color: red;
    }
    .navbar{
        display: inline-block;

    }
.navbar li{
    display: inline-block;
    font-size: 17px;
}
.navbar li a{
    color: white;
    text-decoration: none;
    padding: 0px 28px;
   
}
.navbar li a:hover,.navbar li a.active{
    text-decoration: underline;
   color: goldenrod;
}
.container{
    border: 2px solid rgb(214, 210, 219);
    margin: 130px 22px;
    padding: 2px 15px;
    border-radius: 11px;
    width: 31%;
  }

.form-group input{
    font-family: 'baloo bhai',cursive;
display: block;
text-align: center;
margin: 100px,auto;
padding: -19px;
width: 390px;
font-size: 25px;
border: -14px solid red;
border-radius: 46px;
}
.container h1{
    text-align: center;
}
.container button{
    display: block;
    width: 23%;
    margin: 20px auto;
}
</Style>
<body>
    <header class="header">
    <!-- left box for logo -->
    <div class="left">
      <img src="Screenshothtml.png" alt="">
      <div>Babhanbara fitness</div>
    </div>
    <div class="mid">
        <ul class="navbar">
            <li> <a href="#" class="active">Home</a></li>
            <li> <a href="#">about</a></li>
            <li> <a href="#"> center</a></li>
            <li> <a href="#">contact us</a></li>
 
         </ul>
    </div>
    <div class="right"> 
        <button class="call">call us</button>
        <button class="call"> Email us</button>
    </div>
</header>
    <div class="container">
    <h1>join the best gym in bihar</h1>
    <form action="noaction.php">
        <div class="form-group">
            <input type="text" name="" placeholder="enter your Name">
        </div>
        <div class="form-group">
            <input type="text" name="" placeholder="enter your Age">
        </div>
        <div class="form-group">
            <input type="text" name="" placeholder="enter your Gender">
        </div>
        <div class="form-group">
            <input type="text" name="" placeholder="enter your address">
        </div>
        <div class="form-group">
            <input type="text" name="" placeholder="enter your mobile no.">
        </div>
        <button class="btn">submit</button>
    </div>
    </form>
</body>
</html>

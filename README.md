# Ex.07 Software Product Company Website
## Date:16/12/2023

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="stylee.css">
    <title>ACCENTURE</title>
   
<link rel='stylesheet' href='https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css'>
</head>
<body>
    <header>
        <div class="main">
            <ul>
                <li><a href="index.html">HOME</a></li>
                <li><a href="people.html">PEOPLE</a></li>
                <li><a href="services.html">SERVICES</a></li>
                <li><a href="contact.html">CONTACT</a></li>
            </ul>
        </div>
        <div class="search" >
            <input class="srch" type="search" name="" placeholder="type to search">
            <a href="#"><button class="btn">Search</button></a>
        </div>
        <div class="logo">
            <img src="logo.png" alt="" width="200px" height="200px">
        </div>
        <div class="title">
            <h1><b>Put generative AI<br> to work for your business.!</b></h1>
        </div>
        <div class="button">
            <button type="button">Join Us</button>
        </div>
        <div class="form">
            <h2>Login Here</h2>
            <input type="email" name="email" placeholder="Enter Your Mail ID">
            <input type="password" name=" " placeholder="Enter Your password">
            <button class="btnn"><a href="#">Login</a></button>
            <p class="Link">Don't have an account<br>
            <a href="#">Sign Up</a> Here</p>
            <p class="liw">Login with email</p>
        
        <div class="wrapper">
            <a href="#" class="icon facebook">
              <div class="tooltip">Facebook</div>
              <span><i class="fab fa-facebook-f"></i></span>
            </a>
            <a href="#" class="icon twitter">
              <div class="tooltip">Twitter</div>
              <span><i class="fab fa-twitter"></i></span>
            </a>
            <a href="#" class="icon instagram">
              <div class="tooltip">Instagram</div>
              <span><i class="fab fa-instagram"></i></span>
            </a>
            <a href="#" class="icon github">
              <div class="tooltip">Github</div>
              <span><i class="fab fa-github"></i></span>
            </a>
            <a href="#" class="icon youtube">
              <div class="tooltip">Youtube</div>
              <span><i class="fab fa-youtube"></i></span>
            </a>
          </div>
          </div>

        <div class="t">
            <h1><b>“Technology will never replace great <br>teachers but technology in the hands of<br> great teachers is transformational.”</b></h1>
        </div>
       
</body>
</html>

services.html
<html>
  <head>
    <title>services</title>
    
    <style>
                body{
                background: linear-gradient(rgb(0, 0, 0) , rgb(31, 5, 110) );
                }
                
            ul{
                float: right;
                list-style-type: none;
                margin-top: 20px;
                min-height: 10%;
                margin-right: 60px;
                font-size: 17px;
            }
            ul li{
                display: inline-block;
            }
            ul li a{
                text-decoration: double;
                color: #ffffff;
                padding: 5px 50px;
                border: 1px solid transparent;
                transition: 0.5 ease;
                font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
                font-size: larger;
            }

            ul li a:hover{
                background-color: black;
                color: #fff;
            }
            .search{
                width: 330px;
                float:right;
                margin-right: 20px;
            }
            .srch{
                font-family: 'Times New Roman';
                width: 200px;
                height: 40px;
                background: transparent;
                border: 1px solid #fff;
                margin-top: 13px;
                color: black;
                border-right: none;
                font-size: 16px;
                float: left;
                padding: 10px;
                border-bottom-left-radius: 5px;
                border-top-left-radius: 5px;

            }
            .btn{
                width: 100px;
                height: 40px;
                background: #fff;
                border: 2px solid#ffffff;
                margin-top: 13px;
                color:black;
                font-size: 15px;
                border-bottom-right-radius: 5px;
                
            }
            .btn:focus{
                outline: none;
            }
            .srch:focus{
                outline: none;

            }

footer {
    background-color: #faf7f7;
    color: #040303;
    text-align: center;

    }
   
footer p{
  padding: 0px;
}  
.im{
margin: 35px;
margin-left: 200px;
}
.h1{
    font-size: medium;
    font-family: Arial, Helvetica, sans-serif;
    color: #fff;
    padding: 30px;
    margin-right: 20%;
}

    </style>
  </head>
<body>
  <header>
    <div class="main">
        <ul>
            <li><a href="index.html">HOME</a></li>
            <li><a href="people.html">PEOPLE</a></li>
            <li><a href="services.html">SERVICES</a></li>
            <li><a href="contact.html">CONTACT</a></li>
        </ul>
    </div>
    
    <div class="search" >
        <input class="srch" type="search" name="" placeholder="type to search">
        <a href="#"><button class="btn">Search</button></a>
    </div>
   <div class="h1">
    <h1> SERVICES GOING ON BY ACCENTURES>!</h1>
    </div>
    <div class="im">
<img src="products.jpg" alt="" width="1000px" height="450px">
</div>
  <footer>
    <p>Designed And Developed By: P HEMA LOKITHA &copy;2023</p>
</footer>

</body>
</html>

people.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
            body{
      background: linear-gradient(rgb(0, 0, 0) , rgb(31, 5, 110) );
    }
    
ul{
    float: right;
    list-style-type: none;
    margin-top: 20px;
    min-height: 10%;
    margin-right: 60px;
    font-size: 17px;
}
ul li{
    display: inline-block;
}
ul li a{
    text-decoration: double;
    color: #ffffff;
    padding: 5px 50px;
    border: 1px solid transparent;
    transition: 0.5 ease;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-size: larger;
}

ul li a:hover{
    background-color: black;
    color: #fff;
}
.search{
    width: 330px;
    float:right;
    margin-right: 20px;
}
.srch{
    font-family: 'Times New Roman';
    width: 200px;
    height: 40px;
    background: transparent;
    border: 1px solid #fff;
    margin-top: 13px;
    color: black;
    border-right: none;
    font-size: 16px;
    float: left;
    padding: 10px;
    border-bottom-left-radius: 5px;
    border-top-left-radius: 5px;

}
.btn{
    width: 100px;
    height: 40px;
    background: #fff;
    border: 2px solid#ffffff;
    margin-top: 13px;
    color:black;
    font-size: 15px;
    border-bottom-right-radius: 5px;
    
}
.btn:focus{
    outline: none;
}
.srch:focus{
    outline: none;

}
      
        footer{

        background-color:black;
        height:30px;
        bottom:0;
        width:100%;
        color:white;
        position:absolute;
        
        }
        header
        {
        background-color:darkblue;
        height:10vh;
        width:100%;
        color:white;
        }
        header h2{
        position:absolute;
        color:white;
        margin-top:10px;
        margin-left:10px;
        }
        .search input{
            width:18%;
            height: 30px;

        }
        .search button{
            color:white;
            background-color: rgb(2, 3, 4);
            padding: 5px;
            text-align: center;
        }
        .search input,button{
            position: absolute;
            right: 880px;
            font-size: 18px;
            border-color:silver;
        }
        .small
        {
           width:200px;
           height:200px;
           margin:10px;
        }
        .border{
        border-width:5px;
        border-color:lightblue;
        border-style:solid;
        border-radius:50%;
        }
        .cirpic{
            position:absolute;
            top:35%;
            margin-left: 40px;
            padding: 0px;
            
        }
        .text{
           position: absolute;
            top:55%;
            margin-left: 20px;
            font-size: 16px;
            
        }
        .text2{
            position:absolute;
            top:61%;
            margin-left:58px;
        }
    
    </style>
</head>
<body>
    <header>
        <div class="main">
        
        <ul>
        <li><a href="contact.html">CONTACT</a></li>
        <li><a href="services.html">SERVICES</a></li>
        <li><a href="people.html">PEOPLE</a></li>
        <li><a href="index.html">HOME</a></li>
        </ul>
    </div>
    <div class="search" >
        <input class="srch" type="search" name="" placeholder="type to search">
        <a href="#"><button class="btn">Search</button></a>
    </div>
        <div class="cirpic">
            <img class="small border" src="photo.jpg" width="400px">
            <img class="small border" src="jaddu.jpeg" width="400px" >
            <img class="small border" src="OIP.jpg" width="400px">
            <img class="small border" src="harry.jpeg" width="400px" >
            <img class="small border" src="eilish.jpeg" width="400px">
            <img class="small border" src="alan.jpeg" width="400px" >
        </div>
        <div class ="text">
            <table cellpadding="87">
                <tr div class="head">
                    <th>LOKITHA</th>
                    <th>JADEJA</th>
                    <th>TAYLOR</th>
                    <th>HARRY</th>
                    <th>ELLISH</th>
                    <th>ALAN</th>
                </tr>
            </table>
        </div>
        <div class="text2">
            <table cellpadding="83">
                <tr>
                    <td>CEO</td>
                    <td>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CEO<br>Co-Founder</td>
                    <td>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CTO<br>Co-Founder</td>
                    <td>Director</td>
                    <td>Asst.Director</td>
                    <td>Dy.Director</td>
                </tr>
            </table>
        </div>
    
            <footer>
                Designed and Developed by HEMA LOKITHA P&copy; 2023
                </footer>
               
</body>
</html>

contact.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1{
        color: blue;
        font-size: 45px;
        font-family:Georgia, 'Times New Roman', Times, serif;
        position: absolute;
        top:35%;
        }
        body{
        background-color:silver;
        margin:0;
        }
        .navbar ul{
        list-style-type:none;
        background-color:darkblue;
        
        }
        .navbar a{
         color:white;
        text-decoration:none;
        padding:25px;
        display:flex;
        text-align:left;
        position: relative;
        font-size:20px;
        top:-95px;
        
        }
        .navbar a:hover{
         background-color:lightblue;
        size:60px;
        cursor: pointer;
        }
        .navbar li{
        float:right;
        }
        h2{
        color:white;
        font-family:monospace;
        font-size:60px;
        background-color:darkblue;
        }
        footer{

        background-color:black;
        height:30px;
        bottom:0;
        width:100%;
        color:white;
        position:absolute;
        
        }
        body{
      background: linear-gradient(rgb(67, 9, 70) , rgb(23, 23, 24) );
    }
    
ul{
    float: right;
    list-style-type: none;
    margin-top: 20px;
    min-height: 10%;
    margin-right: 60px;
    font-size: 17px;
}
ul li{
    display: inline-block;
}
ul li a{
    text-decoration: double;
    color: #ffffff;
    padding: 5px 50px;
    border: 1px solid transparent;
    transition: 0.5 ease;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-size: larger;
}

ul li a:hover{
    background-color: black;
    color: #fff;
}
.search{
    width: 330px;
    float:right;
    margin-right: 20px;
}
.srch{
    font-family: 'Times New Roman';
    width: 200px;
    height: 40px;
    background: transparent;
    border: 1px solid #fff;
    margin-top: 13px;
    color: black;
    border-right: none;
    font-size: 16px;
    float: left;
    padding: 10px;
    border-bottom-left-radius: 5px;
    border-top-left-radius: 5px;

}
.btn{
    width: 100px;
    height: 40px;
    background: #fff;
    border: 2px solid#ffffff;
    margin-top: 13px;
    color:black;
    font-size: 15px;
    border-bottom-right-radius: 5px;
    
}
.btn:focus{
    outline: none;
}
.srch:focus{
    outline: none;

}
  
        .coform {
            background-color: white;
            top:43%;
        }
        .coform form{
            position: absolute;
            top:45%;
        }
        .coform form h3{
            font-size:30px;
        }
        .coform form input{
            margin-left: 10px;
            width:500px;
            height:25px;
        }
        .coform form textarea{
            margin-left: 10px;
        }
        .coform form button{
            position: absolute;
            background-color:  rgb(22, 165, 222);
            color:white;
            border-radius: 20%;
            margin-left: 10px;
        }
        #submit{
            left:0px;
            width:20%;
        }
        .vl{
            position:absolute;
            border-left: 3px solid rgb(182, 182, 199);
            height: 450px;
            margin-left: 800px;
            top:44%;
        }
        #ci{
            font-size: 30px;
            margin-left: 40px;
        }
        .info{
            position:absolute;
            top:44.3%;
            font-size: 25px;
            background-color: white;
            padding:70px 250px 95px 147px ;
            margin-left: 800px;
        }
        .coform form{
            background-color: white;
            top:44.3%;
            margin-left: 0px;
            padding:0px 282px 50px 0px;
        }
    </style>
    </head>
    <body>
        <header>
            
            
                <div class="main">
                
                <ul>
                <li><a href="contact.html">CONTACT</a></li>
                <li><a href="services.html">SERVICES</a></li>
                <li><a href="people.html">PEOPLE</a></li>
                <li><a href="index.html">HOME</a></li>
                </ul>
            </div>
            <div class="search" >
                <input class="srch" type="search" name="" placeholder="type to search">
                <a href="#"><button class="btn">Search</button></a>
            </div>

            
            
     
            <div class="logo">
                <img src="logo.png" alt="" width="200px" height="200px">
            </div>
            <div class="coform">
            <form>
              <h3>&nbsp;Contact Us</h3>
              <input type="text" placeholder="Your Name"><br><br>
              <input type="text" placeholder="Your Email"><br><br>
              <textarea rows="12" cols="66" >Your Message
              </textarea><br>
              <button id="submit">Submit</button>
            </form>
        </div>
        <div class="info">
            <h3 id="ci" >Contact Information</h3><br>
            <b>Address: </b>No:51, T E K Meadows, Old Mahabalipuram Road, Sholinganallur, Chennai, Tamil Nadu, India, 600119<br><br>
            <b>Email: </b>accenture@gmail.com<br><br>
            <b>Phone: </b>t

            +914442670000
        </div>
        <div class="vl"></div>
    </div>
                <footer>
                    Designed and Developed by HEMA LOKITHA P&copy; 2023
                    </footer>
                   
    </body>
    </html>
```

## OUTPUT:
![Alt text](<Screenshot (60).png>)
![Alt text](<Screenshot (61).png>)
![Alt text](<Screenshot (62).png>)
![Alt text](<Screenshot 2023-12-16 221007.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.

# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

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

### Step 6:

Publish the website in the given URL.

## PROGRAM :
## Home.html:
```python
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Home Page
        </title>
        <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/html/style.css">
    <style>
    .text{
        color:blueviolet;
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
    }
    
    </style>

    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: darkred; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="product.html" title="Products" style="color: darkred; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:darkred; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:darkred; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>Home</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p><b>Welcome to our store</b></p>
                    <p style="color:darkblue; font-family:'Tahoma'; font-size:20px;"> This is the Mobile Store Official Website</p>
                    </div>
                    <p>Our store provides various Types and models of Mobile phones which u wish to get. You can view our store's products in our products page and can choose your desired Mobile Phones and inform us, we will deliver it.</p>
                    <b>Benefits of using our store:</b>
                    <ul>
                        <li>1- yr Warranty</li>
                        <li>3 months replacement guarantee</li>
                        <li>Cash on Delivery</li>
                        <li>EMI Available</li>
                        <li>Free accessories on payment above Rs.50000</li></ul>
                    <div style="text-align: center;color:mediumaquamarine;font-size:20px;"><b>Kindly use our services!</b></div>

                </div>
                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2022 Developed by GOKUL S</footer></div>
            </div>
        </div>
    </body>
</html>
```
## produxt.html:
```python
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            People
        </title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/html/style.css">
        <style>
        .home{
            height: 3000px;
            width: 85%;
            border: 12px solid violet;
            padding-left:10px;
            padding-right:10px;
            margin-left: auto;
            margin-right:auto;
            background-color:darkorange;
        }
        .text{
        color:blueviolet;
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
        
        }
        .content{
            border:1px solid whitesmoke;
            background-color: white;
            width:95%;
            height:2690px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;
        }
        .ceoph{
            background-image: url(/static/html/apple.jpg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:300px;
            width:20%;
            position:relative;
            left: 0px;
            margin-left:auto;
            margin-right: auto;
        }
        .ceo{
            color: gold;
            position:relative;
            text-align:center;
            
            
        }
        .manph1{
            background-image: url(/static/html/apple2.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:300px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;            
        }
        .man1{
            color: sandybrown;
            position:relative;
            text-align:center;
            
        }
        .manph2{
            background-image: url(/static/html/oneplus.jpg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:300px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .man2{
            color: burlywood;
            position:relative;
            text-align:center;
        }
        
        .amph1{
            background-image: url(/static/html/oneplus2.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:300px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am1{
            color: burlywood;
            position:relative;
            text-align:center;
        }

        .amph2{
            background-image: url(/static/html/redmi.jpg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:220px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am2{
            color: burlywood;
            position:relative;
            text-align:center;
        }
        .amph3{
            background-image: url(/static/html/redmi2.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:250px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am3{
            color: burlywood;
            position:relative;
            text-align:center;
        }
        </style>
    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: darkred; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="product.html" title="Products" style="color: darkred; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:darkred; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:darkred; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>Our Products Now Available</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    </div>
                    <div class="ceoph"></div>
                    <div class="ceo"><p align="center"><b><h2>IPhone 14 pro</h2></b></div>
                    <div class="ceo"><p align="center"><b><h2>Price = Inr 190000</h2></b></div>
                    <br>
                    <div class="text">
                    </div>
                    <div class="manph1"></div>
                    <div class="man1"><p align="center"><b><h2>IPhone 13 pro</b></p></div>
                    <div class="man1"><p align="center"><b><h2>Price = Inr 97000</b></p></div>
                    <div class="manph2"></div>
                    <div class="man2"><p><b><h2>one plus 8T</h2></b></p></div>
                    <div class="man2"><p><b><h2>Price  = Inr 40000</h2></b></p></div>
                    <br>
                    <div class="amph1"></div>
                    <div class="am1"><p align="center"><b><h2>one plus 9T</h2></b></p></div>
                    <div class="am1"><p align="center"><b><h2>Price = Inr 20000 </h2></b></p></div>
                    <div class="amph2"></div>
                    <div class="am2"><p align="center"><b><h2>redmi note 9 pro</h2></b></p></div>
                    <div class="am2"><p align="center"><b><h2>Price = Inr 16000</h2></b></p></div>
                    <div class="amph3"></div>
                    <div class="am3"><p align="center"><b><h2>redmi note 12 pro max</h2></b></p></div><br>
                    <div class="am3"><p align="center"><b><h2>Price = Inr 25000</b></p></div><br>
                    <div class="text">Thank you so much for your kind support!<br>Hope our products had helped you!</div>
                </div>
                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2022 Developed by GOKUL S</footer></div>
            </div>
        </div>
    </body>
</html>
``` 
## people.html:
```python
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            People
        </title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/html/style.css">
        <style>
        .home{
            height: 3000px;
            width: 85%;
            border: 12px solid violet;
            padding-left:10px;
            padding-right:10px;
            margin-left: auto;
            margin-right:auto;
            background-color:darkorange;
        }
        .text{
        color:blueviolet;
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
        
        }
        .content{
            border:1px solid whitesmoke;
            background-color: white;
            width:95%;
            height:2690px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;
        }
        .ceoph{
            background-image: url(/static/html/p1.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:300px;
            width:20%;
            position:relative;
            left: 0px;
            margin-left:auto;
            margin-right: auto;
        }
        .ceo{
            color: gold;
            position:relative;
            text-align:center;
            
            
        }
        .manph1{
            background-image: url(/static/html/p2.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:300px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;            
        }
        .man1{
            color: sandybrown;
            position:relative;
            text-align:center;
            
        }
        .manph2{
            background-image: url(/static/html/p3.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:300px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .man2{
            color: burlywood;
            position:relative;
            text-align:center;
        }
        
        .amph1{
            background-image: url(/static/html/p4.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:300px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am1{
            color: burlywood;
            position:relative;
            text-align:center;
        }

        .amph2{
            background-image: url(/static/html/p5.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:220px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am2{
            color: burlywood;
            position:relative;
            text-align:center;
        }
        .amph3{
            background-image: url(/static/html/p6.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:250px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am3{
            color: burlywood;
            position:relative;
            text-align:center;
        }
        </style>
    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: darkred; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="product.html" title="Products" style="color: darkred; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:darkred; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:darkred; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>People</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p>These are our proud management crew!</p>
                    <h4><u>Chairman</u></h4>
                    </div>
                    <div class="ceoph"></div>
                    <div class="ceo"><p align="center"><b><h2>Shalini</h2></b></div>
                    <br>
                    <div class="text">
                        <p><b><u>Head executives</u></b></p><br>
                    </div>
                    <div class="manph1"></div>
                    <div class="man1"><p align="center"><b><h2>Antony</h2></b></p></div>
                    <div class="manph2"></div>
                    <div class="man2"><p><b><h2>Aravind</h2></b></p></div>
                    <br>
                    <div class="text"><p><b><u>Managers</u></b></p></div><br>
                    <div class="amph1"></div>
                    <div class="am1"><p align="center"><b><h2>The Rock</h2></b></p></div>
                    <div class="amph2"></div>
                    <div class="am2"><p align="center"><b><h2>Lawrence</h2></b></p></div>
                    <div class="amph3"></div>
                    <div class="am3"><p align="center"><b><h2>Gowri Ganesh</h2></b></p></div><br>
                    <div class="text">Thank you so much for your kind support!<br>Hope our products had helped you!</div>
                </div>
                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2022 Developed by GOKUL S</footer></div>
            </div>
        </div>
    </body>
</html>
```
## Contact.html:
```python:
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Contact Us
        </title>
        <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/html/style.css">
    <style>
    .text{
        color:blueviolet;
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
    }
    
    </style>

    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: darkred; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="product.html" title="Products" style="color: darkred; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:darkred; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:darkred; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>Contact Us</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p><b>Here are the details about us
                    <h5>Do contact us for any need</h5></b></p>
                    
                    </div>
                    <b><h2>Contact Information:</h2></b>
                    <p><b>&emsp;&ensp;Address:</b>
                         No:101, 5hth street, Besant Nagar, Chennai-600055, TamilNadu
                    </p>
                    <ul>
                        <li><b>phone: 8908243718</b></li>
                        <li><b>shop owner no</b>: 8608674909</li>
                        <li><b>Shop Manager Number:</b> 7305074223</li>
                        <li><b>Email Id:</b>mobilestore88@gmail.com</li>
                        <li><b>Email Id:</b>mobilestore33@gmail.com</li>
                    </ul>
                    <div style="text-align: center;color:violet;font-size:20px;"><b>Please use our services!</b></div>

                </div>
                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2022 Developed by GOKUL S</footer></div>
            </div>
        </div>
    </body>
</html>
```
## Style.css:
```python
        .home{
            height: 700px;
            width: 85%;
            border: 12px solid blue0;
            padding-left:10px;
            padding-right:10px;
            margin-left: auto;
            margin-right:auto;
            background-color:rgb(42, 243, 16);
        }
        .content{
            border:1px solid whitesmoke;
            background-color: white;
            width:95%;
            height:1190px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;
        }
        .header{
            height: 128px;
            width:100%;
            background-image: url(/static/html/buy.jpeg);
            background-size: cover;
            
        }
        .logo{
            height:18%;
            width: 10%;
            position:absolute;
            background-image: url(/static/html/buy.jpeg);
            background-size:cover;
            
        }
        .prod{
            height:auto;
            width:auto;
            position:relative;
            bottom:10px;
            left:550px;
            border:4px solid transparent;
            text-align:center;
            display: inline;
            padding:15px;
            font-family:'Gill Sans MT';
            font-size: large;  
        }
        .prod:hover{
            background-color:aquamarine;
        }
        .people{
            height:auto;
            width:auto;
            position:relative;
            bottom:10px;
            left:700px;
            border:4px solid transparent;
            text-align:center;
            display: inline;
            padding:15px;
            font-family:'Gill Sans MT';
            font-size: large;  
        }
        .people:hover{
            background-color:aquamarine;
        }
        .contact{
            height:20px;
            width:10%;
            position:relative;
            bottom:45px;
            left:1000px;
            border:4px solid transparent;
            text-align:center;
            
            padding:15px;
            font-family:'Gill Sans MT';
            font-size: large;  
        }
        .contact:hover{
            background-color:aquamarine;
        }
                
        .h{
            height:20px;
            width:10%;
            position:relative;
            top:30px;
            left:200px;
            border:4px solid transparent;
            text-align:center;
            
            padding:15px;
            font-family:'Gill Sans MT';
            font-size: large;  
        }
        .h:hover{
            background-color:aquamarine;
            overflow:hidden;
        }
        .footer{
            border: 15px solid red;
            width:98%;
            height:10px;
            position:relative;
            bottom: 1px;
            background-color:red;
            text-align:center;

        }
        .title{
            border:2px solid pink;
            background-color: pink;
            padding:1px;
            width:99%;
            height: 50px;
            text-align:center;
            font-family:'Impact';
            margin-left:auto;
            margin-right: auto;
            
        }
        .content{
            border:1px solid whitesmoke;
            background-color: white;
            width:95%;
            height:392px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;

        }
  ```
## OUTPUT:
### Home Page:
![Screenshot 2023-05-25 091731](https://github.com/gokul-sureshkumar/productcompanywebsite/assets/121148715/7e02ecae-10f2-4eec-a798-688e5c447bdf)
## People Page:
![Screenshot 2023-05-25 091758](https://github.com/gokul-sureshkumar/productcompanywebsite/assets/121148715/84f11d75-8a8d-46f5-96ae-87e5b0b550d7)
![Screenshot 2023-05-25 091832](https://github.com/gokul-sureshkumar/productcompanywebsite/assets/121148715/37c23c95-3137-444e-b399-8951e4678690)
![Screenshot 2023-05-25 091915](https://github.com/gokul-sureshkumar/productcompanywebsite/assets/121148715/733b3b9d-b747-42d9-910e-997c226cf2f2)
![Screenshot 2023-05-25 092004](https://github.com/gokul-sureshkumar/productcompanywebsite/assets/121148715/709fc863-c095-45d3-b0a9-8762bea50678)
## Product Page:
![Screenshot 2023-05-25 091506](https://github.com/gokul-sureshkumar/productcompanywebsite/assets/121148715/28f27b31-368a-4186-9f93-20d0cbbd90e5)
![Screenshot 2023-05-25 091552](https://github.com/gokul-sureshkumar/productcompanywebsite/assets/121148715/ee2aa9d0-ac2f-42b9-bb24-14d614896a5f)
![Screenshot 2023-05-25 091702](https://github.com/gokul-sureshkumar/productcompanywebsite/assets/121148715/f330ff9e-3d9f-48dc-99c5-ad1a5449ad72)
![Screenshot 2023-05-25 091715](https://github.com/gokul-sureshkumar/productcompanywebsite/assets/121148715/98257df7-911b-4c3e-af35-23fb6ba4aca5)
## Contact Page:
![Screenshot 2023-05-25 091334](https://github.com/gokul-sureshkumar/productcompanywebsite/assets/121148715/f3b69779-dd35-4486-85e6-f3de286ba298)
## Server Output:
![Screenshot 2023-05-25 085024](https://github.com/gokul-sureshkumar/productcompanywebsite/assets/121148715/e521648e-f425-4dad-9ee1-a7b5df32ab58)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.

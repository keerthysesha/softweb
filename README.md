# Ex.07 Software Product Company Website
## Date:15/11/23

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

### index.html:

```
<!DOCTYPE html>
<html>
<head>
    <title>AS Tech</title>
    <script type="text/javascript" src="path-to-javascript-file.js"></script>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="main">
        <div class="navbar">
            <div class="icon">
                <h2 class="email">astechchennai@gmail.com</h2>
                <h2 class="logo">AS Tech</h2>
            </div>

            <div class="menu">
                <ul>
                    <li><a href="#">HOME</a></li>
                    <li><a href="#">SALES</a></li>
                    <li><a href="#">PROJECTS</a></li>
                    <li><a href="#">ABOUT</a></li>
                    <li><a href="#">JOBS</a></li>
                    <li><a href="#">CONTACT</a></li>
                </ul>
            </div>

            <div class="search">
                <input class="srch" type="search" name="" placeholder="Search Here">
                <a href="#"> <button class="btn">Search</button></a>
            </div>

        </div>
        <div class="content"> 
            <h1>Web Development</h1>
            <h2>Making website is very esay now . You just need to learn HTML, <br>CSS, Javascript and you are good to go.</h2>
            <a href="" class="hero-btn">Visit Us to Know More</a>
        </div>


        <div class="form">
            <h2>Login Here</h2>
            <input type="email" name="email" placeholder="Enter Email Here">
            <input type="password" name="" placeholder="Enter Password Here">
            <button class="btn"><a href="#">Login></a></button>

            <p class="link">Don't have an account<br>
            <a href="#">Sign up</a> here</a></p>
        </div>

        <div class="about">
            <hr>
        </div>
            <div class="about-us">
            <h1>AS Tech <br>Whom We Are?</h1>
            <p> we are a young and motivated company,full of new ideas and energy. we aim to supply tip-top services and products to all our customers and contribute to having a marketplace where every business has equal opportunities to grow.</p>
            </div>
        <div class="sales">
            <h1>Sales</h1>
            <p>laptops,phones,ipads...</p>
        </div>
        <div class="projects">
            <h1>Projects</h1>
            <p>Web Development,Web Design,Mobile Development...</p>
        </div>
        <hr>
    </div>
    <div class="images">
        <img src="laptop.png" width="350px" height="600px">
        <em>laptop</em>
        <img src="ipad.png" width="350px" height="600px">
        <em>ipad</em>
        <img src="phone.png" width="350px" height="600px">
        <em>phone</em>
    </div>
    
    <div class="line">
        <hr>
    </div>
    <div class="contact">
        <h1>AS Tech</h1>
        <p>contact us<br>Phone Number : 8056828289<br>Email : astechchennai@gmail.com</p>
        <div class="categories">
             <h1>Categories</h1>
             <p>Privacy Policy<br>Disclaimer Policy<br>Warranty Policy</p>    
        </div>
        <div class="customer-support">
            <h1>Customer Support</h1>
            <p>Terms & Conditions<br>Service Supports<br>Service Centers</p>
        </div>
    </div>
    <footer>

    </footer>
</body>
</html>

```

### styles.css:
```
body{
    background-color: burlywood;
    margin=0px;
}

.navbar{
    width: 1200px;
    height: 75px;
    margin: auto;
}

.icon{
    width: 200px;
    float: left;
    height: 70px;
}

.email{
    color: #0000FF ;
    font size: 20px;
    font family: Arial;
    align-items:centre;
    margin-left: 450px;
    margin-top: 25px;
}

.logo{
    color:#0000FF;
    font-size: 48px;
    font-family: Arial;
    margin-left: 10px;
    float: left;
    margin-top: 1px;
}

.menu{
    width: 300px;
    float: left;
    height: 70px;
}

ul{
    float: left;
    display: flex;
    justify-content: centre;
    align-items: centre;
}

ul li{
    list-style: none;
    margin-left: 22px;
    margin-top: 75px;
    font-size: 14px;
}

ul li a{
     text-decoration: none;
     color: black;
     font-family: Arial;
     font-weight: bold;
     transition: 0.4s ease-in-out;
}

ul li a:hover{
    color: #0000FF;
}

.search{
    width: 330px;
    float: left;
    margin-left: 300px;
}
.srch{
    width: 200px;
    height: 40px;
    background: transparent;
    border: 1px solid black;
    margin-top: 75px;
    color: blue;
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
    background: black;
    border:2px solid black;
    margin-top: 75px;
    color: blue;
    font-size: 15px;
    border-bottom-right-radius: 5px;
    border-bottom-right-radius: 5px;
}

.btn:focus{
    outline: none;
}

.srch:focus{
    outline: none;
}

.form{
    width: 250px;
    height: 350px;
    background: linear-gradient(to top, rgba(0, 0, 0, 0.8)50%,rgba(0, 0, 0, 0.8)50% );
    position: absolute;
    top: 175px;
    left: 950px;
    border-radius: 10px;
    padding: 25px;
}

.form h2{
    width: 220px;
    font-family: sans-serif;
    text-align: center;
    color: #0000FF;
    font-size: 22px;
    background-color: #fff;
    border-radius: 10px;
    margin: 2px;
    padding: 8px;
}

.form input{
    width: 240px;
    height: 25px;
    background: transparent;
    border-bottom: 1px solid blue;
    border-top: none;
    border-right: none;
    border-left: none;
    color: #fff;
    font-size: 15px;
    letter-spacing: 1px;
    margin-top: 30px;
    font-family: sans-serif;
}

.form input:focus{
    outline: none;
}

::placeholder{
    color: #fff;
    font-family: Arial;
}

.btnn{
    width: 240px;
    height: 40px;
    background: #0000FF;
    border: none;
    margin-top: 30px;
    font-size: 18px;
    border-radius: 10px;
    cursor: pointer;
    color: #fff;
    transition: 0.4s ease;
}

.btnn.hover{
    background: #fff;
    color: #0000FF;
}

.btnn a{
    text-decoration: none;
    color: black;
    font-weight: bold;
}

.form .link{
    font-family: Arial, Helvetica, sans-serif;
    font-size: 17px;
    padding-top: 20px;
    text-align: centre;
}

.form .link a{
    text-decoration: none;
    color: #0000FF;
}

.liw{
    padding-top: 15px;
    padding-bottom: 10px;
    text-align: center;
}
.content{
    width: 90%;
    color: black;
    position: absolute;
    top: 50%;
    left: 50%;
    margin-top: 30px;
    transform: translate(-50%,-50%);
    text-align: left;
}

.content h1{
    font-size: 44px;
}

.hero-btn{
    display: inline-block;
    text-decoration: none;
    color: blue;
    border: 1px solid black;
    margin-top: 50px;
    padding: 12px 34px;
    font-size: 13px;
    background: transparent;
    position: relative;
    cursor: pointer;
}

.hero-btn:hover{
    border: 1px solid black;
    background: black;
    transition: 1s;
}

.about-us{
    width: 80%;
    color: #0000FF;
    text-align: center;
    margin-left: 110px ;
    margin-top: 5px;
}
 
.about{
    width: 1500px;
    color: black;
    margin-left: 35px;
    margin-right: 65px;
    margin-top: 550px;
}

.about-us p{
    width: 80%;
    color: black;
    font-size: 20px;
    margin-left: 110px;
}

.sales{
    width: 80%;
    color: #0000FF;
    text-align: center;
    margin-left: 110px;
}

.sales p{
    width: 80%;
    color: black;
    font-size: 20px;
    margin-left: 110px;
}

.projects{
    width: 80%;
    color: #0000FF;
    text-align: center;
    margin-left: 110px;
}

.projects p{
    width: 80%;
    color: black;
    font-size: 20px;
    margin-left: 110px;
}

.line hr{
    width: 1500px;
    color: black;
    margin-left: 35px;
    margin-right: 65px;
    margin-top: 70px;
}

.images{
    margin-left: 90px;
    margin-top: 70px;
}

.contact{
    width: 80%;
    color: #0000FF;
    margin-top: 40px;
    text-align: left;
    margin-left: 100px;
}

.contact p{
    width: 80%;
    color: black;
    font-size: 20px;
    margin-left: 10px;
}

.categories{
    width: 80%;
    color:blue;
    text-align: center;
    margin-left: 180px;
    margin-top: -150px;
}

.categories p{
    width: 80%;
    color: black;
    font-size: 20px;
    margin-left: 90px;
}

.customer-support{
    width: 80%;
    color:blue;
    text-align: right;
    margin-top: -150px;
    margin-right: -120px;
    margin-left: 350px;
}

.customer-support p{
    width: 80%;
    color: black;
    font-size: 20px;
    margin-right: -120px;
    margin-left: 130px;
}

```

## OUTPUT:

![Screenshot 2023-11-16 001324](https://github.com/keerthysesha/softweb/assets/125575936/13f87cda-2319-417d-8ccf-7382ed91fd93)
![Screenshot 2023-11-16 001339](https://github.com/keerthysesha/softweb/assets/125575936/9e5847a3-b7cc-421d-84ab-638b15bcdb7a)
![Screenshot 2023-11-16 001348](https://github.com/keerthysesha/softweb/assets/125575936/71f7ebaf-8158-43c0-8cdf-ba946dfc5b5d)
![Screenshot 2023-11-16 001359](https://github.com/keerthysesha/softweb/assets/125575936/4a4e6b0b-7f67-499c-9823-e44ccbaf5a0f)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.

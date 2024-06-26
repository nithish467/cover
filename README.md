# Ex.06 Book Front Cover Page Design
## Date:09/04/2024

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<html>

<head>
    <title>JS</title>
    <style>
        .bookpage{

            width: 400px;
            height: 650px;
            color:rgb(255, 0, 0);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Roquen';
            background-image: url(wp12454753-javascript-logo-wallpapers.png);
            background-size: cover;
        }
            
        
        .insight{
            color:rgb(255, 0, 0);
        
        }
    
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:rgb(255, 0, 0);
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:rgb(0, 0, 0);
            font-family: 'sans-serif';
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            color:rgb(255, 0, 0);
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .edition{
            color:rgb(0, 0, 0);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:90px;
        
        }
        .subtitle{
            color:rgb(255, 0, 0);
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 145px;
            left: 260px;
            width: 90px;
            height: 80px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHT 
            </div>
            <div class="hrstyle">
                <hr style="color:rgb(255, 153, 0)">
            </div>
            <div class="booktitle">
                <h1>ELOQUENT JAVASCRIPT</h1></div>
            <div class="subtitle">
            </div>
            <div class="subtitle">
                <h2 align="center">A MODERN INTRODUCTION TO PROGRAMMING</h2>
            </div>

            <div class="mypic">
                <img src="cover.jpg" width="100" height="120" >
            </div>
            <div class="id">
                <hr style="color:rgb(255, 249, 82)">
            </div>
            <div class="author">
               <p><b>NITHISH KUMAR S</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="edition">
                <b>EXRENTED EDITION</b>
            </div>
        </div>
        </body>
        

</html>
```


## OUTPUT:
![alt text](<Screenshot (33).png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

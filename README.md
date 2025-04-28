# Ex.06 Book Front Cover Page Design
## Date:28.04.2025

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


## OUTPUT:
```
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compataible"content="IE=edge">
        <meta name="viewport" content="width=device-width,initial-scale=1.0">
        <link rel="stylesheet"href="style.css">
        <title>book cover</title>
    </head>
    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <style>
        .image-container {
          position: relative;
          text-align: center;
        }
        .image-container img {
          width: 40%;
          height: 20%;
        }
        .centered-text {
          position: absolute;
          top:10%;
          left: 50%;
          transform: translate(-50%, -50%);
          color: rgb(20, 24, 26);
          font-size: 24px;
          font-weight: bold;
        }
        .centered-text2{
            position: absolute;
            top:75%;
            left:35%;
            transform:translate(-50,-50) ;
            color:rgb(170, 186, 187);
            font-size: 24px ;
            font-weight: bold;
        }
        .centered-text3{
            position: absolute;
            TOP:40%;
            left:33%;
            transform:translate(-50,-50) ;
            color:rgb(11, 8, 17);
            font: size 24px; 
            font-weight: bold;
        }
        .centered-text4{
          position: absolute;
          top:75%;
          left:60%;
          width: 85px;
          height: 20px;
          
        }
      </style>
    </head>
    <body>
      <div class="image-container">
        <img src="gen2.jpg" alt="Image" height="50px" width="50px">
        <div class="centered-text"><h2>CONCEPTS OF GENETICS<HR><H3>THE EPIGENETICS REVOLUTION</H3></h2></div>
      </div> <BR><br><br><br>
        <div class="centered-text2"><h3>NESSA CAREY</h3><HR><H4>READ BY DONNA POSTEL</H4></div>
        <div class="centered-text3"><h3>How Modern Biology is Rewritting our understanding<br>of Genetics,Disease,and Inheritance</h3></div>
        <div class="centered-text4"><img src="GEN3.jpg" width="130px" height="130px"></div>
    </body>
    </html>
    
</html>


```
OUTPUT:
![image](https://github.com/user-attachments/assets/35282a6f-23da-4b42-aeef-055f4bd2a5ec)




## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

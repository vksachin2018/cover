# Ex.06 Book Front Cover Page Design
## Date:09:04:2024

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
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <style type="text/css">
            .bookcover {
                width: 400px;
                height: 640px;
                color:black (221, 39, 39);
                margin-left: auto;
                margin-right: auto;
                padding: 20px;
                font-family:Verdana, Geneva, Tahoma, sans-serif;
                background-image: url(image.png );
                background-size: cover;
            }
            .insight {
                color:black (221, 39, 39);
            }
            .hr1 {
                width: 130px;
                color:black (221, 39, 39);
            }

            .h1 {
                font-size: larger;
                font-family: Arial, Helvetica, sans-serif;
                text-align: center;
                position: relative;
                top: 30px;
                color:black (221, 39, 39);
            }

            .para {
                font-size: medium;
                font-family: Arial, Helvetica, sans-serif;
                position: relative;
                top: 40px; 
                color:black (221, 39, 39); 
            }

            .edition {
                font-size: large;
                font-family: Arial, Helvetica, sans-serif;
                color:black (221, 39, 39);
                top: 90px;
                position: relative;
            }

            .pic {
                position: relative;
                top: 150px;
                left: 250px;
                width: 100px;
                height: 100px;
                background-size: cover;
                color:black (221, 39, 39);
            }

            .hr2 {
                position: relative;
                width: 400px;
                top: 200px;
                color:black (221, 39, 39);
            }

            .name {
                font-size: medium;
                font-family: Arial, Helvetica, sans-serif;
                display: inline;
                position: relative;
                color:black (221, 39, 39);
                top: 210px;
            }
            .pub {
                font-size: large;
                position: relative;
                top: 180px;
                left: 330px;
                color:black (221, 39, 39);
            }
        </style>
        <title> Book Front Cover Page  </title>
    </head>
    <body>
        <div class="bookcover">
            <div class="insight">
                EXPERT INSIGHT
            </div>
            <div class="hr1">
                <hr>
            </div>
            <div class="h1">
                <h1> Decoding The Software Industry </h1>
            </div>
            <div class="para">
                <p> Unlock The secrets of the software industry with this insightful handbook </p>
            </div>
            <div class="pic">
                <img src="image copy.png" width="150" height="150" >
            </div>
            <div class="hr2">
                <hr>
            </div>
            <div class="name">
                <p><b>Gokul sachin k(212223220025)</b></p>
            </div>
            <div class="pub">
                <b> SEC </b>
            </div>
            <div class="edition">
                <b> Third Edition </b>
            </div>
        </div>
    </body>
</html>

```


## OUTPUT:
![image](https://github.com/vksachin2018/cover/assets/149366019/19c2e99b-fc6c-4931-88e6-45f2e6377253)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

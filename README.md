# Ex.06 Book Front Cover Page Design
## Date: 23.10.2024

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
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: rgb(110, 113, 119); /* Fallback background color */
        }

        .bookpage {
            width: 400px;
            height: 600px;
            color: rgb(0, 0, 0);
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url('background.png');
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;
        }

        .insight {
            color: rgb(1, 1, 1);
        }

        .hrstyle {
            width: 100px;
        }

        .author {
            display: inline;
            position: relative;
            color: rgb(14, 13, 13);
            top: 190px;
            font-family: Georgia;
            font-size: medium;
        }

        .booktitle {
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        }

        .id {
            width: 400px;
            position: relative;
            top: 180px;
        }

        .pub {
            font-size: medium;
            position: relative;
            top: 155px;
            left: 330px;
        }

        .ed {
            color: rgb(8, 8, 8);
            font-size: medium;
            font-family: Verdana;
            position: relative;
            top: 230px;
            right: 410px;
        }

        .subtitle {
            font-family: Tahoma;
            font-size: large;
            position: relative;
            top: 40px;
        }

        .mypic {
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
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
            <hr style="color: yellow;">
        </div>
        <div class="booktitle">
            <h1>The complete Web Design with HTML and CSS</h1>
        </div>
        <div class="subtitle">
            To learn how the web page works and developmet of server page
        </div>
        <div class="mypic">
            <img src="my photo.jpg" width="130" height="145" alt="">
        </div>
        <div class="id">
            <hr style="color: orange;">
        </div>
        <div class="author">
            <p><b>RAJALAKSHMI R</b></p>
        </div>
            SEC 
        </div>
        <div class="ed">
            <b>Third Edition</b>
        </div>
    </div>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2024-04-09 145037.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

# Ex.08 Design of Interactive Image Gallery
## Date:07.10.2025

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
gallery.html


<!DOCTYPE html>
<html>
<head>
  <title>IMAGE GALLERY</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h2>hari's Image Gallery</h2>

  <div class="gallery">
    <img src="image1.jpg" alt="Photo 1">
    <img src="image2.jpg" alt="Photo 2">
    <img src="image3.jpg" alt="Photo 3">
    <img src="image4.jpg" alt="Photo 4">
    <img src="image5.jpg" alt="Photo 5">
  </div>

  <div class="popup" id="popup">
    <span id="close">&times;</span>
    <img id="popupImg" src="">
  </div>
  <center>
    <h3>&copy;Image Gallery Designed by:</h3>
    <h2>HARIPRASATH.S-25017723</h2>
  </center>

  <script src="script.js"></script>
</body>
</html>

style.css

body {
  background-color:pink;
  font-family: Arial, sans-serif;
  margin: 0;
  display: flex;
  flex-direction: column;
  align-items: center;
}

h2 {
  margin: 20px;
}

.gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 30px;
  padding:35px;
}

.gallery img {
  width: 400px;
  height: 610px;
  object-fit: cover;
  border-radius: 10px;
  cursor: pointer;
  transition: transform 0.2s;
}

.gallery img:hover {
  transform: scale(1.05);
}


.popup {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.8);
  display: none;
  justify-content: center;
  align-items: center;
}

.popup img {
  width: 60%;
  max-width: 400px;
  border-radius: 12px;
  box-shadow: 0 0 20px #000;
}

.popup span {
  position: absolute;
  top: 20px;
  right: 40px;
  font-size: 40px;
  color: white;
  cursor: pointer;
  font-weight:bolder;
}





```
## OUTPUT:
![alt text](<leo/glleryapp/static/Screenshot 2025-10-07 182748.png>)
![alt text](<leo/glleryapp/static/Screenshot 2025-10-07 182825.png>)

## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.

# Ex.08 Design of Interactive Image Gallery
## Date: 25/12/2025

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
h1 {
    text-align: center;
    margin-bottom: 30px;
    color: darkmagenta;
}

.gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 15px;
}

.gallery img {
    width: 100%;
    height: auto;
    border-radius: 10px;
    cursor: pointer;
    transition: transform 0.3s, box-shadow 0.3s;
}

.gallery img:hover {
    transform: scale(1.05);
    box-shadow: 0 10px 20px rgba(0,0,0,0.3);
}

/* Lightbox overlay */
.lightbox {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0,0,0,0.8);
    display: none;
    justify-content: center;
    align-items: center;
}

.lightbox img {
    max-width: 90%;
    max-height: 80%;
    border-radius: 10px;
}

.lightbox:target {
    display: flex;
}

.close {
    position: absolute;
    top: 20px;
    right: 30px;
    font-size: 30px;
    color: #fff;
    text-decoration: none;
}
```

## OUTPUT:
<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/c2fd7ca8-2d82-4c73-a1c3-79ba45a7f108" />

## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.

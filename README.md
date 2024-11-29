# Ex.06 Book Front Cover Page Design
## Date:29.11.2024

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
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;500;700&family=Roboto:wght@400;500&display=swap" rel="stylesheet">
  <style>
    /* General Reset */
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      background: #e0f7fa; /* Light cyan background */
      color: #333; /* Dark text color */
    }

    /* Book Cover Container */
    .book-cover {
      position: relative;
      width: 800px; /* Book cover width */
      height: 1200px; /* Book cover height */
      background: url('https://media.licdn.com/dms/image/v2/D5612AQGrlmwjCT078A/article-cover_image-shrink_720_1280/article-cover_image-shrink_720_1280/0/1716484384275?e=2147483647&v=beta&t=3eNZXCHe3VeyTHOJIwsAcYEe3uOdLL_dqV9eHdLxaXs') no-repeat center center/cover; /* Your Background Image */
      border: 10px solid #00bcd4; /* Cyan border */
      border-radius: 20px; /* Rounded corners */
      box-shadow: 0 0 30px rgba(0, 0, 0, 0.2); /* Subtle shadow */
      overflow: hidden;
      text-align: center;
      position: relative;
      padding: 50px;
    }

    /* Title Styling using Orbitron Font */
    .book-title {
      font-family: 'Orbitron', sans-serif;
      font-size: 4.5em;
      text-transform: uppercase;
      letter-spacing: 5px;
      margin-top: 100px;
      color: #ffeb3b; /* Bright yellow color */
      z-index: 1;
      position: relative;
      font-weight: bold;
      text-shadow: 0 0 15px rgba(255, 235, 59, 0.8);
    }

    /* Subtitle Styling using Roboto Font */
    .book-subtitle {
      font-family: 'Roboto', sans-serif;
      font-size: 2.2em;
      margin-top: 20px;
      color: #ff4081; /* Bright pink color */
      z-index: 1;
      position: relative;
      text-shadow: 0 0 10px rgba(255, 64, 129, 0.8);
    }

    /* Tech-themed Element List */
    .tech-elements {
      font-size: 1.5em;
      margin: 50px;
      text-align: left;
      z-index: 1;
    }

    .tech-elements li {
      list-style: none;
      padding: 10px 20px;
      margin-bottom: 15px;
      border-left: 4px solid #00bcd4;
      color: #ffffff; /* White color */
      font-family: 'Orbitron', sans-serif; /* Futuristic font */
      font-weight: bold;
      text-shadow: 0 0 15px rgba(255, 255, 255, 0.8); /* White glow effect */
      background: rgba(0, 188, 212, 0.1);
      border-radius: 5px;
      transition: background 0.3s ease;
    }

    .tech-elements li:hover {
      background: rgba(0, 188, 212, 0.3);
    }

    /* Right Bottom Photo */
    .right-bottom-photo {
      position: absolute;
      bottom: 20px; /* Adjust bottom distance */
      right: 20px; /* Adjust right distance */
      width: 300px; /* Increased width */
      height: 300px; /* Increased height */
      background: url('https://i.ibb.co/ynL0fd3/Whats-App-Image-2024-11-27-at-9-02-36-AM-1.jpg') no-repeat center center/cover; /* Your online photo */
      background-position: top; /* Focus on the top part of the image */
      border: 5px solid #00bcd4; /* Cyan border for photo */
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.3); /* Shadow around image */
      border-radius: 10px; /* Rounded corners */
    }

    /* SEC Text Above the Photo */
    .sec-text {
      position: absolute;
      bottom: 350px; /* Move it higher above the photo */
      right: 40px;
      font-family: 'Orbitron', sans-serif;
      font-size: 3em;
      color: white; /* White color */
      font-weight: bold;
      text-shadow: 0 0 10px rgba(255, 255, 255, 0.8); /* White glow effect */
    }

    /* Below the photo - REF.NO and NAME */
    .right-bottom-photo-info {
      position: absolute;
      bottom: 10px; /* Adjust distance from the bottom */
      right: 20px; /* Right aligned */
      color: #ffffff; /* White text */
      font-size: 1em;
      text-align: center;
      font-family: 'Roboto', sans-serif;
      z-index: 1;
      background: rgba(0, 0, 0, 0.5); /* Semi-transparent background */
      padding: 10px;
      border-radius: 5px;
    }

  </style>
</head>

<body>
  <div class="book-cover">
    <div class="book-title">Shape-Shifting Gadgets</div>
    <div class="book-subtitle">Redefining Adaptability</div>
    <ul class="tech-elements">
      <li>Modular Smartphones</li>
      <li>Transforming Robots</li>
      <li>Foldable Screens</li>
      <li>Adaptive Wearables</li>
    </ul>
    <!-- Right Bottom Image -->
    <div class="right-bottom-photo"></div>
    <!-- SEC Text Above the Photo -->
    <div class="sec-text">SEC</div>
    <!-- Details below the photo -->
    <div class="right-bottom-photo-info">
      REF.NO: 24901330<br>
      NAME: G.T.GOWTHAM
    </div>
  </div>
</body>
</html>
```


## OUTPUT:
![alt text](<exp 6.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

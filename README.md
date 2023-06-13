# Exp-3 Create a Web-Layout using FLEXBOX.
## AIM:
To write html & css code to create Web-Layout using FLEXBOX.
## PROCEDURE:
### STEP 1:
Create a html code for the Web-Layout.
### STEP 2:
Make style for the Web Layout using style tag.
### STEP 3:
Include Style in the html using class and id Selector.
### STEP 4:
Verify the output by running the Web-Layout in any web browser. 
## PROGRAM:
### HTML&CSS:
```html
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" type="text/css" href="header.css">
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      background-color: #e353ae;
    }
    
    header {
      background-color: #333;
      padding: 20px;
      color: #fff;
      text-align: center;
    }
    
    main {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      align-items: flex-start;
      gap: 20px;
      margin-top: 20px;
      padding: 20px;
      background-color: #ffffff;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
	  border-color: #333;
    }
    
    .box {
      flex-basis: 300px;
      padding: 20px;
      background-color: #66cc99;
      border-radius: 5px;
      color: #000000;
    }
    
    footer {
      background-color: #333;
      padding: 20px;
      color: #fff;
      text-align: center;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to our Fullstack Course</h1>
  </header>
  
  <main>
    <div class="box">
      <h2>Syllabus</h2>
      <p>A full-stack Java developer is a web programmer who uses Java, a popular computer programming language.</p>
    </div>
    <div class="box">
      <h2>Practices</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse quis mollis leo.</p>
    </div>
    <div class="box">
      <h2>Skills Learned</h2>
      <p>A Java full stack developer is responsible for developing and maintaining both front-end and back-end of web applications. </p>
    </div>
  </main>
  <br>
  <br>
  <footer>
	

    <p>&copy; 2023 Saveetha. All rights reserved.</p>
  </footer>
</body>
</html>

```
## CSS:
```css

.box:nth-child(1) {
  background-color: #46e86e;
}

.box:nth-child(2) {
  background-color: #6699ff;
}

.box:nth-child(3) {
  background-color: #ffcc66;
}

```
## OUTPUT:
![flexbox](https://github.com/naveenkumar12624/Mern-Ex-03/assets/93427235/ef9b5d2d-43a1-4150-ae58-c3f1622ff8d3)

## RESULT:
html & css code to create Web-Layout using FLEXBOX has been created and output has been verified.

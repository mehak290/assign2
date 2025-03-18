# Project Name
WEBPAGE 

## Description
This project is designed to showcase a webpage with an interactive button, created using simple HTML and CSS. The goal is to demonstrate basic web development skills.

## Demo Preview (HTML & CSS)
Here is a simple **HTML & CSS** snippet used in this project:

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>WEBPAGE</title>
  <style>
    /* Global Styles */
    body {
      font-family: Verdana, Geneva, Tahoma, sans-serif;
      text-align: justify;
      background-color: bisque;
      margin: 0;
      padding: 0;
    }
    h1 {
      color: deeppink;
      background-color: cornsilk;
      text-align: center;
      margin: 0;
      padding: 20px;
    }
    h2 {
      color: coral;
    }
    h4 {
      color: greenyellow;
    }
    p {
      color: blue;
    }
    img {
      height: 500px;
      width: 500px;
      border: 2px solid #000;
    }

    /* Navigation */
    #navigation {
      background-color: black;
      margin: 20px;
      padding: 10px;
      text-align: center;
    }
    #navigation a {
      color: white;
      text-decoration: none;
      margin: 0 10px;
    }

    /* Container for Content */
    #container {
      display: flex;
      flex-direction: column;
      max-width: 800px;
      margin: auto;
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    }

    /* Skills Section */
    #skills {
      display: flex;
      flex-direction: column;
    }
    #skill-indicators {
      display: flex;
      flex-wrap: wrap;
    }
    .skill {
      background-color: #e0e0e0;
      border-radius: 4px;
      margin: 5px;
      padding: 10px;
      color: #fff;
      text-align: center;
      position: relative;
      flex: 0 0 auto;
    }
    .skill span {
      position: absolute;
      right: 10px;
      top: 5px;
    }

    /* Responsive Styles */
    @media (max-width: 600px) {
      #container {
        padding: 10px;
      }
      #skill-indicators {
        flex-direction: column;
      }
      .skill {
        width: 100%;
        margin: 10px 0;
      }
    }

    /* Featured Post */
    #featured-post {
      max-width: 600px;
      margin: 20px auto;
      padding: 20px;
      border: 1px solid #ccc;
      border-radius: 8px;
      background-color: white;
      position: relative;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    }
    #featured-image {
      width: 100%;
      border-radius: 4px;
    }
    #summary {
      margin: 15px 0;
    }
    #read-more {
      position: absolute;
      bottom: 20px;
      right: 20px;
      padding: 10px 15px;
      background-color: #007bff;
      color: white;
      text-decoration: none;
      border-radius: 4px;
      transition: background-color 0.3s;
    }

    /* Card Styles */
    #card {
      position: relative;
      max-width: 300px;
      background: linear-gradient(135deg, #e0f7fa, #b2ebf2);
      border-radius: 8px;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
      overflow: hidden;
      transition: transform 0.3s ease;
      padding: 20px;
    }
    #card:hover {
      transform: scale(1.05);
    }
    #card::before,
    #card::after {
      content: '';
      position: absolute;
      border: 2px solid rgba(255, 255, 255, 0.7);
      border-radius: 10px;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
    }
    #card::before {
      transform: translate(-5px, -5px);
    }
    #card::after {
      transform: translate(5px, 5px);
    }
    #card-title {
      font-size: 1.5em;
      color: #00796b;
      margin: 0 0 10px 0;
    }
    #card-image {
      width: 100%;
      border-radius: 4px;
    }
    #card-description {
      color: #555;
      margin: 10px 0;
      overflow-wrap: break-word;
    }
    #card-description a {
      color: #00796b;
      text-decoration: none;
      transition: color 0.2s;
    }
    #card-description a:hover {
      color: #004d40;
    }
    #card-description a:active {
      color: #00332a;
    }
  </style>
</head>
<body>
  <header>
    <h1>ASSIGNMENT3</h1>
  </header>
  <div id="navigation">
    <a href="#">HOME</a>
    <a href="#about">ABOUT</a>
    <a href="#contact">CONTACT</a>
  </div>

  <div class="blog1">
    <h2>HTML</h2>
    <p>
      HTML (HyperText Markup Language) is the backbone of the web. It provides the fundamental
      structure of web pages by using a system of tags and elements that define and organize content
      such as text, images, and multimedia. HTML allows developers to outline the layout and semantics
      of a page, making it easier for both browsers and users to understand and navigate the content.
      When combined with CSS and JavaScript, HTML transforms into a dynamic medium that can deliver
      rich, interactive experiences. Whether you're building a simple blog or a complex web application,
      understanding HTML is essential for creating accessible and well-structured digital content.
    </p>
  </div>

  <div class="blog2">
    <h2>CSS</h2>
    <p>
      CSS (Cascading Style Sheets) is a stylesheet language that defines how HTML elements are
      displayed on screen, on paper, or in other media. It allows developers to separate content
      from design by specifying layout, colors, fonts, spacing, animations, and other visual aspects
      of a webpage. With CSS, you can create responsive and visually engaging web pages that adjust
      to different screen sizes and devices. By organizing style rules in external stylesheets, you
      ensure consistency across your website while also making it easier to update and maintain the design.
      CSS has evolved to support advanced features like flexbox, grid layouts, and custom properties,
      enabling dynamic and modern user interfaces.
    </p>
  </div>
</body>
</html>


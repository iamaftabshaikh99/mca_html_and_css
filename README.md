# HTML and CSS Examples

This repository contains a collection of HTML and CSS examples to demonstrate various functionalities and styling techniques.

## Table of Contents

1. [Repeat Background Image](#1-repeat-background-image)
2. [Repeat Background Image Horizontally](#2-repeat-background-image-horizontally)
3. [Set Background Colors for Different Elements](#3-set-background-colors-for-different-elements)
4. [Repeat Background Image Vertically](#4-repeat-background-image-vertically)
5. [No Repeat Background Image](#5-no-repeat-background-image)
6. [Set Right Margin for a Paragraph](#6-set-right-margin-for-a-paragraph)
7. [Set Maximum Width for Paragraph](#7-set-maximum-width-for-paragraph)
8. [Text Decoration for Headings](#8-text-decoration-for-headings)
9. [Set Rounded Border](#9-set-rounded-border)
10. [Display Different Cursor Types](#10-display-different-cursor-types)
11. [Indent First Line of Paragraphs](#11-indent-first-line-of-paragraphs)
12. [Set Line Height in Percent](#12-set-line-height-in-percent)
13. [Z-Index Demonstration](#13-z-index-demonstration)
14. [Rotate an Element Using CSS](#14-rotate-an-element-using-css)
15. [Client-Side Image Mapping](#15-client-side-image-mapping)

---

### 1. Repeat Background Image

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Background Image Repeat</title>
    <style>
        .full-repeat {
            background-image: url('calm.jpg');
            background-repeat: repeat;
            height: 4000px;
            color: rgb(0, 94, 255);
        }
    </style>
</head>
<body>
    <div class="full-repeat">Full Repeat</div>
</body>
</html>
```

---

### 2. Repeat Background Image Horizontally

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Background Image Horizontally</title>
    <style>
        .repeat-x {
            background-image: url('abj.jpg');
            background-repeat: repeat-x;
            height: 2000px;
            color: red;
        }
    </style>
</head>
<body>
    <div class="repeat-x">Repeat Horizontally</div>
</body>
</html>
```

---

### 3. Set Background Colors for Different Elements

```html
<!DOCTYPE html>
<html>
<head>
    <title>Background Colors Example</title>
    <style>
        body {background-color: #f0f0f0;}
        header {
            background-color: #960606;
            color: rgb(255, 255, 255);
            padding: 20px;
            text-align: center;
        }
        section {
            background-color: #ff7b00;
            color: white;
            padding: 20px;
            margin: 10px 0;
        }
        article {
            background-color: #006915;
            color: rgb(255, 0, 0);
            padding: 15px;
            margin: 10px 0;
        }
        .highlight {
            background-color: #FFC107;
            color: #333;
            padding: 10px;
            margin: 10px 0;
        }
        footer {
            background-color: #4f005f;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Header Section</h1>
    </header>
    <section>
        <h2>Section 1</h2>
        <p>This section has a blue background color.</p>
    </section>
    <section>
        <h2>Section 2</h2>
        <p>This section also has a blue background color.</p>
    </section>
    <article>
        <h2>Article</h2>
        <p>This article has an orange background color.</p>
    </article>
    <div class="highlight">
        <p>This div has an amber background color, specified by the 'highlight' class.</p>
    </div>
    <footer>
        <p>Footer Section</p>
    </footer>
</body>
</html>
```

---

### 4. Repeat Background Image Vertically

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Background Image Repeat</title>
    <style>
        .repeat-y {
            background-image: url('abj.jpg');
            background-repeat: repeat-y;
            height: 6000px;
            color: red;
        }
    </style>
</head>
<body>
    <div class="repeat-y">Repeat Vertically</div>
</body>
</html>
```

---

### 5. No Repeat Background Image

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Background Image No Repeat</title>
    <style>
        .no-repeat {
            background-image: url('abj.jpg');
            background-repeat: no-repeat;
            height: 500px;
            background-size: cover;
            color: red;
        }
    </style>
</head>
<body>
    <div class="no-repeat">No Repeat</div>
</body>
</html>
```

---

### 6. Set Right Margin for a Paragraph

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Right Margin for Paragraph</title>
    <style>
        p {
            margin-right: 20px;
        }
        .custom-margin {
            margin-right: 50px;
        }
    </style>
</head>
<body>
    <p>This paragraph has a right margin of 20px.</p>
    <p class="custom-margin">This paragraph has a right margin of 50px, specified by the 'custom-margin' class.</p>
</body>
</html>
```

---

### 7. Set Maximum Width for Paragraph

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Max Width for Paragraph</title>
    <style>
        p {
            max-width: 800px;
            margin: 0 auto;
        }
        body {
            font-family: cursive;
            line-height: 2;
        }
    </style>
</head>
<body>
    <p>This paragraph has a maximum width of 800px. When the screen is wider, the paragraph will stay at this width and be centered due to the `margin: 0 auto` setting.</p>
    <p>This approach is useful for keeping text readable by limiting the line length, especially on large screens.</p>
</body>
</html>
```

---

### 8. Text Decoration for Headings

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Text Decoration for Headings</title>
    <style>
        h1 {text-decoration: underline;}
        h2 {text-decoration: overline;}
        h3 {text-decoration: line-through;}
        h4 {text-decoration: none;}
        h5 {text-decoration: underline overline;}
        .special-heading {
            text-decoration: underline;
            text-decoration-color: rgb(255, 0, 242);
            text-decoration-style: wavy;
        }
    </style>
</head>
<body>
    <h1>This is an H1 heading with underline</h1>
    <h2>This is an H2 heading with overline</h2>
    <h3>This is an H3 heading with line-through</h3>
    <h4>This is an H4 heading with no decoration</h4>
    <h5>This is an H5 heading with both underline and overline</h5>
    <h2 class="special-heading">This is an H2 heading with custom red wavy underline</h2>
</body>
</html>
```

---

### 9. Set Rounded Border

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Rounded Border Example</title>
    <style>
        .rounded-box {
            border: 2px solid #ad4caf;
            border-radius: 15px;
            padding: 20px;
            width: 300px;
            text-align: center;
        }
        .circle-image {
            border: 3px solid #4f0000;
            border-radius: 50%;
            width: 150px;
            object-fit: cover;
        }
        .partially-rounded {
            border: 2px solid #0400ff;
            border-radius: 15px 50px;
            padding: 20px;
            width: 300px;
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="rounded-box">This box has fully rounded corners with a 15px radius.</div>
    <img src="abj.jpg" alt="Circular Image" class="circle-image">
    <div class="partially-rounded">This box has partially rounded corners with different radii.</div>
</body>
</html>
```

---

### 10. Display Different Cursor Types

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cursor Types Example</title>
    <style>
        .default-cursor {cursor: default;}
        .pointer-cursor {cursor: pointer;}
        .crosshair-cursor {cursor: crosshair;}
        .wait-cursor {cursor: wait;}
        .text-cursor {cursor: text;}
        .not-allowed-cursor {cursor: not-allowed;}
        .custom-cursor {cursor: url('images/image1.jpg'), auto;}
        .help-cursor {cursor: help;}
    </style>
</head>
<body>
    <p class="default-cursor">This paragraph has the default cursor.</p>
    <p class="pointer-cursor">This paragraph has a pointer cursor.</p>
    <p class="crosshair-cursor">This paragraph has a crosshair cursor.</p>
    <p class="wait-cursor">This paragraph has a wait cursor.</p>
    <p class="text-cursor">This paragraph has a text cursor.</p>
    <p class="not-allowed-cursor">This paragraph has a not-allowed cursor.</p>
    <p class="custom-cursor">This paragraph has a custom image cursor.</p>
    <p class="help-cursor">This paragraph has a help cursor.</p>
</body>
</html>
```

---

### 11. Indent First Line of Paragraphs

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>First Line Indent</title>
    <style>
        p {text-indent: 30px;}
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
        }
    </style>
</head>
<body>
    <p>Videography involves capturing moving images on electronic media, and can include streaming media. It encompasses both video production and post-production methods.</p>
    <p>The arrival of computers and the Internet expanded videography beyond traditional methods. With advances in technology, new tools like action cameras and mobile phones transform how videos are created and shared.</p>
</body>
</html>
```

---

### 12. Set Line Height in Percent

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Line Height Example</title>
    <style>
        p {
            font-size: 16px;
            line-height: 150%;
        }
        body {
            font-family: Arial, sans-serif;
        }
    </style>
</head>
<body>
    <p>This paragraph has a line height set to 150%. With a font size of 16px, the line height will be 1.5 times the font size, which equals 24px.</p>
    <p>Increasing the line height improves readability, especially for paragraphs with a lot of text.</p>
</body>
</html>
```

---

### 13. Z-Index Demonstration

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Z-Index Example</title>
    <style>
        .container {
            position: relative;
            width: 300px;
            height: 300px;
            border: 1px solid #000;
            margin: 20px auto;
        }
        .box1 {
            position: absolute;
            top: 50px;
            left: 50px;
            width: 150px;
            height: 150px;
            background-color: rgb(234, 0, 255);
            z-index: 1;
        }
        .box2 {
            position: absolute;
            top: 100px;
            left: 100px;
            width: 150px;
            height: 150px;
            background-color: rgb(81, 0, 0);
            z-index: 2;
        }
        .box3 {
            position: absolute;
            top: 150px;
            left: 150px;
            width: 150px;
            height: 150px;
            background-color: rgb(255, 157, 0);
            z-index: 3;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="box1">Box 1 (z-index: 1)</div>
        <div class="box2">Box 2 (z-index: 2)</div>
        <div class="box3">Box 3 (z-index: 3)</div>
    </div>
</body>
</html>
```

---

### 14. Rotate an Element Using CSS

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>CSS Rotation Example</title>
    <style>
        .container {
            text-align: center;
            margin-top: 50px;
        }
        .square {
            width: 100px;
            height: 100px;
            background-color: orange;
            margin: 0 auto;
            transition: transform 0.5s ease;
        }
        .square:hover {
            transform: rotate(45deg);
        }
        .circle {
            width: 100px;
            height: 100px;
            background-color: lightblue;
            border-radius: 50%;
            margin: 20px auto;
            transform: rotate(90deg);
        }
        .rotated-text {
            display: inline-block;
            margin-top: 20px;
            font-size: 18px;
            font-weight: bold;
            color: darkgreen;
            transform: rotate(-30deg);
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="square">Hover me!</div>
        <div class="circle"></div>
        <div class="rotated-text">Rotated Text</div>
    </div>
</body>
</html>
```

---

### 15. Client-Side Image Mapping

```html
<!DOCTYPE html>
<html>
<body>
    <h2>Image Maps</h2>
    <p>Click on the person, the glass, or the clover background to go to a new page and read more about the topic:</p>
    <img src="abj.jpg" alt="ENCORE" usemap="#workmap" width="400" height="379">
    <map name="workmap">
        <area shape="rect" coords="34,44,270,350" alt="Person" href="LINK1">
        <area shape="rect" coords="290,172,333,250" alt="Cup" href="LINK2">
        <area shape="circle" coords="337,300,44" alt="Background" href="LINK3">
    </map>
</body>
</html>
```

---


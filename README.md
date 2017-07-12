# mini-HTML-and-CSS-starter-template
**@abdalala**

When trying to experiment HTML and CSS component or you want to start a new small project, have a blank starter template on hand so you can play around in a clean sandbox environment for distraction-free experimentation.

## Instructions

You can create you own by following the steps below, or fork this repository and update the details below.

## Forking this repository 

1. open [mini-HTML-and-CSS-starter-template]() and click Fork at the right top side of the page.
2. Clone it to your local computer and update the title and author meta details below, then push back to your repository.
3. From now on, you want to build something copy and paste the folder rename it and start coding. Enjoy!

## To create your own

1. Create a directory called **mini-HTML-and-CSS-starter-template**. 
2. Within this directory create the following sub directories and file
    - **images** this will house all our images
    - **js** this will house our JavaScript files
    - **css** this will house our Css files
    - **index.html** our main html page
3. Within the **index.html** page lets put our empty HTML structure

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <title>mini-HTML-and-CSS-starter-template</title>
  <meta name="description" content="">
  <meta name="author" content="Abd Al-Ala Camara - tixibit.com">

  <!-- normalize CSS -->
  <link rel="stylesheet" href="css/normalize.css">
  
  <!-- External CSS our own css -->
  <link rel="stylesheet" href="css/main.css">
</head>
<body>
  <div class="site-wrapper">

      <!-- TODO CODE BELOW THIS LINE -->

  </div>

  <!-- JavaScript -->
  <script src="js/main.js"></script>
</body>
</html>
```


1. The first line is the doctype
2. The root html element with the language attribute
3. In the head element we have:
    - `meta charset="utf-8"` specify the character encoding for the HTML document
    - `meta http-equiv="X-UA-Compatible" content="IE=Edge"`  Use the following value to display the webpage in edge mode, which is the highest standards mode supported by Internet Explorer, from Internet Explorer 6 through IE11
    - `meta name="viewport"` gives the browser instructions on how to control the page's dimensions and scaling
    - `meta name="description"` Define a description of your web page/site - put the description for each problem set or so
    - `meta name="author"` Define the author of a page/site - you may put your own name here
    - normalize css: **normalize.css** makes browsers render all elements more consistently and in line with modern standards. It precisely targets only the styles that need normalizing.
    - our main css file: **main.css** will be our authored css for the problem set or so.

4. <!-- TODO CODE BELOW THIS LINE --> remove this HTML comment and start you code within the body

5. All javaScript at the bottom of the page


**Notes**:
- We are including two css files, we might not do this upon deploying the site to production (we would concatenate them in that kind of situation)

## Credits
Inspired by [Chen Hui Jing](https://www.chenhuijing.com)
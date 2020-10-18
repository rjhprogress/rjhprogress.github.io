#Installation
To view my Portfolio site visit: https://rjhprogress.github.io/

#Usage
On my Portfolio site you may download a copy of my resume, and view
a list of some of the coding projects I've done.

#Credits
- University of Pennsylvania: Penn LPS Coding Bootcamp Starter Code
- URL Image from https://www.gettyimages.com/
- Other images from Unsplash.com

#License
This Portfolio site is a personal project site and should not be copied

#Title: README.md
These files contain my portfolio which showcase some of my
personal projects, as well as work for clients.

Hyper Text Markup Language (HTML), and Cascading Style Sheets (CSS)
are two of the technologies used to design and development this
portfolio website.

The code started out as a basic HTML file highlighting relative paths with CSS.
Take a look at the original code here:
<code>
<!DOCTYPE html>
<html lang="en-us">
<head>
  <meta charset="UTF-8">
  <title>CSS Stylesheets with Relative Paths</title>
  <link rel="stylesheet" type="text/css" href="css/style.css">
</head>
<body>
  <header>
    <h1>Original Code:</h1>
  </header>
  <div class="container">
    <section id="main-bio">
      <h2>My Name</h2>
      <img id="bio-image" src="https://placehold.it/200x200" alt="My Name">
      <p>Short paragraph or two about self, or placeholder text from <a href="http://www.lipsum.com/">www.lipsum.com</a></p>
    </section>
    <section id="contact-info">
      <h2>Contact Info</h2>
      <ul>
        <li><strong>Email:</strong> <a href="#">someplace@gmail.com</a></li>
        <li><strong>Github:</strong> <a href="#">sampleName</a></li>
        <li><strong>Portfolio:</strong> <a href="#">coming soon</a></li>
      </ul>
    </section>
  </div>
    <h2>Original Code of style.css file</h2>

body {padding: 0;margin: 0;font-family: Georgia, "Times New Roman", Times, serif;font-size: 18px;
line-height: 150%;color: #333;background: #efeee7;} header {background: #333;} h1 {padding: 20px
0;margin: 0;margin-bottom: 20px;font-size: 28px;color: #eee;text-align: center;} h2 {font-size: 24px;}
a {color: #d21034;} .container {width: 1024px;margin: 0 auto;} #main-bio,#contact-info,#bio-image {float: left;}
#main-bio {width: 70%;} #contact-info {width: 30%;} #bio-image {width: 200px;height: 200px;margin-right: 20px;}
</body></html></code>

Changes Made:
 <br>
- Changed the font styling of the page from Georgia/Times New Roman/Times/serif to Source Sans Pro/sans-serif.<br>
- Moved the contact section to the naviation bar.<br>
- Removed Portfolio from "contacts" and made it a section where contacts used to be. <br>
- Added a drop down feature to the "Contact" link.<br>
- Added icon images to coinside with the links of the dropdown menu. <br>
- Added styling to the "h1" tag via style.css to center all headers. <br>
- Changed the color of the Navigation bar from #333 to #B1B4B<br>
- Changed logo to my name with a coding icon <br>
    -Added PDF download code for resume viewing under Training and Education<br>
- Added images and small description of each skill/ service I provide. <br>

Challenges Faced:
<br>
- Trouble setting footer to stay fixed at the bottom of the screen<br>
Solution:
Added fixed styling to the CSS file, add fixed code to the <br>
<code>
#ft {
position: fixed;
bottom: 0;
width: 100%;
height: 65px;
left: 0;
}
</code>

- Navigation and footer was responsive when the site scaled down to mobile size,
but the body section of the page didn't respond with the same flexibility.
Instead it would add an annoying footer slide bar that I felt took away from the
beautification of the page. <br>

Solution:
There were three bootstrap container classes applied to the code. I removed the
two (rom the "About Me" section, and the "Portfolio Section"), and kept the one
in the navigation. I then added padding, and margin styling in the css
to the body section. This made the entire page responsive the way I wanted.
<code>
body {
    padding-left: 50px;
    margin: 20px;
    font-family: 'Source Sans Pro', sans-serif;
    font-size: 18px;
    line-height: 150%;
    color: #000;
    background: #fff;
  }
</code>

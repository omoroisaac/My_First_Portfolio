0. Create the most basic, simple and valid HTML file called base_index.html

The page should contain:

a DOCTYPE
a head:
with a title
a body
Tips: don’t forget to read all concept pages…

Test the webpage with the official HTML Validator. You will see that it is not happy!

First things first, fix the code in base_index.html so that it is valid.

You will see that the validator then becomes much happier!

1. Copy your file base_index.html to index.html

Add in the body of the page:

at least 4 paragraphs;
headings (titles) of level 1, 2 and 3, which are represented by <h1>, <h2> and <h3> tags;
a clickable image of your choice (you can use this link https://i.ibb.co/gTDZZT8/ALX-Logo-07.png image, or another one you find on the internet by using its full URL); and it may link to any URL online that you want.

2. Copy your file base_index.html to tweets.html

Add in the body of the page:

embed at least one tweet (Here’s the official documentation from Twitter about embedding single tweets in a webpage’s HTML code.)
contain a link to your index.html webpage, for users who may go back to your homepage
In index.html, add a link to tweets.html, for users landing on your homepage, who want to see your tweets!

3. However, in order to start getting consistency throughout the website, all of the HTML files (index.html and tweets.html) must now have the same structure:

The <body> tag of all of your webpages must contain exactly three direct sub-tags in that order: <header>, <main> and <footer>
The <header> tag must contain an unordered list (the <ul> and <li> tags) of links (the <a> tag) to each of your webpages. As you may have understood, this will serve as a navigation for your website.
The <footer> tag must contain one paragraph with the sentence Made by <YOUR NAME> - <a href="<ANY LINK>" target="_blank">here</a>. The paragraph must be on a single line in your code (no line breaks), or the checker may fail.
The <main> tag must contain two direct sub-tags in that order: <article> and <aside>:
<article> contains the content of your webpage: texts, links, images, tweets, … This is the part of index.html and tweets.html that you have already written.
<aside> contains a single paragraph, just reading for now “placeholder to add comment thread later”.

4. Update your index.html to add a table with information about some of the learners.

On a new line before the last </article> tag, let’s introduce a container for the table of learners.

The bottom part of the <article> tag (before its closing tag) should contain a table <table> with the following structure:

Use the <thead> tag to define the table header row.
Use the <tbody> tag to contain the table data rows.
Populate the table with the following data:
Name	Age	Country
John	25	USA
Emily	28	Canada
Michael	32	Australia
Sophia	21	UK

5. Objective
Create a personal portfolio webpage that effectively showcases your skills, projects, and contact information.

Detailed Requirements
Create a Github repository named My_First_Portfolio if not already created and within it create a directory called portfolio

HTML File:

Create an HTML file within the portfolio directory and name your HTML file index.html.
Page Structure and Semantic HTML:

The document must start with the <!DOCTYPE html> declaration.
Use <html lang="en"> to define the document language.
The <head> section must contain <meta charset="utf-8"> and a <title> element with your full name followed by - Personal Portfolio (e.g., John Doe - Personal Portfolio).
The body of the document must include the following semantic HTML5 elements in order: <header>, <nav>, <section>, <article>, and <footer>.
Header:

The <header> must contain an <h1> element with your name.
Include a <p> tag beneath the <h1> with a brief tagline or professional statement.
Navigation Bar (<nav>):

Include a list of links (<ul> containing <li> elements) that allows navigation to the different sections of the webpage: Introduction, Projects, About Me, and Contact.
Each list item must contain an <a> tag with the href attribute pointing to the corresponding section ID (e.g., href="#projects" for the Projects section).
Content Sections:

Introduction Section (<section id="introduction">): Include an <h2> heading titled “Introduction” and a paragraph <p> describing yourself.
Projects Section (<section id="projects">): Use an <h2> heading titled “Projects”. Each project must be wrapped in <article> tags with a class of “project”. Each <article> must contain an <h3> for the project title, a <p> for the description, and an <a> tag linking to the project with target="_blank".
About Me Section (<section id="about">): Include an <h2> heading titled “About Me” and paragraphs or lists describing your background, skills, or hobbies.
Contact Section (<section id="contact">): Use an <h2> heading titled “Contact” and provide an email link using <a href="mailto:your.email@example.com"> and links to your LinkedIn and GitHub profiles, ensuring these links open in a new tab using target="_blank".
Footer:

The <footer> must contain a <p> element with copyright information (e.g., &copy; 2024 Your Name).
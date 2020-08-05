Homework Assignment 1
=====================

For this homework assignment I was tasked to refactor the HTML and CSS of an existing webpage to make it more accessible.
Below, I have included the acceptance criteria and a description of changes I made to fit each of the criteria. 
----------------------------------------------------------------------------------------------------------------

Per the acceptance criteria:
GIVEN a webpage meets accessibility standards

"WHEN I view the source code
THEN I find semantic HTML elements"

*lines 12 & 28, changed element to "header" element and removed header class which was no longer necessary.
*lines 15 & 27, updated to "nav" element as this is the navigation portion of the site.
*line 30, changed to "figure" element
*lines 32 & 54, updated to "section"
*lines 33-53, updated to "main" as they contain the main content of the website.
*lines 56 & 78, updated to "aside" element
*lines 57-77, updated "divs" to "articles" as each has independent, self contained information.
*lines 80 & 85 updated to footer element. 

"WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning"

Ensured that html elements followed a logical structure per https://webplatform.github.io/docs/guides/html_structural_elements/ with
*header at top, including navigation
*main content 
*aside section
*footer at the bottom

"WHEN I view the image elements
THEN I find accessible alt attributes"

*included alt attributes for all images included within html file and renamed figure class to be more accessible.

"WHEN I view the heading attributes
THEN they fall in sequential order"

*Ensured that headings fall in sequencial order

"WHEN I view the title element
THEN I find a concise, descriptive title"

*Updated title to company name

Contact info: jbenningfield.dev@gmail.com
![Homework](./assets/homework.PNG)



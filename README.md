Personal Portfolio Website

Project Description

This project is a personal portfolio website created for INFR3120 Web and Scripting Programming.

The website was built using HTML5 and CSS3. It includes four separate pages:

Home
About Me
Projects
Contact Me

The website also includes responsive design, a contact form, an introductory video, semantic HTML elements, gradients, and separate CSS files for different screen sizes.

---

Website Pages

Home Page
The home page welcomes visitors to my portfolio and provides navigation to the other pages.

About Me Page
The About Me page contains a personal photo, a short introduction about me, and a 45–60 second introductory video.

The video uses the HTML5 video element with controls and a poster image.

Projects Page
The Projects page contains five projects that I have worked on or studied.

Each project includes a heading and a short description.

Contact Me Page
The Contact Me page includes a form containing:

Name
Email
Cell number
Comments
Submit button

HTML validation rules are used for required fields, email addresses, and phone numbers.

---

Responsive Design

The website uses separate CSS files for mobile, tablet, and laptop/desktop devices.

Mobile
Screen width: 600px or smaller

File used:

`mobile.css`

The mobile layout uses smaller font sizes, reduced padding, narrower content areas, and navigation links displayed vertically.

Tablet
Screen width: 601px to 1024px

File used:

`tablet.css`

The tablet layout uses slightly larger text and spacing than the mobile version while keeping the content responsive.

Laptop/Desktop
Screen width: 1025px and larger

File used:

`laptop.css`

The laptop layout uses larger text, additional spacing, and a wider main content area.

These viewport sizes were chosen so the website can adjust to common mobile, tablet, and desktop screen sizes.

---

Fluid Design

The website uses percentage-based widths such as 90%, 92%, and 95% so that the content can adjust based on the size of the browser window.

Images and videos also use a maximum width of 100% so they do not overflow their containers.

---

Gradients

Two types of linear gradients are used in the website.

Standard Linear Gradient

A standard linear gradient is used in the header:

`linear-gradient(#1f3c5b, #2f5f8f)`

It creates a transition between two shades of blue.

Angled Linear Gradient

An angled linear gradient is used in the footer:

`linear-gradient(135deg, #1f3c5b, #2f5f8f)`

The 135-degree angle creates a diagonal color transition.

---

Color Scheme

The website uses a blue, white, light gray, and dark gray color scheme.

Main colors include:

Dark Blue: `#1f3c5b`
Medium Blue: `#2f5f8f`
White: `#ffffff`
Light Gray: `#f4f4f4`
Dark Gray: `#222222`

The blue colors are mainly used for the header, footer, and submit button. White is used for the content sections, while gray colors are used for the background and text.

---

Semantic HTML

Semantic HTML5 elements are used throughout the website, including:

`<header>`
`<nav>`
`<main>`
`<section>`
`<footer>`

These elements help organize the content and make the structure of the website easier to understand.

---

HTML5 Features

The project uses HTML5 features including:

Semantic HTML elements
HTML5 video
Form validation
Email input validation
Telephone number validation
Required form fields

---

Project Structure

The project is organized using the following structure:

portfolio/
    index.html
    bout.html
    projects.html
    contact.html
    README.md
css/
    main.css
    mobile.css
    tablet.css
    laptop.css
images/
    profile.jpeg
    video-poster.jpg
videos/
    intro.mp4

---

Code Sources

The HTML and CSS used in this project were written for this assignment using concepts taught in the INFR3120 course lectures.

Any external code used in the project should be listed and cited in this section.
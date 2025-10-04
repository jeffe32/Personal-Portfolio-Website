Assignment 1 for INFR3120 - Web and Scripting Programming

The goal of this assignment was to create an Personal Portfolio Website using HTML5 and CSS3.
Also adding and demonstrating responsive design, semantic HTML, and proper structure.

This Personal Portfolio Website is deployed using GitHub Pages and it includes four main pages
they are:

- Home Page
- About Me Page
- Project Page
- Contact Me Page

File Structure contains:

- index.html --> This is the Home Page (navigation menu, welcome content, and footer)
- aboutMe.html --> This includes personal photo, short introduction, and an introduction video with poster and controls
- projects.html --> This displays 4-5 projects with titles and also short description of the projects
- contactMe.html --> This contains a functional contact form with input validation (Name, Email, Phone, Comments)
- styles.css --> Main stylesheet for styling
- mobile.css --> CSS for mobile viewports
- tablet.css --> CSS for tablet viewports
- laptop.css --> CSS for laptop and desktop viewports
- README.md --> Documentation file (this file)

Features

1. Site structure & Functionality

- Navifation bar there on all pages, linking to about me, projects, and also contact me
- About Me Page:
	- Displays a profile photo
	- Short personal introduction
	- 46 second introduction video (on_record.mp4) with a poster image
	  (on_record.png) and video controls

- Projects page:	
	- This contains 5 projects titles with 2-3 sentence descriptions

- Contact Me page:
	- Functional form with fields: Name, Email, Phone Number, Comments
	- Input vaildation for required field (email format, numeric phone input, etc.)

- Footer:
	- This contains contact email
	- Contains copyright


2. GUI & Interface

Responsiveness (viewports)

- Mobile (≤767px):
	- This size is used for smartphones. Where the screens are small and content needs to be stacked
	  vertically.
	- This viewport ensures that it easy navigation with the larger buttons and also the
	  single-column layout for the readability.
	- Why I used 767px and below because 767px is a common cutoff for smartphones since most of the 
	  modern mobile devices fall below 768px in width.

- Tablet (768px-1024px)
	- Used for mid-size devices
	- The layout for this viewport uses more spacing and also two-column arrangements when appropriate,
	  balancing readbility and space usage.
	- Why I used 768px to 1024px range is becuase this is the standard width for an iPad
	  in portrait mode, and also the 1024px is the width in the landscape mode therfore
	  this range covers most tablets.

- Laptop/Desktop (≥1025px):
	- Used for larger screens where the users expect full-width layouts and more professional
	  spacing.
	- This version allows for content to be spread out tihe the centered sections which in turn
	  providing a more polished desktop experience.
	- Why I used 1025px and above is because it typically that is the px of a laptop and a desktop
	  display. Because anything that is larger than 1024px is generally means that the user
	  has a full keyboard and mouse setup or ratherthan touch.

Overall this Responsiveness ensures that my portfolio is user-friendly across devices, and its
optimized for the most common screens.

Gradients:
	- A linear gradient was used for the About Me page box for a modern look and also to
	  to make the introduction stand out.
	- Linear gradient were also applied to each of the project box on the Projects Page
	  giving them a uniform but also making it visually appealing style.
	- In the Contact Page. The wrapper background uses a gradient to separate the form area
	  from the rest of the content.

Types of gradient used:
	- linear-gradient
	- -webkit-linear-gradient
	- -moz-linear-gradient

Color Scheme used:
	- Blue - used for the text "Kanth" and "Cybersecurity"
	- Mixed of pink and gold used for the wrapper in About Me and the Contact Me
	- White - Used for the main content area to keep everything clean
	- Black used mostly for maximum contrast and accessibility.
	- Mixed of blue and light blue used for box 1 and box 2 in Projects Page
	- Mixed of pink and golden yellow for box 3 in Projects Page
	- Mixed of navy blue and purple for box 4 and box 5 in Projects Page

Testing & Validation

The website was tested and availdated using the tools provided:
- HTML Validation: W3C HTML Validator
	- Obsolete background and color attributes on <hr>
	- Error: Attribute background not allowed on element hr at this point.

- CSS Validation: W3C CSS Validator 
	- No major errors. Minor vendor-prefix warnings (-webkit-, -moz-) are acceptable for browser 
	  compatibility.

- Link Validation: W3C Link Checker 
	- All internal links and navigation links were tested and validated. 
	  No broken links found.

- Spelling
	- Checked with Grammarly (Free version)

- Accessiblity: Tested with WAVE Web Accessibility Tool
	- 2 contrast errors
	- 1 Alerts

External Code Sources
	- Google Fonts - Lexend Deca https://fonts.google.com/

Deployment
	- Live Website: https://jeffe32.github.io/Personal-Portfolio-Website/
	- Repository Link: https://github.com/jeffe32/Personal-Portfolio-Website

Author: Kanth Manotheepan
	- Ontario Tech University
	- INFR3120 – Web and Scripting Programming


	


	




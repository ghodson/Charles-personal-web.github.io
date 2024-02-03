# TITLE: CHARLSE COMPLETED PORTFOLIO WEB APPLICATION

## DESCRIPTION: ** This is my school portfolio project as a web app developer to demonstrate my understanding of basic web technologies, such as; CSS _(Cascading Style Sheets used for styling this web application layouts)_ and HTML _( Hypertext Markup Language which functions as the skeletal framework of this web application)_. **

# TECHNOLOGIES USED:

- HTML
- CSS

# svg icons source: https://www.svgrepo.com/

# HOW TO USE THIS PROJECT: ** After cloning this repository from my GitHub account to your local machine, then open the folder content of the project using VSCcode _(Visual Studio Code)_, download the live server extension and click on the live server icon (indicated with _Go Live_) located in the VSCcode icon tray to spin up the local server in the browser **

# CODE-BASE BREAKDOWN: ** The comments utilized both in HTML and CSS of this project will help to give a clear functionality of what each code block does **

## BODY: \*\*\* The body tag of this project contains two major children elements which are the header and main tag and this was done to attain simplicity in code readability.

## HEADER: \*\*\* The header tag contains the necessary navigations for this page, including the social handle links and the internal links that target respective #id's

## MAIN: \*\*\* The main tag contains both my image and description of the services I offer while having the major focus on web app development as my core profession

**HTML STRUCTURE (Index.html)**

**The Header:**
The header section of this portfolio website includes the name of the website and social media link for easy navigation

**MAIN CONTENT:**

**Hero Section:**
A visual hero section has a brief description of me with a photo of me aligned to the left

**About Me Section:**
This section has a detailed description of me and my passion for A&R and my vision of the tech industry

**Skills And Services Sections**:
This section highlights my skills and the services I offer, and this is presented in a clean and organized format

**Contact Section:**
This section displays my contact details, my phone number and email addresses for easy communication

**CSS DESIGN (styles/index.css)**

**Global Styling:**
Universal styling rules are applied, including resetting padding, margin, and box-sizing and custom variables define the colour theme used throughout the website (`--BG:` `--TEXT:` `--INNER-BG:`) These custom variables were used to design the websites. - The `*` selector resets padding, margin, and box-sizing for all elements. - Custom variables are defined in `: root` for colour theming. - `html` has `scroll-behavior: smooth` for smooth scrolling.

**Element Styling:**
A specific style was applied to the body, header, and navigation elements and links are styled for better visibility and interaction. - Styling for `body` includes background images, font, and colour settings. - `header` is set to sticky with a radial gradient background. - Navigation (`nav`) styles include grid layout and link styling. - Links (`nav ul li a`) have border-radius, border style, and padding.

**Class Styling:**
Various sections and elements are se=tyled with specific classes to achieve a cohesive and visually appealing layout and hover effects are applied to service and skill sections for user interactions. - `.link-style` defines common styles for links used throughout the document. - `.fig-caption` styles are applied to figure captions. - `.section-name-style` styles the header section containing the website name and social media links. - `.article-intro-style` styles introductory text articles. - `.line` defines a decorative line. - `.photo-and-content-style` styles the layout of photo and content sections. - `.hero-content` sets minimum height and width for the hero section. - `.photo-content` styles the photo content section. - `.about-style`, `.skill-style`, `.service-style`, and `.contact-style` style various sections of the website. - `.flexer` styles a flex container for arranging content. - Hover effects are applied to `.service-style` and `.skill-style` on hover.

**Utility Class Styles:**
`.center-content-row` and `.center-content-column` are utility classes for flex container alignment.

**Media Queries:**
Responsive design is implemented with media queries, adjusting styles for screens with a minimum width of 764px, navigation and layout adjustments are made for larger screens.

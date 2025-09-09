Interactive 3D Portfolio
An immersive, Netflix-inspired personal portfolio website built as a single-page application. This project presents a resume not as a static document, but as an interactive journey through a 3D galaxy, where each section is a world to explore.

Live Demo
(You can add your GitHub Pages link here once deployed)

Features
Immersive 3D Experience: Navigate a "galaxy" of custom 3D objects representing different resume sections.

Netflix-Inspired UI: A clean, dark-themed interface inspired by the popular streaming service.

Dynamic Universe: Features an animated nebula background, a starfield, ambient galaxy rotation, and a sparkling "stardust" mouse trail.

Seamless Animations: Smooth GSAP-powered "fly-through" animations transition between the galaxy view and detailed content sections.

Fully Responsive: Adapts to all screen sizes, with dedicated touch-swipe and arrow controls for mobile navigation.

Easily Customizable: All personal data (work experience, education, skills, etc.) is managed from a single JavaScript object for easy updates.

Technologies Used
Three.js: For the core 3D rendering and scene management.

GSAP (GreenSock Animation Platform): For all camera animations and UI transitions.

Tailwind CSS: For modern, responsive styling.

HTML, CSS, & JavaScript: The foundational web technologies.

Setup & Customization
This project is a self-contained single-page application with no build process required.

Running Locally
Clone the repository.

Open the index.html file in your web browser. A live server extension in your code editor is recommended to avoid any potential CORS issues.

Customizing The Content
All personal information is stored in the dummyData JavaScript object within the <script type="module"> tag in index.html. To add your own information:

Open index.html in a text editor.

Locate the dummyData object inside the main <script> tag.

Edit the content for each section (about, experience, education, projects, skills) with your own details.

Update the contactLinks object with your personal social media and email links.

Change the name in the header and footer to your own.

License
This project is licensed under the MIT License. See the LICENSE file for details.

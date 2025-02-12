# Ridam
/portfolio
   |-- index.html
   |-- style.css
   |-- script.js
   |-- images/
   <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ridam Bhardwaj | Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <script defer src="script.js"></script>
</head>
<body>
    <header>
        <h1>Ridam Bhardwaj</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="hero">
        <h2>Creative Developer & Photographer</h2>
        <p>Building modern, visually appealing, and functional websites.</p>
    </section>

    <section id="about">
        <h2>About Me</h2>
        <p>I'm Ridam Bhardwaj, a passionate Software Developer and Website Creator currently pursuing BCA at Galgotias University. Skilled in HTML, CSS, JavaScript, and C Programming.</p>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>HTML, CSS, JavaScript</li>
            <li>C Programming</li>
            <li>Photography & Editing</li>
        </ul>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Food Ordering System</h3>
            <p>A web-based food ordering system created as part of my BCA Semester 1 project.</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: <a href="mailto:ridambhardwaj4@gmail.com">ridambhardwaj4@gmail.com</a></p>
        <p>Social Media: <a href="https://instagram.com/ridam_bhardwaj" target="_blank">@ridam_bhardwaj</a></p>
    </section>

    <footer>
        <p>© 2025 Ridam Bhardwaj. All rights reserved.</p>
    </footer>
</body>
</html>
/* Dark Theme Styling */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background: #121212;
    color: #ffffff;
}

header {
    background: #1f1f1f;
    padding: 15px;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #ffffff;
    text-decoration: none;
}

#hero {
    text-align: center;
    padding: 50px 20px;
    background: #282828;
}

h2 {
    color: #00ffcc;
}

section {
    padding: 20px;
    text-align: center;
}

.project {
    background: #333;
    padding: 15px;
    margin: 10px auto;
    width: 60%;
    border-radius: 5px;
}

footer {
    text-align: center;
    padding: 10px;
    background: #1f1f1f;
    margin-top: 20px;
}
document.addEventListener("DOMContentLoaded", function() {
    console.log("Portfolio loaded successfully!");
});

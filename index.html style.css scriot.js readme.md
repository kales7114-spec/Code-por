<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Sunil Kale Portfolio</title>
    <link rel="stylesheet" href="my.css">
</head>
<body>

<header>
    <h1>Sunil Kale</h1>
    <p>Frontend Web Developer</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <h2>About Me</h2>
    <p>
        I am a web developer skilled in HTML, CSS, and JavaScript.
        I create responsive and user-friendly websites.
    </p>
</section>

<section id="skills">
    <h2>Skills</h2>
    <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
        <li>Responsive Design</li>
    </ul>
</section>

<section id="projects">
    <h2>Projects</h2>
    <div class="project">
        <h3>Movie & Series Website</h3>
        <p>Legal movie info website with trailers and categories.</p>
    </div>
    <div class="project">
        <h3>Portfolio Website</h3>
        <p>Personal responsive portfolio using HTML, CSS & JS.</p>
    </div>
</section>

<section id="contact">
    <h2>Contact Me</h2>
    <form onsubmit="sendMessage(); return false;">
        <input type="text" id="name" placeholder="Your Name" required>
        <input type="email" id="email" placeholder="Your Email" required>
        <textarea id="message" placeholder="Your Message" required></textarea>
        <button type="submit">Send</button>
    </form>
</section>

<footer>
    <p>© 2026 Sunil Kale</p>
</footer>

<script src="script.js"></script>
</body>
</html>

body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #111;
    color: #fff;
}

header {
    background: #e50914;
    text-align: center;
    padding: 20px;
}

nav {
    background: #000;
    text-align: center;
    padding: 10px;
}

nav a {
    color: white;
    margin: 0 15px;
    text-decoration: none;
    font-weight: bold;
}

section {
    padding: 30px;
    max-width: 900px;
    margin: auto;
}

h2 {
    color: #e50914;
}

ul li {
    margin: 8px 0;
}

.project {
    background: #222;
    padding: 15px;
    margin: 15px 0;
    border-radius: 8px;
}

form input, form textarea {
    width: 100%;
    padding: 10px;
    margin: 8px 0;
    border-radius: 5px;
    border: none;
}

form button {
    background: #e50914;
    color: white;
    padding: 10px;
    border: none;
    width: 100%;
    cursor: pointer;
    border-radius: 5px;
}

footer {
    background: #000;
    text-align: center;
    padding: 10px;
}
function sendMessage() {
    alert("Thank you! Your message has been sent.");
}

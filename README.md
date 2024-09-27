<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sagar Sharma - Portfolio</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f4f4f4;
            color: #333;
            text-align: center;
        }
        /* Typewriter effect */
        .typewriter h1 {
            font-size: 2.5rem;
            font-weight: bold;
            overflow: hidden;
            border-right: .15em solid orange;
            white-space: nowrap;
            margin: 0 auto;
            letter-spacing: .15em;
            animation: typing 3.5s steps(30, end), blink-caret 0.75s step-end infinite;
        }
        @keyframes typing {
            from { width: 0 }
            to { width: 100% }
        }
        @keyframes blink-caret {
            from, to { border-color: transparent }
            50% { border-color: orange }
        }
        ul {
            list-style-type: none;
        }
        li::before {
            content: "✨ "; /* Attractive bullet icon */
            font-size: 1.5rem;
        }
        a {
            text-decoration: none;
            color: orange;
        }
        a:hover {
            color: #ff9933;
        }
    </style>
</head>
<body>

    <!-- Heading with Typewriter Effect -->
    <div class="typewriter">
        <h1>Hi 👋, I'm Sagar Sharma</h1>
    </div>

    <!-- Personal Details -->
    <ul>
        <li>🔭 I’m currently working on <strong>PHP</strong></li>
        <li>🌱 I’m currently learning <strong>Laravel</strong></li>
        <li>📫 How to reach me: <strong>sharmasagar1961@gmail.com</strong></li>
        <li>⚡ Fun fact: <strong>I think I am Funny</strong></li>
    </ul>

    <!-- Connect with me Section -->
    <h3 align="left">Connect with me:</h3>
    <p align="left">
        <a href="https://linkedin.com/in/sagar-sharma-160b96269" target="blank">
            <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="40" />
        </a>
    </p>

    <!-- Languages and Tools Section -->
    <h3 align="left">Languages and Tools:</h3>
    <p align="left">
        <a href="https://getbootstrap.com" target="_blank" rel="noreferrer">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="Bootstrap" width="40" height="40" />
        </a>
        <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3" width="40" height="40" />
        </a>
        <a href="https://www.figma.com/" target="_blank" rel="noreferrer">
            <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="Figma" width="40" height="40" />
        </a>
        <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5" width="40" height="40" />
        </a>
        <a href="https://laravel.com/" target="_blank" rel="noreferrer">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQMoO1kQEm6tKiQbd-moXfnmzFakSSyYPpdIw&s" alt="Laravel" width="40" height="40" />
        </a>
        <a href="https://www.mysql.com/en" target="_blank" rel="noreferrer">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL" width="40" height="40" />
        </a>
        <a href="https://www.photoshop.com/en" target="_blank" rel="noreferrer">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/photoshop/photoshop-line.svg" alt="Photoshop" width="40" height="40" />
        </a>
        <a href="https://www.php.net" target="_blank" rel="noreferrer">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="PHP" width="40" height="40" />
        </a>
        <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer">
            <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="Tailwind" width="40" height="40" />
        </a>
    </p>

</body>
</html>

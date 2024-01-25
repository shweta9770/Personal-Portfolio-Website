<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Your Name - Portfolio</title>
</head>
<body>

    <header>
        <div class="container">
            <h1>Your Name</h1>
            <p>Web Developer | Designer</p>
        </div>
    </header>

    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <p>Welcome to my portfolio! I am a passionate web developer and designer with a focus on creating user-friendly and visually appealing websites.</p>
        </div>
    </section>

    <section id="projects">
        <div class="container">
            <h2>Projects</h2>

            <!-- Example project card, repeat as needed -->
            <div class="project-card">
                <h3>Project Title</h3>
                <p>Description of the project. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                <a href="#">View Project</a>
            </div>

        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <p>Feel free to reach out to me. I am open to collaboration and new opportunities.</p>
            <p>Email: your.email@example.com</p>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Your Name. All rights reserved.</p>
        </div>
    </footer>

</body>
</html>
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.container {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 30px 0;
}

header h1 {
    margin: 0;
}

header p {
    margin: 10px 0;
}

section {
    margin: 40px 0;
}

h2 {
    color: #333;
}

project-card {
    background-color: #f9f9f9;
    padding: 20px;
    margin: 10px 0;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}


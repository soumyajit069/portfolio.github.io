# portfolio.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Home | My Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="projects.html">Projects</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
    <h1>Welcome to My Portfolio</h1>
    <p>I am a Web Developer, Designer, and Tech Enthusiast.</p>
  </header>

  <main>
    <section>
      <h2>Introduction</h2>
      <p>Explore my work, projects, and skills. Let's connect!</p>
    </section>
  </main>

  <footer>
    <p>© 2024 Your Name | Email: your.email@example.com</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About | My Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="projects.html">Projects</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
    <h1>About Me</h1>
  </header>

  <main>
    <section>
      <h2>Who Am I?</h2>
      <p>I am a passionate web developer with experience in front-end and back-end technologies. I love creating user-friendly, responsive websites.</p>
    </section>
  </main>

  <footer>
    <p>© 2024 Your Name | Email: your.email@example.com</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Projects | My Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="projects.html">Projects</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
    <h1>My Projects</h1>
  </header>

  <main>
    <section>
      <h2>Project 1</h2>
      <p>Brief description of Project 1.</p>
    </section>

    <section>
      <h2>Project 2</h2>
      <p>Brief description of Project 2.</p>
    </section>

    <section>
      <h2>Project 3</h2>
      <p>Brief description of Project 3.</p>
    </section>
  </main>

  <footer>
    <p>© 2024 Your Name | Email: your.email@example.com</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact | My Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="projects.html">Projects</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
    <h1>Contact Me</h1>
  </header>

  <main>
    <section>
      <h2>Get in Touch</h2>
      <form action="#">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="5" required></textarea>

        <button type="submit">Send</button>
      </form>
    </section>
  </main>

  <footer>
    <p>© 2024 Your Name | Email: your.email@example.com</p>
  </footer>
</body>
</html>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  line-height: 1.6;
  background-color: #f4f4f4;
  color: #333;
}

header {
  background-color: #00539C;
  color: #fff;
  padding: 1rem;
  text-align: center;
}

nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
}

nav ul li {
  margin: 0 1rem;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
}

h1, h2 {
  margin: 1rem 0;
  text-align: center;
}

main {
  padding: 2rem;
  text-align: center;
}

form {
  display: flex;
  flex-direction: column;
  width: 300px;
  margin: 0 auto;
}

form label, form input, form textarea {
  margin-bottom: 1rem;
}

form button {
  background-color: #00539C;
  color: #fff;
  border: none;
  padding: 0.5rem;
  cursor: pointer;
}

footer {
  text-align: center;
  padding: 1rem;
  background-color: #333;
  color: #fff;
}

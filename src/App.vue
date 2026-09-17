<template>
  <div class="portfolio">
    <header class="navbar">
      <h1>Jerelyn Adella</h1>

      <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <main>
      <section id="home" class="hero">
        <p class="intro">Hello, I'm</p>
        <h2>Jerelyn Teves Adella</h2>
        <p>
          An Information Systems student interested in web development,
          technology, and creating useful digital solutions.
        </p>
      </section>

      <section id="about">
  <h2>About Me</h2>
  <p>
    I am an Information Systems student with an interest in web development,
    technology, and creating practical digital solutions. I enjoy learning
    new technologies and applying them to projects that are useful and
    user-friendly.
  </p>
</section>

      <section id="skills">
        <h2>Skills</h2>
        <ul>
          <li>HTML</li>
          <li>CSS</li>
          <li>JavaScript</li>
          <li>Vue.js</li>
          <li>Git and GitHub</li>
        </ul>
      </section>

      <section id="projects">
        <h2>Projects</h2>

        <div class="project">
          <h3>Personal Portfolio</h3>
          <p>
            A personal portfolio website created using Vue.js and Vite.
          </p>
        </div>
      </section>

      <section id="contact">
        <h2>Contact</h2>
        <p>Thank you for visiting my portfolio.</p>
      </section>
    </main>
  </div>
</template>

<style>
* {
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #f5f7fa;
  color: #222;
}

.portfolio {
  min-height: 100vh;
}

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 60px;
  background: #0b2e6d;
  color: white;
  position: sticky;
  top: 0;
  z-index: 10;
}

.navbar h1 {
  margin: 0;
  font-size: 24px;
}

.navbar nav {
  display: flex;
  gap: 25px;
}

.navbar a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

.navbar a:hover {
  text-decoration: underline;
}

main {
  max-width: 1000px;
  margin: 0 auto;
}

section {
  padding: 80px 30px;
}

.hero {
  min-height: 80vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.hero h2 {
  font-size: 48px;
  margin: 10px 0;
  color: #0b2e6d;
}

.intro {
  font-size: 20px;
  margin: 0;
}

section h2 {
  color: #0b2e6d;
  margin-bottom: 20px;
}

ul {
  padding-left: 25px;
}

li {
  margin-bottom: 10px;
}

.project {
  background: white;
  padding: 25px;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.08);
}

.project h3 {
  margin-top: 0;
  color: #0b2e6d;
}

@media (max-width: 700px) {
  .navbar {
    flex-direction: column;
    gap: 15px;
    padding: 20px;
  }

  .navbar nav {
    gap: 12px;
    flex-wrap: wrap;
    justify-content: center;
  }

  section {
    padding: 60px 20px;
  }

  .hero h2 {
    font-size: 36px;
  }
}
</style>
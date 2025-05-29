
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Airah Nicolei delos Reyes</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background-color: #f5f7fa;
      color: #333;
      line-height: 1.6;
    }

    header {
      background-color: #dcebf7;
      padding: 2rem;
      text-align: center;
    }

    .avatar-header {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 3px solid #fff;
      object-fit: cover;
      margin-bottom: 1rem;
    }

    h1 {
      font-size: 2rem;
    }

    .tagline {
      font-style: italic;
      color: #555;
    }

    nav {
      background: #003366;
      padding: 1rem;
    }

    nav ul {
      display: flex;
      justify-content: center;
      list-style: none;
    }

    nav li {
      margin: 0 1rem;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    main {
      max-width: 900px;
      margin: 2rem auto;
      padding: 1rem;
      background: white;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
    }

    section {
      margin-bottom: 2rem;
    }

    .profile-img {
      width: 150px;
      border-radius: 50%;
      display: block;
      margin: 1rem auto;
    }

    .gallery {
      display: flex;
      gap: 1rem;
      flex-wrap: wrap;
    }

    .gallery img {
      width: 100%;
      max-width: 300px;
      border-radius: 8px;
      object-fit: cover;
    }

    footer {
      text-align: center;
      padding: 1rem;
      background: #003366;
      color: white;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <img src="images/avatar.jpg" alt="Avatar" class="avatar-header">
    <h1>Airah Nicolei delos Reyes</h1>
    <p class="tagline">BS Entrepreneurship Student | Baker | Nature Lover | Artist</p>
  </header>

  <nav>
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <main>
    <section id="about">
      <h2>About Me</h2>
      <img src="images/Avatar.jpg" alt="Profile Picture" class="profile-img">
      <p>Hello! I’m Airah Nicolei delos Reyes, a first-year BS Entrepreneurship student at Mariano Marcos State University. I’m passionate about learning how to start and manage businesses, and I enjoy taking risks when it comes to exploring new opportunities. I have a strong interest in baking, nature photography, and creating art, which I often combine with my business ideas. I’m a creative and curious individual who loves turning small ideas into meaningful projects. Whether it’s designing a product, capturing nature’s beauty through my camera, or experimenting with new recipes, I always bring enthusiasm and attention to detail. My goal is to keep growing as an entrepreneur while doing the things I love.</p>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <h3>SweetBox Brownie Shop</h3>
      <div class="gallery">
        <img src="images/Brownies.jpg" alt="Brownies">
        <img src="images/Brownie_flavors.jpg" alt="Brownie Flavors">
      </div>
      <p>A simple page I created to showcase my small brownie business. It includes a photo of my homemade brownies and a short description of the different flavors I offer.</p>

      <h3>Nature Photography Gallery</h3>
      <div class="gallery">
        <img src="images/Nature.jpg" alt="Nature">
        <img src="images/Sea.jpg" alt="Sea">
      </div>
      <p>A photo gallery that displays some of my favorite nature shots. This project shows my love for nature and photography in a simple and organized layout that looks good on both phones and computers.</p>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>Email: <a href="mailto:airahnicoleidelosreyes@gmail.com">airahnicoleidelosreyes@gmail.com</a></p>
      <p>Phone: 0960-913-9158</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Airah Nicolei delos Reyes. All rights reserved.</p>
  </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <meta name="description" content="Tennis for All - Learn, Play, Compete."/>
  <title>Tennis for All</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f8f8f8;
      color: #333;
    }

    header {
      background-color: #00529B;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav ul {
      display: flex;
      justify-content: center;
      list-style: none;
      padding: 0;
      background-color: #003d73;
      margin: 0;
      flex-wrap: wrap;
    }

    nav ul li {
      margin: 10px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    nav ul li a:hover {
      text-decoration: underline;
    }

    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }

    h2 {
      border-bottom: 3px solid #ccc;
      padding-bottom: 10px;
      color: #00529B;
    }

    img {
      max-width: 100%;
      height: auto;
      margin: 20px 0;
    }

    figcaption {
      font-size: 0.9em;
      color: #555;
    }

    .gallery-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
    }

    table, th, td {
      border: 1px solid #999;
    }

    th, td {
      padding: 10px;
      text-align: left;
    }

    form {
      display: flex;
      flex-direction: column;
      gap: 10px;
      max-width: 500px;
    }

    label {
      font-weight: bold;
    }

    input, textarea {
      padding: 8px;
      font-size: 1em;
    }

    input[type="submit"] {
      background-color: #00529B;
      color: white;
      border: none;
      cursor: pointer;
      padding: 10px;
    }

    input[type="submit"]:hover {
      background-color: #003d73;
    }

    footer {
      background-color: #00529B;
      color: white;
      text-align: center;
      padding: 15px;
    }

    .nested-list ul {
      margin-left: 20px;
    }

    iframe {
      width: 100%;
      height: 360px;
      margin-top: 20px;
    }
  </style>
</head>
<body>

<header>
  <h1>Tennis for All</h1>
</header>

<nav>
  <ul>
    <li><a href="#home">Home</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#learn">Learn</a></li>
    <li><a href="#events">Events</a></li>
    <li><a href="#gallery">Gallery</a></li>
    <li><a href="#join">Join Us</a></li>
  </ul>
</nav>

<!-- HOME -->
<section id="home">
  <h2>Welcome to Tennis for All</h2>
  <p>Explore everything from tennis history and tips to tournaments and local events.</p>
  <figure>
    <img src="https://images.unsplash.com/photo-1618675522211-5cfb216f29a3" alt="Tennis racket and balls on court">
    <figcaption>Tennis is for everyone — just grab a racket and start!</figcaption>
  </figure>
</section>

<!-- ABOUT -->
<section id="about">
  <h2>About Tennis</h2>
  <p>Tennis is a sport enjoyed by millions. It's great for fitness, focus, and fun.</p>
  <ul>
    <li>Top 5 Players:
      <ol>
        <li>Novak Djokovic</li>
        <li>Roger Federer</li>
        <li>Serena Williams</li>
        <li>Rafael Nadal</li>
        <li>Coco Gauff</li>
      </ol>
    </li>
  </ul>
  <figure>
    <img src="https://images.unsplash.com/photo-1584985845436-8e1520f1f6c6" alt="Players shaking hands at net">
    <figcaption>Sportsmanship is a key part of tennis.</figcaption>
  </figure>
</section>

<!-- LEARN -->
<section id="learn">
  <h2>Learn to Play</h2>
  <p>Start with the basics:</p>
  <div class="nested-list">
    <ul>
      <li>Serving
        <ul>
          <li>Overhand</li>
          <li>Underhand</li>
        </ul>
      </li>
      <li>Scoring
        <ul>
          <li>Love, 15, 30, 40</li>
          <li>Deuce and Advantage</li>
        </ul>
      </li>
    </ul>
  </div>
  <iframe 
    src="https://www.youtube.com/embed/o6PKMIzH0G8" 
    title="Learn Tennis - How to Play" 
    allowfullscreen 
    aria-label="Tennis basics video tutorial">
  </iframe>
  <figcaption>Video: Learn Tennis Basics (YouTube)</figcaption>
</section>

<!-- EVENTS -->
<section id="events">
  <h2>Upcoming Events</h2>
  <table>
    <thead>
      <tr>
        <th>Event</th>
        <th>Location</th>
        <th>Date</th>
        <th>Level</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Wimbledon</td>
        <td>London</td>
        <td>July 2025</td>
        <td>Professional</td>
      </tr>
      <tr>
        <td>Local Club Match</td>
        <td>Bogotá</td>
        <td>August 3</td>
        <td>Amateur</td>
      </tr>
    </tbody>
  </table>
  <figure>
    <img src="https://images.unsplash.com/photo-1517649763962-0c623066013b" alt="Grass court match">
    <figcaption>Grass court tennis — iconic and fast-paced!</figcaption>
  </figure>
</section>

<!-- GALLERY -->
<section id="gallery">
  <h2>Photo Gallery</h2>
  <div class="gallery-grid">
    <figure>
      <img src="https://images.unsplash.com/photo-1617727553256-3c3f8ed0d8d5" alt="Junior tennis player">
      <figcaption>Youth match — future stars in action.</figcaption>
    </figure>
    <figure>
      <img src="https://images.unsplash.com/photo-1599058917212-6cc24f5c8102" alt="Close-up of racket">
      <figcaption>Equipment matters: choose the right gear.</figcaption>
    </figure>
  </div>
</section>

<!-- JOIN US -->
<section id="join">
  <h2>Join Our Community</h2>
  <form>
    <label for="name">Name:</label>
    <input type="text" id="name" required>

    <label for="email">Email:</label>
    <input type="email" id="email" required>

    <label for="message">Message:</label>
    <textarea id="message" rows="4"></textarea>

    <input type="submit" value="Send">
  </form>

  <figure>
    <img src="https://images.unsplash.com/photo-1521412644187-c49fa049e84d" alt="Happy tennis players">
    <figcaption>Everyone is welcome — join the fun!</figcaption>
  </figure>
</section>

<footer>
  <p>&copy; 2025 Tennis for All | Created by Santiago Pedraza</p>
</footer>

</body>
</html>

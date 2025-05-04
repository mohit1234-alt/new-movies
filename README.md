
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>New Movie Releases</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #111;
      color: #fff;
    }
    header {
      background-color: #222;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2em;
    }
    .movie-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .movie-card {
      background-color: #1c1c1c;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 4px 10px rgba(0,0,0,0.5);
      transition: transform 0.2s;
    }
    .movie-card:hover {
      transform: scale(1.03);
    }
    .movie-poster {
      width: 100%;
      height: 330px;
      object-fit: cover;
    }
    .movie-details {
      padding: 15px;
    }
    .movie-title {
      font-size: 1.2em;
      margin: 0 0 10px;
    }
    .release-date {
      color: #aaa;
      font-size: 0.9em;
    }
    .description {
      font-size: 0.95em;
      margin-top: 10px;
    }
  </style>
</head>
<body>

<header>
  <h1>New Movie Releases</h1>
</header>

<section class="movie-grid">
  <!-- Example Movie Card -->
  <div class="movie-card">
    <img class="movie-poster" src="poster1.jpg" alt="Movie Poster">
    <div class="movie-details">
      <h2 class="movie-title">Movie Title 1</h2>
      <p class="release-date">Released: May 3, 2025</p>
      <p class="description">Short description of the movie goes here.</p>
    </div>
  </div>

  <div class="movie-card">
    <img class="movie-poster" src="poster2.jpg" alt="Movie Poster">
    <div class="movie-details">
      <h2 class="movie-title">Movie Title 2</h2>
      <p class="release-date">Released: May 1, 2025</p>
      <p class="description">Another exciting film about mystery and adventure.</p>
    </div>
  </div><section class="articles" style="padding: 20px; background-color: #222;">
  <h2 style="color: #fff;">Latest Articles</h2>

  <article style="margin-top: 15px; color: #ccc;">
    <h3 style="color: #fff;">Review: Guardians of the Galaxy Vol. 4</h3>
    <p>Marvel delivers another fun ride. Here's what we thought of the cosmic adventure.</p>
    <a href="#" style="color: #4fc3f7;">Read more →</a>
  </article>

  <article style="margin-top: 15px; color: #ccc;">
    <h3 style="color: #fff;">Upcoming: Spider-Man Reboot</h3>
    <p>Sony and Marvel Studios are planning a fresh take on the friendly neighborhood hero.</p>
    <a href="#" style="color: #4fc3f7;">Read more →</a>
  </article>
</section>


  <!-- Add more movie cards as needed -->
</section>

</body>
</html>

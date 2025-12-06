<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>My Mood Board</title>
</head>
<style>
    /* Global Styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'georgia', 'Times New Roman', Times, serif;
    }
  
    /* Body */
    body {
      background-color: #c2cb1e; /* Soft pastel background */
      color: #444; /* Dark text color for contrast */
      line-height: 1.6;
      padding: 20px;
      text-align: center;
    }
  
    h1 {
      font-size: 2.5rem;
      color: #0622c2; /* Cute pinkish red for main title */
      text-transform: uppercase;
      letter-spacing: 2px;
      margin-bottom: 20px;
    }
  
    h2 {
      font-size: 1.8rem;
      color: #6c5ce7; /* Soft purple color for section titles */
      margin: 10px 0;
    }
  
    h3 {
      font-size: 1.4rem;
      color: #b2bec3;
      margin-top: 15px;
    }
  
    /* Quotes */
    blockquote {
      font-size: 1.2rem;
      font-style: italic;
      color: #34495e;
      margin: 20px auto;
      padding: 10px 20px;
      background-color: #f1f1f1;
      border-left: 5px solid #ff6b6b;
      max-width: 80%;
      border-radius: 10px;
    }
  
    /* List (Manifesting) */
    ul {
      text-align: left;
      margin: 0 auto;
      max-width: 500px;
      padding: 10px;
    }
  
    li {
      font-size: 1.2rem;
      color: #2d3436;
      margin: 8px 0;
      padding-left: 20px;
      position: relative;
    }
  
    li::before {
      content: "🌟"; /* Add star emoji to list items */
      position: absolute;
      left: 0;
      font-size: 1.4rem;
    }
  
    /* Playlist Link */
    a {
      display: inline-block;
      background-color: #00b894;
      color: white;
      text-decoration: none;
      padding: 10px 20px;
      border-radius: 5px;
      margin: 20px 0;
      font-weight: bold;
      transition: background-color 0.3s ease;
    }
  
    a:hover {
      background-color: #09e38f;
    }
  
    /* Image Section */
    img {
      margin: 15px;
      border-radius: 10px;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease;
    }
  
    img:hover {
      transform: scale(1.05); /* Subtle zoom effect on hover */
    }
  
    /* Responsive Design */
    @media (max-width: 768px) {
      h1 {
        font-size: 2rem;
      }
  
      h2 {
        font-size: 1.5rem;
      }
  
      ul {
        padding: 0;
        margin: 0 auto;
      }
  
      img {
        width: 100%;
        max-width: 250px;
        margin: 10px auto;
      }
    }
  </style>
  
<body>

  <h1>🌈 Nonuu's Mood Board</h1>

  <h2>✨ My Favorite Quote</h2>
  <blockquote>
    “Code like nobody's watching, debug like everyone is.” – Nonuu
  </blockquote>
  <h1> IN THIS PLAYLIST YOU MIGHT ONLY FOUND WHAT I LISTEN DAILY OOPSIE</h1>

  <h2>💭 Things I'm Manifesting</h2>
  <ul>
    <li>🔥 Becoming a JavaScript wizard</li>
    <li>📚 Acing my finals</li>
    <li>💼 Internship at a cool tech company</li>
  </ul>

  <h2>🎵 CURRENTLY NOT FEELING LIKE MY PLAYLIST</h2>
  <p><a href="https://open.spotify.com/playlist/1Rc7l9RyF1sVR23I5wKHyW?si=n9DM7pUiSmGW8OShAzgHgw" target="_blank">Visit my playlist 🎧</a></p>

  <h2>📸 Vibe Check</h2>
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQrFD9XzMCe8GdMAmoOaxaxt7VGSqHHQxgrxQ&s" alt="Vibes" width="300" />
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSbj7bLZo_DzrFeLwfJnSMutFdWscpg9nfv0w&s" alt="Chill" width="300" />
  <img src="https://i.scdn.co/image/ab67616100005174c40600e02356cc86f0debe84" alt="Zen" width="300" />
  <img src="https://image-cdn-ak.spotifycdn.com/image/ab67706c0000da84a8444c524caa07be92de533e" alt="Zen" width="300" />
  <img src="https://i.scdn.co/image/ab67616d00001e0288e3cda6d29b2552d4d6bc43" alt="Zen" width="300" />
  <img src="https://i.scdn.co/image/ab67616d00001e02cb80f5ee50364e3a1691477d" alt="Zen" width="300" />
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRqV7TE3B2OPG8uD6dWJXNFUEDG3ijxzDU_2w&s" alt="Zen" width="300" />
  <img src="https://image-cdn.hypb.st/https%3A%2F%2Fhypebeast.com%2Fimage%2F2020%2F08%2Fspotify-the-weeknd-personalized-artificial-intelligence-experience-2.jpg?q=75&w=800&cbr=1&fit=max" alt="Zen" width="300" />
  <img src="https://static01.nyt.com/images/2021/03/26/arts/26playlist/26playlist-articleLarge.jpg?quality=75&auto=webp&disable=upscale" alt="Zen" width="300" />

</body>
</body>
<script>
  // Change Background Color Function
  function changeBackgroundColor() {
    const colors = ['#f7f7f7', '#ffdfdf', '#e0f7fa', '#f9e6ff'];
    const randomColor = colors[Math.floor(Math.random() * colors.length)];
    document.body.style.backgroundColor = randomColor;
  }

  // Toggle Visibility of Images
  function toggleImages() {
    const images = document.querySelectorAll('.hidden');
    images.forEach(image => {
      image.style.display = (image.style.display === 'block' || image.style.display === '') ? 'none' : 'block';
    });
  }
</script>
</html>

</html>

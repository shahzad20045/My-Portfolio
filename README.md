<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Meet Our Team</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0; padding: 0;
      background: #f9f9f9; color: #333;
    }
    header {
      text-align: center;
      background: #007bff; color: white;
      padding: 50px 20px;
    }
    header h1 { font-size: 2.5em; margin-bottom: 10px; }
    header p { font-size: 1.1em; }

   .team-section { padding: 50px 20px; text-align: center; }
    .team-section h2 { font-size: 2em; margin-bottom: 30px; color: #007bff; }

   .team-container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      max-width: 1100px;
      margin: auto;
    }

  /* Card Styling */
    .team-card {
      background: white;
      border-radius: 10px;
      overflow: hidden;
      position: relative;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .team-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
    }
    .team-card img {
      width: 70%;
      height: 150px;
      object-fit: cover;
    }

  .info {
      padding: 20px;
    }
    .info h3 { color: #007bff; margin: 5px 0; }
    .info p.role { font-weight: bold; color: #555; margin: 5px 0 10px; }

  /* Hover Overlay */
    .overlay {
      position: absolute;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background: rgba(0, 123, 255, 0.8);
      color: white;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      opacity: 0;
      transition: opacity 0.4s ease;
    }
    .team-card:hover .overlay { opacity: 1; }

  .overlay p { max-width: 80%; text-align: center; margin-bottom: 10px; }
    .socials a {
      margin: 0 5px;
      font-size: 20px;
      color: white;
      transition: color 0.3s;
    }
    .socials a:hover { color: yellow; }

  @media(max-width: 600px){
      header h1 { font-size: 1.8em; }
      .team-section h2 { font-size: 1.5em; }
    }
  </style>
</head>
<body>

<header>
  <h1>Meet Our Team</h1>
  <p>Our team is made up of talented professionals with expertise in web development, design, and digital marketing. Together, we craft innovative solutions that drive success.</p>
</header>

<section class="team-section">
  <h2>👨‍💻 Our Experts</h2>
  <div class="team-container">
<!-- Member -->
    <div class="team-card">
      <img src="image/download (1).jpg " alt="John Doe">
      <div class="overlay">
        <p>Specialist in building interactive and responsive websites.</p>
        <div class="socials">
          <a href="#"><i class="fab fa-linkedin"></i></a>
          <a href="#"><i class="fab fa-twitter"></i></a>
        </div>
      </div>
      <div class="info">
        <h3>John Doe</h3>
        <p class="role">Front-End Developer</p>
      </div>
    </div>
 <!-- Member -->
    <div class="team-card">
      <img src="image/download (2).jpg" alt="Jane Smith">
      <div class="overlay">
        <p>Creating user-friendly designs that delight customers.</p>
        <div class="socials">
          <a href="#"><i class="fab fa-dribbble"></i></a>
          <a href="#"><i class="fab fa-behance"></i></a>
        </div>
      </div>
      <div class="info">
        <h3>Jane Smith</h3>
        <p class="role">UI/UX Designer</p>
      </div>
    </div>
 <!-- Member -->
    <div class="team-card">
      <img src="image/download (3).jpg" alt="Mark Wilson">
      <div class="overlay">
        <p>Ensuring smooth project delivery and coordination.</p>
        <div class="socials">
          <a href="#"><i class="fab fa-linkedin"></i></a>
          <a href="#"><i class="fab fa-facebook"></i></a>
        </div>
      </div>
      <div class="info">
        <h3>Mark Wilson</h3>
        <p class="role">Project Manager</p>
      </div>
    </div>
 <!-- Member -->
    <div class="team-card">
      <img src="image/download (4).jpg" alt="Sara Lee">
      <div class="overlay">
        <p>SEO expert helping your site rank higher in search engines.</p>
        <div class="socials">
          <a href="#"><i class="fab fa-linkedin"></i></a>
          <a href="#"><i class="fab fa-twitter"></i></a>
        </div>
      </div>
      <div class="info">
        <h3>James Nikolos</h3>
        <p class="role">SEO Specialist</p>
      </div>
    </div>

  </div>
</section>

</body>
</html>

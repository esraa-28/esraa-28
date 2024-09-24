<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Esraa Taha's Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
    }

    h1, h2 {
      text-align: center;
    }

    .skills-container {
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .skill-icon {
      margin: 10px;
      opacity: 0;
      animation: fadeIn 1s ease-in-out forwards;
    }

    .skill-icon:nth-child(1) { animation-delay: 0.2s; }
    .skill-icon:nth-child(2) { animation-delay: 0.4s; }
    .skill-icon:nth-child(3) { animation-delay: 0.6s; }
    .skill-icon:nth-child(4) { animation-delay: 0.8s; }
    .skill-icon:nth-child(5) { animation-delay: 1s; }
    .skill-icon:nth-child(6) { animation-delay: 1.2s; }
    .skill-icon:nth-child(7) { animation-delay: 1.4s; }
    .skill-icon:nth-child(8) { animation-delay: 1.6s; }
    .skill-icon:nth-child(9) { animation-delay: 1.8s; }
    .skill-icon:nth-child(10) { animation-delay: 2s; }
    .skill-icon:nth-child(11) { animation-delay: 2.2s; }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    .project-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin: 20px;
    }

    .project-card {
      border: 1px solid #ddd;
      padding: 15px;
      text-align: center;
      box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
    }

    .project-card img {
      width: 100%;
      height: auto;
      border-radius: 10px;
    }

    .project-card h3 {
      margin: 10px 0;
    }

    .connect-links {
      text-align: center;
    }

    .connect-links img {
      margin: 5px;
    }
  </style>
</head>
<body>

  <h1 align="center">Hi there, I'm Esraa 👋</h1>

  <h2>🚀 About Me</h2>
  <p align="center">I’m a passionate Computer Science student at Ain Shams University, specializing in AI and Machine Learning. I love building projects that solve real-world problems, whether it's through smart IoT systems or creative software solutions.</p>

  <hr>

  <h2>🛠️ Skills</h2>
  <div class="skills-container">
    <div class="skill-icon">
      <img src="https://img.shields.io/badge/-C-00599C?style=for-the-badge&logo=c&logoColor=white" alt="C" />
    </div>
    <div class="skill-icon">
      <img src="https://img.shields.io/badge/-C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" />
    </div>
    <div class="skill-icon">
      <img src="https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
    </div>
    <div class="skill-icon">
      <img src="https://img.shields.io/badge/-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
    </div>
    <div class="skill-icon">
      <img src="https://img.shields.io/badge/-CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
    </div>
    <div class="skill-icon">
      <img src="https://img.shields.io/badge/-Java-007396?style=for-the-badge&logo=java&logoColor=white" alt="Java" />
    </div>
    <div class="skill-icon">
      <img src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
    </div>
    <div class="skill-icon">
      <img src="https://img.shields.io/badge/-SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL" />
    </div>
    <div class="skill-icon">
      <img src="https://img.shields.io/badge/-Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap" />
    </div>
    <div class="skill-icon">
      <img src="https://img.shields.io/badge/-IoT-FF7F50?style=for-the-badge&logo=iot&logoColor=white" alt="IoT" />
    </div>
    <div class="skill-icon">
      <img src="https://img.shields.io/badge/-Electronics-008080?style=for-the-badge&logo=electronics&logoColor=white" alt="Electronics" />
    </div>
  </div>

  <hr>

  <h2>📊 GitHub Stats</h2>
  <p align="center">
    <img src="https://github-readme-stats.vercel.app/api?username=EsraaTaha&show_icons=true&theme=radical" alt="Esraa's GitHub Stats" />
  </p>
  <p align="center">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=EsraaTaha&layout=compact&theme=radical" alt="Top Languages" />
  </p>

  <hr>

  <h2>📁 Projects</h2>
  <div class="project-grid">
    <div class="project-card">
      <img src="https://via.placeholder.com/300" alt="Fireboy and Watergirl">
      <h3>Fireboy and Watergirl</h3>
      <p>A two-player puzzle platformer game developed using SFML and C++.</p>
    </div>
    <div class="project-card">
      <img src="https://via.placeholder.com/300" alt="Squid Game">
      <h3>Squid Game</h3>
      <p>A real-world game controlled via IoT and sensors.</p>
    </div>
    <div class="project-card">
      <img src="https://via.placeholder.com/300" alt="WatchHub">
      <h3>WatchHub</h3>
      <p>A full-stack app for managing movie preferences and subscriptions.</p>
    </div>
    <!-- Add more project cards here -->
  </div>

  <hr>

  <h2>📫 Connect with Me</h2>
  <div class="connect-links">
    <a href="https://www.linkedin.com/in/esraa-taha/">
      <img src="https://img.shields.io/badge/LinkedIn-EsraaTaha-blue?style=flat&logo=linkedin" alt="LinkedIn" />
    </a>
    <a href="mailto:esraa.taha@gmail.com">
      <img src="https://img.shields.io/badge/Gmail-EsraaTaha-red?style=flat&logo=gmail" alt="Gmail" />
    </a>
  </div>

  <hr>

  <h2>🔥 Fun Stats</h2>
  <p align="center">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=EsraaTaha&theme=radical" alt="GitHub Streak" />
  </p>

</body>
</html>

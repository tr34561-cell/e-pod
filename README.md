
<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="My Personal Portfolio">
  <title>My Portfolio | Student</title>

  <link rel="stylesheet" href="style.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Kanit:wght@300;400;500;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
</head>
<body>

  <header>
    <nav class="navbar container">
      <a href="#home" class="logo">My<span>Portfolio.</span></a>

      <div class="menu-toggle" id="menu-toggle">
        <i class="fas fa-bars"></i>
      </div>

      <ul class="nav-links" id="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#education">Education</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- HOME -->
  <section class="hero container" id="home">
    <div class="hero-content">
      <p class="welcome">WELCOME TO MY PORTFOLIO</p>

      <h1>Hello, I'm <span>Student</span></h1>

      <h2>I'm a <span class="typing">Creative Learner</span></h2>

      <p class="hero-description">
        สวัสดีครับ/ค่ะ ยินดีต้อนรับเข้าสู่ Portfolio ของฉัน
        เว็บไซต์ที่รวบรวมประวัติส่วนตัว ทักษะ ความสามารถ
        และผลงานที่ฉันภาคภูมิใจ
      </p>

      <div class="hero-buttons">
        <a href="#projects" class="btn primary">View My Work</a>
        <a href="#contact" class="btn secondary">Contact Me</a>
      </div>

      <div class="social-icons">
        <a href="#"><i class="fab fa-facebook"></i></a>
        <a href="#"><i class="fab fa-instagram"></i></a>
        <a href="#"><i class="fab fa-github"></i></a>
      </div>
    </div>

    <div class="hero-image">
      <div class="image-glow"></div>
      <img src="images/profile.jpg" alt="My Profile"
           onerror="this.style.display='none'">
      <div class="profile-placeholder">
        <i class="fas fa-user-graduate"></i>
        <span>YOUR PHOTO</span>
      </div>
    </div>
  </section>

  <!-- ABOUT -->
  <section class="section container" id="about">
    <div class="section-title">
      <span>INTRODUCTION</span>
      <h2>About <span>Me</span></h2>
    </div>

    <div class="about-content">
      <div class="about-card">
        <i class="fas fa-user"></i>
        <h3>Personal Information</h3>
        <p>ชื่อ: ชื่อ-นามสกุลของคุณ</p>
        <p>ชื่อเล่น: ชื่อเล่น</p>
        <p>อายุ: XX ปี</p>
        <p>สถานะ: Student</p>
      </div>

      <div class="about-text">
        <h3>Who Am I?</h3>
        <p>
          ฉันเป็นนักเรียน/นักศึกษาที่มีความสนใจด้านเทคโนโลยี
          การออกแบบเว็บไซต์ และการเขียนโปรแกรม
          ชอบเรียนรู้สิ่งใหม่ ๆ และพัฒนาความสามารถของตนเองอยู่เสมอ
        </p>
        <p>
          My goal is to improve my skills,
          explore new technologies and create
          something meaningful.
        </p>
      </div>
    </div>
  </section>

  <!-- SKILLS -->
  <section class="section container" id="skills">
    <div class="section-title">
      <span>WHAT I CAN DO</span>
      <h2>My <span>Skills</span></h2>
    </div>

    <div class="skills-grid">
      <div class="skill-card">
        <i class="fab fa-html5"></i>
        <h3>HTML</h3>
        <div class="progress"><span style="width:85%"></span></div>
        <p>85%</p>
      </div>

      <div class="skill-card">
        <i class="fab fa-css3-alt"></i>
        <h3>CSS</h3>
        <div class="progress"><span style="width:75%"></span></div>
        <p>75%</p>
      </div>

      <div class="skill-card">
        <i class="fab fa-js"></i>
        <h3>JavaScript</h3>
        <div class="progress"><span style="width:60%"></span></div>
        <p>60%</p>
      </div>

      <div class="skill-card">
        <i class="fab fa-python"></i>
        <h3>Python</h3>
        <div class="progress"><span style="width:65%"></span></div>
        <p>65%</p>
      </div>
    </div>
  </section>

  <!-- EDUCATION -->
  <section class="section container" id="education">
    <div class="section-title">
      <span>MY JOURNEY</span>
      <h2>My <span>Education</span></h2>
    </div>

    <div class="timeline">
      <div class="timeline-item">
        <span class="year">2024 - Present</span>
        <h3>มัธยมศึกษาปีที่6</h3>
        <p>โรงเรียนธั / สาขาวิชา</p>
      </div>

      <div class="timeline-item">
        <span class="year">2021 - 2024</span>
        <h3>ระดับมัธยมศึกษา</h3>
        <p>ชื่อโรงเรียน</p>
      </div>

      <div class="timeline-item">
        <span class="year">2015 - 2021</span>
        <h3>ระดับประถมศึกษา</h3>
        <p>ชื่อโรงเรียน</p>
      </div>
    </div>
  </section>

  <!-- PROJECTS -->
  <section class="section container" id="projects">
    <div class="section-title">
      <span>MY RECENT WORK</span>
      <h2>My <span>Projects</span></h2>
    </div>

    <div class="projects-grid">
      <div class="project-card">
        <div class="project-icon">
          <i class="fas fa-laptop-code"></i>
        </div>
        <div class="project-info">
          <span>WEB DEVELOPMENT</span>
          <h3>My First Website</h3>
          <p>เว็บไซต์แนะนำตัวที่สร้างด้วย HTML และ CSS</p>
          <a href="#" class="project-link">View Project <i class="fas fa-arrow-right"></i></a>
        </div>
      </div>

      <div class="project-card">
        <div class="project-icon">
          <i class="fas fa-calculator"></i>
        </div>
        <div class="project-info">
          <span>JAVASCRIPT</span>
          <h3>Calculator App</h3>
          <p>โปรแกรมเครื่องคิดเลขสำหรับการคำนวณ</p>
          <a href="#" class="project-link">View Project <i class="fas fa-arrow-right"></i></a>
        </div>
      </div>

      <div class="project-card">
        <div class="project-icon">
          <i class="fas fa-palette"></i>
        </div>
        <div class="project-info">
          <span>DESIGN</span>
          <h3>Creative Design</h3>
          <p>ผลงานการออกแบบกราฟิกและ UI Design</p>
          <a href="#" class="project-link">View Project <i class="fas fa-arrow-right"></i></a>
        </div>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section class="section container" id="contact">
    <div class="section-title">
      <span>GET IN TOUCH</span>
      <h2>Contact <span>Me</span></h2>
    </div>

    <div class="contact-content">
      <h3>Let's Connect!</h3>
      <p>หากสนใจผลงานหรืออยากพูดคุย สามารถติดต่อฉันได้ที่นี่</p>

      <div class="contact-item">
        <i class="fas fa-envelope"></i>
        <span>your@email.com</span>
      </div>

      <div class="contact-item">
        <i class="fab fa-facebook"></i>
        <span>Facebook: Your Name</span>
      </div>

      <div class="contact-item">
        <i class="fab fa-instagram"></i>
        <span>Instagram: @username</span>
      </div>

      <a href="mailto:your@email.com" class="btn primary">
        Send Me an Email
      </a>
    </div>
  </section>

  <footer>
    <p>© 2026 My Portfolio. Made with ❤️ by Student</p>
  </footer>

  <button id="back-to-top" aria-label="Back to top">
    <i class="fas fa-arrow-up"></i>
  </button>

  <script src="script.js"></script>
</body>
</html>

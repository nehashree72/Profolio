# Profolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Nehashree N - Portfolio</title>
  <style>

    /* ── BASIC RESET ── */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background-color: #f5f5f5;
      color: #333;
    }

    /* ── TOP BAR ── */
    header {
      background-color: #2563eb;
      color: white;
      text-align: center;
      padding: 40px 20px;
    }

    header h1 {
      font-size: 40px;
    }

    header p {
      font-size: 16px;
      margin-top: 8px;
      color: #cce0ff;
    }

    /* ── NAV LINKS ── */
    nav {
      background-color: #1e4fc2;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 12px;
      flex-wrap: wrap;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-size: 14px;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    /* ── SECTIONS ── */
    section {
      max-width: 900px;
      margin: 30px auto;
      background: white;
      border-radius: 8px;
      padding: 30px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.08);
    }

    section h2 {
      font-size: 22px;
      color: #2563eb;
      margin-bottom: 20px;
      border-bottom: 2px solid #2563eb;
      padding-bottom: 8px;
    }

    /* ── EDUCATION ── */
    .edu-item {
      margin-bottom: 16px;
    }

    .edu-item h3 {
      font-size: 16px;
      color: #333;
    }

    .edu-item p {
      font-size: 14px;
      color: #666;
      margin-top: 3px;
    }

    .edu-item span {
      display: inline-block;
      margin-top: 5px;
      background: #eef4ff;
      color: #2563eb;
      font-size: 12px;
      padding: 2px 10px;
      border-radius: 20px;
    }

    /* ── SKILLS ── */
    .skill-group {
      margin-bottom: 16px;
    }

    .skill-group h3 {
      font-size: 14px;
      color: #888;
      margin-bottom: 8px;
      text-transform: uppercase;
      letter-spacing: 1px;
    }

    .tags {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
    }

    .tag {
      background: #f0f0f0;
      border: 1px solid #ddd;
      border-radius: 5px;
      padding: 5px 12px;
      font-size: 13px;
      color: #333;
    }

    /* ── PROJECTS ── */
    .project-item {
      border: 1px solid #e0e0e0;
      border-radius: 8px;
      padding: 18px;
      margin-bottom: 16px;
    }

    .project-item h3 {
      font-size: 17px;
      color: #222;
      margin-bottom: 6px;
    }

    .project-item p {
      font-size: 14px;
      color: #555;
      margin-bottom: 10px;
    }

    .project-item ul {
      padding-left: 18px;
      font-size: 13px;
      color: #666;
      line-height: 1.8;
    }

    /* ── CERTIFICATIONS ── */
    .cert-list {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
    }

    .cert-item {
      background: #f9f9f9;
      border: 1px solid #ddd;
      border-radius: 8px;
      padding: 12px 20px;
      font-size: 14px;
      font-weight: bold;
      color: #333;
    }

    /* ── SOFT SKILLS ── */
    .soft-list {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }

    .soft-item {
      background: #eef4ff;
      color: #2563eb;
      border-radius: 6px;
      padding: 8px 16px;
      font-size: 14px;
      font-weight: bold;
    }

    /* ── TOOLS ── */
    .tool-list {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }

    .tool-item {
      background: #fff7ed;
      color: #c2410c;
      border: 1px solid #fed7aa;
      border-radius: 20px;
      padding: 8px 18px;
      font-size: 14px;
      font-weight: bold;
    }

    /* ── FOOTER ── */
    footer {
      text-align: center;
      padding: 24px;
      background: #333;
      color: #aaa;
      font-size: 13px;
    }

    /* ── MOBILE ── */
    @media (max-width: 600px) {
      header h1 { font-size: 28px; }
      section { margin: 16px; padding: 20px; }
    }

  </style>
</head>
<body>

  <!-- TOP HEADER -->
  <header>
    <h1>Nehashree N</h1>
    <p>Computer Science Student · Full-Stack · MERN · Python · Java</p>
    <p style="margin-top:6px; font-size:14px;">📍 Coimbatore, Tamil Nadu</p>
  </header>

  <!-- NAVIGATION -->
  <nav>
    <a href="#education">Education</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#certifications">Certifications</a>
    <a href="#softskills">Soft Skills</a>
    <a href="#tools">Tools</a>
  </nav>

  <!-- EDUCATION -->
  <section id="education">
    <h2>Education</h2>

    <div class="edu-item">
      <h3>B.Sc Computer Science</h3>
      <p>KG College of Arts and Science</p>
      <span>2024 – 2027</span>
    </div>

    <div class="edu-item">
      <h3>12th Standard</h3>
      <p>Higher Secondary Education</p>
      <span>2023-2024
      </span>
    </div>

    <div class="edu-item">
      <h3>10th Standard</h3>
      <p>Secondary Education</p>
      <span>2021-2022</span>
    </div>
  </section>

  <!-- SKILLS -->
  <section id="skills">
    <h2>Tech Skills</h2>

    <div class="skill-group">
      <h3>Languages</h3>
      <div class="tags">
        <span class="tag">Python</span>
        <span class="tag">Java</span>
        <span class="tag">C</span>
        <span class="tag">JavaScript</span>
      </div>
    </div>

    <div class="skill-group">
      <h3>Frontend</h3>
      <div class="tags">
        <span class="tag">HTML</span>
        <span class="tag">CSS</span>
        <span class="tag">React.js</span>
      </div>
    </div>

    <div class="skill-group">
      <h3>Database</h3>
      <div class="tags">
        <span class="tag">MongoDB</span>
        <span class="tag">MySQL</span>
      </div>
    </div>

    <div class="skill-group">
      <h3>Stack</h3>
      <div class="tags">
        <span class="tag">MERN Stack</span>
        <span class="tag">Node.js</span>
        <span class="tag">Express.js</span>
      </div>
    </div>
  </section>

  <!-- PROJECTS -->
  <section id="projects">
    <h2>Projects</h2>

    <div class="project-item">
      <h3>Mobile Store Management System</h3>
      <p>A system to manage stock, billing, and customer data for a mobile retail store.</p>
      <ul>
        <li>Stock management & inventory tracking</li>
        <li>Billing & invoice generation</li>
        <li>Customer data management</li>
      </ul>
    </div>

    <div class="project-item">
      <h3>Comment & Reply Thread System</h3>
      <p>A MERN stack project for threaded comments with likes, dislikes, and delete.</p>
      <ul>
        <li>Nested replies with deep threading</li>
        <li>Like / Dislike on comments</li>
        <li>Delete functionality</li>
      </ul>
    </div>
  </section>

  <!-- CERTIFICATIONS -->
  <section id="certifications">
    <h2>Certifications</h2>
    <div class="cert-list">
      <div class="cert-item">🐍 Python</div>
      <div class="cert-item">☕ Java</div>
      <div class="cert-item">🍃 MongoDB</div>
      <div class="cert-item">📚 NPTEL</div>
    </div>
  </section>

  <!-- SOFT SKILLS -->
  <section id="softskills">
    <h2>Soft Skills</h2>
    <div class="soft-list">
      <div class="soft-item">💬 Communication</div>
      <div class="soft-item">🤝 Teamwork</div>
      <div class="soft-item">🧩 Problem Solving</div>
      <div class="soft-item">⏱️ Time Management</div>
    </div>
  </section>

  <!-- TOOLS -->
  <section id="tools">
    <h2>Tools</h2>
    <div class="tool-list">
      <div class="tool-item">💻 VS Code</div>
      <div class="tool-item">🐙 GitHub</div>
      <div class="tool-item">🎨 Canva</div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    <p>Nehashree N · B.Sc Computer Science · KG College · Coimbatore</p>
  </footer>

</body>
</html>

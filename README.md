# Ex01 Portfolio
## Date: 3.02.2026

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
### about.html
```
<!DOCTYPE html>
<html>
<head>
    <title>About</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<div class="nav">
    <a href="port.html">Home</a>
    <a href="about.html" class="active" aria-current="page">About</a>
    <a href="skills.html">Skills</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
</div>

<div class="page">
    <h1>About Me</h1>
    <p class="lead">Full-stack software engineer passionate about designing scalable solutions and clean code architecture.</p>

    <p>
        I'm a dedicated software engineer with expertise in building robust, scalable applications. I specialize in full-stack development with a strong focus on backend architecture, database design, and system optimization.
    </p>

    <p>
        My journey in software engineering has been driven by a passion for solving complex problems through well-architected solutions. I believe in writing maintainable code, following SOLID principles, and leveraging modern development practices to deliver production-ready applications.
    </p>

    <p>
        I'm experienced in agile methodologies, CI/CD pipelines, cloud technologies, and have worked on microservices architecture. I continuously explore emerging technologies and best practices to stay at the forefront of the industry.
    </p>

    <p>
        <a href="port.html" class="btn btn-primary">← Back to Home</a>
    </p>
</div>

</body>
</html>
```

### contact.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Contact </title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<div class="nav">
    <a href="port.html">Home</a>
    <a href="about.html">About</a>
    <a href="skills.html">Skills</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
</div>

<div class="page">
    <h1>Contact Me</h1>
    <p class="lead">Let's collaborate on innovative software engineering solutions.</p>

    <div class="contact-info">
        <div class="contact-item">
            <h3>Email</h3>
            <p><a href="mailto:nikexhkumar@gmail.com">nikexhkumar@gmail.com</a></p>
        </div>
        <div class="contact-item">
            <h3>Phone</h3>
            <p><a href="tel:+916380652445">+91 6380652445</a></p>
        </div>
        <div class="contact-item">
            <h3>LinkedIn</h3>
            <p><a href="#" target="_blank">linkedin.com/in/nikesh</a></p>
        </div>
        <div class="contact-item">
            <h3>GitHub</h3>
            <p><a href="#" target="_blank">github.com/nikesh</a></p>
        </div>
    </div>

    <div class="contact-form">
        <h2>Send me a Message</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" rows="5" required></textarea>
            <button type="submit" class="btn btn-primary">Send Message</button>
        </form>
    </div>
</div>

</body>
</html>
```

### port.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Home</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<div class="nav">
    <a href="port.html">Home</a>
    <a href="about.html">About</a>
    <a href="skills.html">Skills</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
</div>

<div class="home">
    <h1>Hello, I'm NIKESH</h1>
    <p class="subtitle">Full Stack Software Engineer</p>
    <p class="description">Building scalable systems, clean architectures, and innovative solutions 🧑‍💻</p>
    <div class="cta-buttons">
        <a href="about.html" class="btn btn-primary">Learn More</a>
        <a href="projects.html" class="btn btn-secondary">View My Work</a>
    </div>
</div>

</body>
</html>
```
### projects.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Contact </title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<div class="nav">
    <a href="port.html">Home</a>
    <a href="about.html">About</a>
    <a href="skills.html">Skills</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
</div>




<div class="page">
    <h1>My Projects</h1>
    <p class="lead">A collection of full-stack software engineering projects showcasing system design, scalability, and best practices.</p>

    <div class="projects-container">

        <div class="project">
            <div class="project-badge">Full Stack</div>
            <h3>Lifeline AI - Mental Health Detection System</h3>
            <p>
                An AI-powered backend service that detects early signs of emotional distress using NLP and behavioral analysis. Implemented microservices architecture with Python, PostgreSQL, and Redis for real-time data processing. Deployed on AWS with Docker containerization and automated CI/CD pipeline.
            </p>
            <div class="tech-stack">
                <span>Python</span>
                <span>PostgreSQL</span>
                <span>AWS</span>
                <span>Docker</span>
            </div>
            <a href="#">View Project</a>
        </div>

        <div class="project">
            <div class="project-badge">Backend</div>
            <h3>RESTful Task Management API</h3>
            <p>
                Scalable REST API for task management with JWT authentication, role-based access control, and comprehensive unit tests. Implemented pagination, filtering, and sorting for optimal performance. Achieved 99.9% uptime with proper error handling and logging.
            </p>
            <div class="tech-stack">
                <span>Node.js</span>
                <span>Express</span>
                <span>MongoDB</span>
                <span>Jest</span>
            </div>
            <a href="#">View Project</a>
        </div>

        <div class="project">
            <div class="project-badge">Full Stack</div>
            <h3>Distributed System Monitoring Dashboard</h3>
            <p>
                Real-time monitoring dashboard for microservices architecture. Built with React frontend, Node.js backend, and time-series database for metrics. Implemented WebSocket for live updates and Grafana integration for advanced analytics.
            </p>
            <div class="tech-stack">
                <span>React</span>
                <span>Node.js</span>
                <span>InfluxDB</span>
                <span>WebSocket</span>
            </div>
            <a href="#">View Project</a>
        </div>

        <div class="project">
            <div class="project-badge">DevOps</div>
            <h3>Infrastructure as Code Setup</h3>
            <p>
                Automated infrastructure provisioning using Terraform and CloudFormation. Implemented Kubernetes orchestration with Helm charts for multi-environment deployment. Set up comprehensive monitoring with Prometheus and ELK stack.
            </p>
            <div class="tech-stack">
                <span>Kubernetes</span>
                <span>Terraform</span>
                <span>Docker</span>
                <span>AWS</span>
            </div>
            <a href="#">View Project</a>
        </div>

        <div class="project">
            <div class="project-badge">Frontend</div>
            <h3>Responsive Developer Portfolio</h3>
            <p>
                Modern, performance-optimized portfolio website with accessibility standards compliance. Implemented responsive design, SEO optimization, and critical CSS inline strategy. Achieved 98/100 Lighthouse score.
            </p>
            <div class="tech-stack">
                <span>React</span>
                <span>TypeScript</span>
                <span>Tailwind CSS</span>
                <span>Next.js</span>
            </div>
            <a href="#">View Project</a>
        </div>

        <div class="project">
            <div class="project-badge">Backend</div>
            <h3>Database Optimization & Query Performance</h3>
            <p>
                Analyzed and optimized complex database queries reducing response time by 78%. Implemented caching strategy with Redis, database indexing, and query optimization. Documented best practices for team implementation.
            </p>
            <div class="tech-stack">
                <span>PostgreSQL</span>
                <span>Redis</span>
                <span>Python</span>
                <span>EXPLAIN ANALYZE</span>
            </div>
            <a href="#">View Project</a>
        </div>

    </div>
</div>
</body></html>
```

### skills.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Skills</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<div class="nav">
    <a href="port.html">Home</a>
    <a href="about.html">About</a>
    <a href="skills.html">Skills</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
</div>

<div class="page">
    <h1>My Skills</h1>
    
    <h2 class="skill-category">Backend Development</h2>
    <div class="skills-grid">
        <div class="skill">Python</div>
        <div class="skill">Java</div>
        <div class="skill">Node.js</div>
        <div class="skill">Go</div>
        <div class="skill">SQL</div>
        <div class="skill">PostgreSQL</div>
    </div>

    <h2 class="skill-category">Frontend Development</h2>
    <div class="skills-grid">
        <div class="skill">React</div>
        <div class="skill">JavaScript</div>
        <div class="skill">TypeScript</div>
        <div class="skill">HTML/CSS</div>
        <div class="skill">Vue.js</div>
        <div class="skill">REST APIs</div>
    </div>

    <h2 class="skill-category">Tools & Platforms</h2>
    <div class="skills-grid">
        <div class="skill">Git</div>
        <div class="skill">Docker</div>
        <div class="skill">Kubernetes</div>
        <div class="skill">AWS</div>
        <div class="skill">Linux</div>
        <div class="skill">CI/CD</div>
    </div>

    <h2 class="skill-category">Core Competencies</h2>
    <div class="skills-grid">
        <div class="skill">Microservices</div>
        <div class="skill">System Design</div>
        <div class="skill">OOP</div>
        <div class="skill">Agile/Scrum</div>
        <div class="skill">Unit Testing</div>
        <div class="skill">Code Review</div>
    </div>
</div>

</body>
</html>
```

### style.css
```
:root {
    --bg: #0a0a0a;
    --panel: #1a1a1a;
    --muted: #e5e7eb;
    --accent: #ef4444;
    --accent-2: #dc2626;
    --accent-cta: #f87171;
    --glass: rgba(255,255,255,0.03);
    --card-shadow: 0 15px 40px rgba(0,0,0,0.5);
    --radius: 14px;
}

body {
    margin: 0;
    font-family: "Segoe UI", Arial, sans-serif;
    background: linear-gradient(180deg, var(--bg), #081024 160%);
    color: var(--muted);
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}

/* Navbar */
.nav {
    text-align: center;
    padding: 18px 12px;
    background: rgba(17,24,39,0.9);
    box-shadow: 0 6px 18px rgba(0,0,0,0.45);
    backdrop-filter: blur(4px);
}

.nav a {
    color: var(--muted);
    text-decoration: none;
    margin: 0 14px;
    font-size: 16px;
    font-weight: 700;
    padding: 8px 14px;
    border-radius: 10px;
    transition: all 180ms ease;
}

.nav a:hover {
    color: white;
    transform: translateY(-2px);
    background: linear-gradient(90deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
}

.nav a:focus {
    outline: 2px solid var(--accent);
    outline-offset: 2px;
}

.nav a.active,
.nav a[aria-current="page"] {
    background: linear-gradient(90deg, rgba(239,68,68,0.14), rgba(220,38,38,0.08));
    color: white;
    box-shadow: 0 6px 20px rgba(239,68,68,0.12);
}

```

## OUTPUT
<img width="1920" height="1080" alt="Screenshot 2026-02-10 144244" src="https://github.com/user-attachments/assets/068ded41-1297-4180-a58e-50d56e5d078c" />

<img width="1920" height="1080" alt="Screenshot 2026-02-10 144254" src="https://github.com/user-attachments/assets/fc5cce52-c066-49cf-85f0-a95908664682" />

<img width="1920" height="1080" alt="Screenshot 2026-02-10 144304" src="https://github.com/user-attachments/assets/7aa36387-e2ec-474d-95e9-93f6872d4c29" />

<img width="1920" height="1080" alt="Screenshot 2026-02-10 144313" src="https://github.com/user-attachments/assets/257c1d35-d9f1-43f7-be5a-1e08539b792e" />

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.

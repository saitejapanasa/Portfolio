<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SAI TEJA PANASA | Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #0f0f0f;
            color: white;
            margin: 0;
            padding: 0;
            text-align: center;
            overflow-x: hidden;
        }
        header {
            padding: 20px;
            background: rgba(0, 0, 0, 0.9);
            box-shadow: 0px 0px 20px cyan;
        }
        section {
            padding: 20px;
        }
        footer {
            background: rgba(0, 0, 0, 0.9);
            padding: 10px;
            box-shadow: 0px 0px 20px cyan;
        }
        .contact-icons {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 10px;
        }
        .contact-icons a {
            color: cyan;
            font-size: 24px;
            text-decoration: none;
            transition: transform 0.3s;
        }
        .contact-icons a:hover {
            transform: scale(1.2);
        }
        h1, h2, h3 {
            color: cyan;
            text-shadow: 0px 0px 10px cyan;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        li {
            margin: 10px 0;
        }
    </style>
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>
<body>
    <header>
        <h1>SAI TEJA PANASA</h1>
        <p>Full-Stack Engineer | Java | Python | React | Node.js</p>
    </header>
    
    <section id="about">
        <h2>About Me</h2>
        <p>Enthusiastic and driven full-stack engineer, eager to leverage academic achievements and hands-on project experiences into impactful contributions.</p>
        <p>Former Java Full Stack Developer at Accenture with experience in developing scalable web applications, integrating APIs, and enhancing user experiences.</p>
    </section>
    
    <section id="experience">
        <h2>Professional Experience</h2>
        <h3>Java Full Stack Developer - Accenture, Hyderabad, India (Aug 2021 - July 2023)</h3>
        <ul>
            <li>Developed and integrated user-friendly interfaces ensuring seamless interaction between frontend and backend components.</li>
            <li>Maintained data integrity and security in database applications, preventing critical security vulnerabilities.</li>
            <li>Designed and optimized server-side applications and databases for performance and scalability.</li>
            <li>Participated in code reviews and contributed to high-quality, error-free development in collaborative projects.</li>
            <li>Implemented automated unit and integration testing, achieving 90% code coverage and reducing post-release defects by 70%.</li>
        </ul>
    </section>
    
    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Java, Python, JavaScript, TypeScript, C, C++</li>
            <li>React.js, Angular, Node.js, Express.js</li>
            <li>Spring Boot, Hibernate, Django, Flask</li>
            <li>MySQL, PostgreSQL, MongoDB</li>
            <li>Docker, Kubernetes, Git, Jenkins</li>
        </ul>
    </section>
    
    <footer>
        <p>Contact me: 
            <a href="mailto:saitejapanasa2@gmail.com" style="color: cyan;" aria-label="Email">
                <i class="fas fa-envelope"></i> saitejapanasa2@gmail.com
            </a>
        </p>
        <div class="contact-icons">
            <a href="mailto:saitejapanasa2@gmail.com" title="Email" aria-label="Email">
                <i class="fas fa-envelope"></i>
            </a>
            <a href="https://www.linkedin.com/in/saitejapanasa/" target="_blank" rel="noopener noreferrer" title="LinkedIn" aria-label="LinkedIn">
                <i class="fab fa-linkedin"></i> LinkedIn
            </a>
            <a href="tel:+19135867656" title="Phone" aria-label="Phone">
                <i class="fas fa-phone"></i> Mobile
            </a>
        </div>
    </footer>
     
    <script src="script.js"></script>
</body>
</html>

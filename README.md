<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nikol Panova · Computer Engineering Student</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: linear-gradient(135deg, #0a0f1e 0%, #0c1222 100%);
            font-family: 'Segoe UI', 'Inter', system-ui, -apple-system, 'Roboto', sans-serif;
            color: #eef2ff;
            line-height: 1.5;
            padding: 2rem 1rem;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            background: rgba(15, 23, 42, 0.7);
            backdrop-filter: blur(2px);
            border-radius: 2.5rem;
            padding: 2rem;
            box-shadow: 0 25px 45px -12px rgba(0, 0, 0, 0.5);
            border: 1px solid rgba(56, 189, 248, 0.2);
        }

        .hero {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid #1e293b;
            padding-bottom: 2rem;
            margin-bottom: 2rem;
        }

        .badge-area {
            display: flex;
            gap: 0.75rem;
            flex-wrap: wrap;
            margin-top: 0.75rem;
        }

        .badge {
            background: #0f172a;
            padding: 0.25rem 0.9rem;
            border-radius: 40px;
            font-size: 0.8rem;
            font-weight: 500;
            border: 1px solid #334155;
            color: #b9e6ff;
        }

        .name {
            font-size: 3.2rem;
            font-weight: 800;
            background: linear-gradient(120deg, #ffffff, #7dd3fc);
            background-clip: text;
            -webkit-background-clip: text;
            color: transparent;
            letter-spacing: -0.02em;
        }

        .title {
            font-size: 1.3rem;
            color: #94a3b8;
            margin-top: 0.3rem;
        }

        .contact-info {
            text-align: right;
        }

        .contact-info p {
            margin: 0.25rem 0;
            display: flex;
            gap: 0.6rem;
            justify-content: flex-end;
            align-items: center;
        }

        .contact-info a {
            color: #7dd3fc;
            text-decoration: none;
            font-weight: 500;
        }

        .grid-2 {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 2rem;
            margin-bottom: 2rem;
        }

        .card {
            background: #0f172a;
            border-radius: 1.75rem;
            padding: 1.5rem;
            border: 1px solid #1e293b;
            transition: all 0.2s ease;
        }

        .card:hover {
            border-color: #38bdf8;
            box-shadow: 0 10px 20px -8px rgba(56, 189, 248, 0.2);
        }

        .section-title {
            font-size: 1.5rem;
            font-weight: 700;
            margin-bottom: 1.25rem;
            display: flex;
            align-items: center;
            gap: 0.6rem;
            border-left: 4px solid #38bdf8;
            padding-left: 1rem;
        }

        .exp-item, .edu-item {
            margin-bottom: 1.5rem;
        }

        .exp-header, .edu-header {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            font-weight: 700;
            margin-bottom: 0.3rem;
            font-size: 1.1rem;
        }

        .exp-company, .edu-major {
            color: #38bdf8;
        }

        .exp-date, .edu-date {
            color: #9ca3af;
            font-weight: 400;
        }

        .exp-desc {
            color: #cbd5e1;
            font-size: 0.9rem;
            margin-top: 0.5rem;
            padding-left: 1rem;
        }

        .exp-desc li {
            margin-bottom: 0.25rem;
        }

        .skills-list {
            display: flex;
            flex-wrap: wrap;
            gap: 0.7rem;
            margin-top: 0.5rem;
        }

        .skill-tag {
            background: #1e293b;
            padding: 0.3rem 1rem;
            border-radius: 40px;
            font-size: 0.8rem;
            font-weight: 500;
            border: 1px solid #334155;
        }

        .skill-cat {
            margin-bottom: 1.2rem;
        }

        .skill-cat strong {
            color: #7dd3fc;
            display: block;
            margin-bottom: 0.5rem;
            font-size: 0.95rem;
        }

        .interests {
            background: #0f172a;
            border-radius: 1.75rem;
            padding: 1.5rem;
            margin-top: 1rem;
            line-height: 1.6;
            color: #cbd5e6;
        }

        .certificate-item {
            background: #1e293b;
            padding: 0.5rem 1rem;
            border-radius: 1rem;
            margin-bottom: 0.5rem;
            font-size: 0.9rem;
        }

        footer {
            margin-top: 2.5rem;
            text-align: center;
            font-size: 0.8rem;
            color: #5b6e8c;
            border-top: 1px solid #1e293b;
            padding-top: 1.5rem;
        }

        @media (max-width: 760px) {
            .hero {
                flex-direction: column;
                align-items: start;
                gap: 1rem;
            }
            .contact-info {
                text-align: left;
            }
            .contact-info p {
                justify-content: flex-start;
            }
            .name {
                font-size: 2.4rem;
            }
            .grid-2 {
                grid-template-columns: 1fr;
                gap: 1.5rem;
            }
        }
    </style>
</head>
<body>
<div class="container">
    
    <div class="hero">
        <div>
            <h1 class="name">Nikol Panova</h1>
            <div class="title">🎓 Computer Engineering Student · Sofia, Bulgaria</div>
            <div class="badge-area">
                <span class="badge">🐍 Python</span>
                <span class="badge">⚙️ C/C++</span>
                <span class="badge">📘 Java</span>
                <span class="badge">🌐 HTML/CSS</span>
                <span class="badge">🗄️ MySQL</span>
                <span class="badge">🔧 Git & GitHub</span>
            </div>
        </div>
        <div class="contact-info">
            <p>📧 <a href="mailto:nikol.pan02@gmail.com">nikol.pan02@gmail.com</a></p>
            <p>📞 +359 876 155 000</p>
            <p>📍 Sofia, Bulgaria | 23.09.2002</p>
        </div>
    </div>

    <div class="grid-2">
        
        <div>
            <div class="card">
                <div class="section-title">
                    <span>💼</span> Work Experience
                </div>
                
                <div class="exp-item">
                    <div class="exp-header">
                        <span class="exp-company">Driver · Delivery 2015</span>
                        <span class="exp-date">April 2022 – March 2024</span>
                    </div>
                    <ul class="exp-desc">
                        <li>Order coordination and efficient route planning</li>
                        <li>Responsibility, critical thinking, and time management</li>
                        <li>Adaptability in fast-paced environments</li>
                    </ul>
                </div>

                <div class="exp-item">
                    <div class="exp-header">
                        <span class="exp-company">Sales Consultant · Inventer Trading</span>
                        <span class="exp-date">January 2021 – March 2022</span>
                    </div>
                    <ul class="exp-desc">
                        <li>Customer service and direct client communication</li>
                        <li>Task organization and multitasking</li>
                        <li>Team collaboration and retail operations</li>
                    </ul>
                </div>
            </div>

            <div class="card">
                <div class="section-title">
                    <span>📖</span> Education
                </div>

                <div class="edu-item">
                    <div class="exp-header">
                        <span class="edu-major">BSc in Computer Engineering</span>
                        <span class="edu-date">Sep 2023 – June 2027</span>
                    </div>
                    <div style="color:#b9c3db; font-size:0.9rem;">Technical University of Sofia</div>
                    <div style="color:#8ba0bc; font-size:0.85rem; margin-top: 0.25rem;">
                        Information Technologies in Industry, Faculty of Computer Systems and Technology<br>
                        <em>Current: 3rd year</em>
                    </div>
                </div>

                <div class="edu-item">
                    <div class="exp-header">
                        <span class="edu-major">High School Diploma</span>
                        <span class="edu-date">May 2021</span>
                    </div>
                    <div style="color:#b9c3db; font-size:0.9rem;">134 SU "Dimcho Debelyanov" – Jewish Language High School</div>
                    <div style="color:#8ba0bc; font-size:0.85rem;">Profile: Informatics & Mathematics</div>
                </div>
            </div>

            <div class="card">
                <div class="section-title">
                    <span>📜</span> Certificates
                </div>
                <div class="certificate-item">✅ Programming Basics – SoftUni (with distinction)</div>
                <div class="certificate-item">✅ Programming Fundamentals with Python – SoftUni (with distinction)</div>
                <div style="margin-top: 0.8rem; color:#7dd3fc; font-size:0.85rem;">July 2024 – May 2025</div>
            </div>
        </div>

        <div>
            <div class="card">
                <div class="section-title">
                    <span>⚡</span> Core Competencies
                </div>

                <div class="skill-cat">
                    <strong>🗣️ Communication & Organization</strong>
                    <div class="skills-list">
                        <span class="skill-tag">Client service</span>
                        <span class="skill-tag">Teamwork</span>
                        <span class="skill-tag">Time management</span>
                        <span class="skill-tag">Order coordination</span>
                        <span class="skill-tag">Working under pressure</span>
                        <span class="skill-tag">Responsibility</span>
                        <span class="skill-tag">English B2</span>
                    </div>
                </div>

                <div class="skill-cat">
                    <strong>🔍 Analytical & Personal</strong>
                    <div class="skills-list">
                        <span class="skill-tag">Attention to detail</span>
                        <span class="skill-tag">Critical thinking</span>
                        <span class="skill-tag">Logical thinking</span>
                        <span class="skill-tag">Fast adaptation</span>
                    </div>
                </div>

                <div class="skill-cat">
                    <strong>🖥️ Technical Skills</strong>
                    <div class="skills-list">
                        <span class="skill-tag">C / C++</span>
                        <span class="skill-tag">Python</span>
                        <span class="skill-tag">Java</span>
                        <span class="skill-tag">HTML/CSS</span>
                        <span class="skill-tag">MySQL basics</span>
                        <span class="skill-tag">Electronics basics</span>
                        <span class="skill-tag">MS Office</span>
                        <span class="skill-tag">Git / GitHub</span>
                    </div>
                </div>
            </div>

            <div class="interests">
                <div style="display: flex; gap: 0.6rem; align-items: center; margin-bottom: 1rem;">
                    <span style="font-size: 1.8rem;">✨</span>
                    <span style="font-weight: 700; font-size: 1.2rem;">Beyond the code</span>
                </div>
                <p>Since childhood, I've been curious about how things work — from simple devices to complex systems. That curiosity evolved into a passion for creating. Art and writing gave me an expressive side, but engineering brought the balance I needed.</p>
                <p style="margin-top: 0.75rem;">Today I love exploring emerging technologies and building things that matter. My ambitious nature pushes me to step into unfamiliar fields and challenge myself. I never leave work unfinished — and I'd be thrilled to share knowledge with young minds in a fun, engaging way.</p>
                <div style="margin-top: 1.2rem;">
                    <span class="badge">🔧 hardware curiosity</span>
                    <span class="badge">🎨 creative balance</span>
                    <span class="badge">📖 lifelong learning</span>
                </div>
            </div>

            <div class="card" style="margin-top: 1rem;">
                <div class="section-title">
                    <span>🐙</span> GitHub & goals
                </div>
                <div class="skills-list">
                    <span class="skill-tag">🌱 learning open source</span>
                    <span class="skill-tag">📌 building projects in C/Python</span>
                    <span class="skill-tag">🤝 open for collaboration</span>
                </div>
                <p style="margin-top: 0.9rem; font-size: 0.85rem; color:#94a3b8;">
                    🚀 Currently leveling up my Git skills and preparing my first portfolio projects. 
                    I'm actively looking for internships or junior dev opportunities where I can grow and contribute.
                </p>
            </div>
        </div>
    </div>

    <footer>
        ⚡ Computer Engineering student @ TU-Sofia | Open for internships & tech conversations<br>
        ✨ "Leave no work unfinished — and make learning exciting."
    </footer>
</div>
</body>
</html>

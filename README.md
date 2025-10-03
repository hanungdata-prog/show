<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Hanung Akbar Pramusintho — DevOps & Software Engineer</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0f1724; /* dark navy */
      --card:#111827;
      --muted:#9ca3af;
      --accent:#7c3aed; /* purple */
      --glass: rgba(255,255,255,0.04);
      color-scheme: dark;
      font-family: Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      background: linear-gradient(180deg, #071026 0%, var(--bg) 100%);
      color:#e6edf3;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      display:flex;align-items:center;justify-content:center;padding:48px;
    }

    .container{width:100%;max-width:980px}
    .card{
      background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border-radius:14px;padding:28px;box-shadow:0 10px 30px rgba(2,6,23,0.6);
      backdrop-filter: blur(6px);border:1px solid rgba(255,255,255,0.03)
    }

    .head{display:flex;gap:20px;align-items:center}
    .avatar{
      width:108px;height:108px;border-radius:14px;flex:0 0 108px;overflow:hidden;border:2px solid rgba(255,255,255,0.04);
      background:linear-gradient(135deg,var(--accent),#06b6d4);display:flex;align-items:center;justify-content:center;font-weight:800;font-size:36px;color:white
    }

    .title{flex:1}
    h1{margin:0;font-size:24px}
    .subtitle{margin:6px 0 0;color:var(--muted);font-weight:600}

    .bio{display:flex;gap:18px;margin-top:22px;align-items:flex-start}
    .left{flex:1}
    .right{width:320px}

    .pill{display:inline-flex;gap:8px;align-items:center;padding:8px 12px;border-radius:999px;background:var(--glass);color:var(--muted);font-weight:600}

    .skills{display:flex;flex-wrap:wrap;gap:10px;margin-top:12px}
    .skill{background:linear-gradient(90deg,rgba(255,255,255,0.02),rgba(255,255,255,0.01));padding:8px 12px;border-radius:10px;font-weight:600;color:var(--muted);font-size:13px;border:1px solid rgba(255,255,255,0.02)}

    .stats{display:flex;gap:12px;margin-top:16px}
    .stat-card{flex:1;background:linear-gradient(180deg, rgba(255,255,255,0.01), rgba(255,255,255,0.02));padding:12px;border-radius:12px;text-align:center;border:1px solid rgba(255,255,255,0.02)}
    .stat-card small{display:block;color:var(--muted);font-weight:600}
    .stat-card strong{display:block;font-size:18px;margin-top:6px}

    .projects{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:12px;margin-top:18px}
    .project{background:linear-gradient(180deg, rgba(255,255,255,0.01), rgba(255,255,255,0.02));padding:14px;border-radius:12px;border:1px solid rgba(255,255,255,0.02)}
    .project h4{margin:0 0 8px}
    .project p{margin:0;color:var(--muted);font-size:13px}

    .socials{display:flex;gap:8px;flex-wrap:wrap;margin-top:18px}
    .btn{display:inline-flex;align-items:center;gap:8px;padding:8px 12px;border-radius:10px;background:linear-gradient(90deg,var(--accent),#06b6d4);color:white;text-decoration:none;font-weight:700}
    .outline{background:transparent;border:1px solid rgba(255,255,255,0.04);color:var(--muted);font-weight:700}

    footer{margin-top:18px;color:var(--muted);font-size:13px;text-align:center}

    /* small screens */
    @media (max-width:720px){
      .head{flex-direction:row}
      .right{width:100%}
      .bio{flex-direction:column}
    }

    /* typing animation */
    .typing{color:var(--accent);font-weight:800}
    .cursor{display:inline-block;width:10px;height:18px;background:linear-gradient(90deg,var(--accent),#06b6d4);margin-left:6px;border-radius:3px;animation:blink 1s steps(2) infinite}
    @keyframes blink{50%{opacity:0}}
  </style>
</head>
<body>
  <div class="container">
    <div class="card">
      <div class="head">
        <div class="avatar">HA</div>
        <div class="title">
          <h1>Hanung Akbar Pramusintho <span style="color:var(--muted);font-weight:600">— DevOps & Software Engineer</span></h1>
          <div class="subtitle">Building resilient systems, automations & efficient CI/CD pipelines.</div>
        </div>
        <div style="display:flex;flex-direction:column;gap:8px;align-items:flex-end">
          <div class="pill">📍 Indonesia</div>
          <a class="pill outline" href="mailto:hanungpramusintho@gmail.com">✉️ Contact</a>
        </div>
      </div>

      <div class="bio">
        <div class="left">
          <div style="display:flex;align-items:center;gap:12px;">
            <div class="typing">Hi, I build cloud-native apps & DevOps workflows</div>
            <div class="cursor"></div>
          </div>

          <p style="color:var(--muted);margin-top:12px;line-height:1.6">Experienced in containerization, orchestration, infrastructure as code, and automation. I enjoy turning manual ops into repeatable pipelines and optimizing developer experience.</p>

          <div class="skills" aria-hidden>
            <div class="skill">Docker</div>
            <div class="skill">Kubernetes</div>
            <div class="skill">Terraform</div>
            <div class="skill">GitOps</div>
            <div class="skill">CI/CD</div>
            <div class="skill">React</div>
            <div class="skill">Go</div>
            <div class="skill">Python</div>
          </div>

          <div class="stats">
            <div class="stat-card"><small>Top Language</small><strong>JavaScript</strong></div>
            <div class="stat-card"><small>Active</small><strong>Open to collaborate</strong></div>
            <div class="stat-card"><small>Current</small><strong>GoWak</strong></div>
          </div>

          <div style="margin-top:16px">
            <h3 style="margin:0 0 8px">Featured Projects</h3>
            <div class="projects">
              <a class="project" href="https://github.com/hanungdata-prog/GoWak" target="_blank">
                <h4>GoWak</h4>
                <p>Delivery microservice & frontend integration — CI/CD, Docker, Kubernetes manifests.</p>
              </a>
              <a class="project" href="#" class="project">
                <h4>Infra-Playbook</h4>
                <p>Terraform modules & Ansible playbooks for repeatable infra provisioning.</p>
              </a>
              <a class="project" href="#" class="project">
                <h4>DevOps-Toolkit</h4>
                <p>Collection of scripts and GitHub Actions to accelerate onboarding and testing.</p>
              </a>
            </div>
          </div>

        </div>

        <div class="right">
          <div style="display:flex;flex-direction:column;gap:12px">
            <div style="padding:14px;border-radius:12px;background:linear-gradient(180deg, rgba(255,255,255,0.01), rgba(255,255,255,0.02));border:1px solid rgba(255,255,255,0.02)">
              <h4 style="margin:0 0 8px">Quick Stats</h4>
              <img src="https://github-readme-stats.vercel.app/api?username=hanungdata-prog&show_icons=true&theme=react&hide_border=true" alt="stats" style="width:100%;border-radius:8px" />
            </div>

            <div style="padding:14px;border-radius:12px;background:linear-gradient(180deg, rgba(255,255,255,0.01), rgba(255,255,255,0.02));border:1px solid rgba(255,255,255,0.02)">
              <h4 style="margin:0 0 8px">Connect</h4>
              <div class="socials">
                <a class="btn" href="mailto:hanungpramusintho@gmail.com">✉️ Email</a>
                <a class="btn" href="https://linkedin.com/in/hanung-akbar-pramusintho" target="_blank">🔗 LinkedIn</a>
                <a class="btn" href="https://instagram.com/hanunggakbar" target="_blank">📸 Instagram</a>
                <a class="btn" href="https://discord.gg/692037233644929075" target="_blank">💬 Discord</a>
              </div>
            </div>

            <div style="padding:14px;border-radius:12px;background:linear-gradient(180deg, rgba(255,255,255,0.01), rgba(255,255,255,0.02));border:1px solid rgba(255,255,255,0.02)">
              <h4 style="margin:0 0 8px">Want to work together?</h4>
              <p style="margin:0;color:var(--muted);font-size:13px">I'm open to short-term gigs and collaborations on DevOps, infra automation, and frontend integrations. Let's chat!</p>
            </div>

          </div>
        </div>
      </div>

      <footer>Designed with ❤️ — Feel free to copy & adapt. Last updated: Oct 3, 2025</footer>
    </div>
  </div>
</body>
</html>

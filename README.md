<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Kaue Guedes — Desenvolvedor</title>
  <meta name="description" content="Perfil profissional — Kaue Guedes. Desenvolvedor em Análise e Desenvolvimento de Sistemas. Projetos, skills e contato." />
  <meta property="og:title" content="Kaue Guedes — Desenvolvedor" />
  <meta property="og:description" content="Portfólio e perfil profissional de Kaue Guedes. Projetos, tecnologias e contato." />
  <meta property="og:type" content="website" />
  <style>
    :root{
      --bg:#0f1724; --card:#0b1220; --muted:#94a3b8; --accent:#06b6d4; --glass:rgba(255,255,255,0.03);
      --maxw:950px; --radius:14px; --gap:18px; color-scheme: dark;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0; font-family:Inter, ui-sans-serif, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
      background:linear-gradient(180deg,#071027 0%, #071226 60%); color:#e6eef8; -webkit-font-smoothing:antialiased;
      display:flex; align-items:flex-start; justify-content:center; padding:48px 20px;
    }
    .wrap{width:100%; max-width:var(--maxw)}
    header{display:flex; gap:var(--gap); align-items:center; margin-bottom:20px}
    .avatar{
      width:120px; height:120px; border-radius:18px; background:linear-gradient(135deg,var(--accent),#7c3aed);
      display:flex; align-items:center; justify-content:center; font-weight:700; font-size:28px; color:#042029;
      box-shadow:0 6px 30px rgba(2,6,23,0.6);
      flex-shrink:0;
    }
    .meta{
      display:flex; flex-direction:column; gap:8px;
    }
    h1{margin:0;font-size:20px}
    .title-sub{display:flex; gap:12px; align-items:center; flex-wrap:wrap}
    .role{color:var(--muted); font-size:14px}
    .links{display:flex; gap:8px}
    .btn{background:var(--glass); padding:8px 12px; border-radius:10px; color:inherit; text-decoration:none; font-size:14px; border:1px solid rgba(255,255,255,0.03)}

    main{display:grid; grid-template-columns:1fr 360px; gap:18px}
    @media (max-width:920px){main{grid-template-columns:1fr} header{flex-direction:row} .avatar{width:96px;height:96px}}

    .card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); padding:18px; border-radius:var(--radius); box-shadow:0 8px 30px rgba(2,6,23,0.6); border:1px solid rgba(255,255,255,0.03)}

    /* Left column */
    .about p{color:var(--muted); line-height:1.6; margin-top:8px}
    .projects{display:flex; flex-direction:column; gap:12px; margin-top:14px}
    .project{display:flex; gap:12px; align-items:flex-start}
    .project .thumb{width:84px; height:56px; border-radius:10px; background:linear-gradient(90deg,#0b1220,#071022); display:flex; align-items:center; justify-content:center; font-size:12px; color:var(--muted)}
    .project h3{margin:0;font-size:15px}
    .project p{margin:6px 0 0 0; color:var(--muted); font-size:13px}

    /* Right column */
    .side{display:flex; flex-direction:column; gap:12px}
    .skills{display:flex; flex-wrap:wrap; gap:8px}
    .skill{padding:6px 10px; background:rgba(255,255,255,0.03); border-radius:10px; font-size:13px; color:var(--muted)}
    .contact a{display:block; text-decoration:none; color:var(--accent); font-weight:600}

    footer{margin-top:18px; text-align:center; color:var(--muted); font-size:13px}

    /* small helpers */
    .muted{color:var(--muted)}
    .row{display:flex; gap:8px; align-items:center}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="avatar" aria-hidden="true">KG</div>
      <div class="meta">
        <div class="title-sub">
          <h1>Kaue Guedes</h1>
          <span class="role">Estudante de Análise e Desenvolvimento de Sistemas • Front-end & Python</span>
        </div>
        <div class="row links">
          <a class="btn" href="#projects">Projetos</a>
          <a class="btn" href="#contact">Contato</a>
          <a class="btn" href="https://github.com/SEU_USUARIO" target="_blank" rel="noopener noreferrer">GitHub</a>
        </div>
      </div>
    </header>

    <main>
      <section>
        <article class="card about">
          <h2>Sobre</h2>
          <p>Sou estudante de Análise e Desenvolvimento de Sistemas na FATEC-Sorocaba. Gosto de resolver problemas, construir interfaces limpas e aprender novas tecnologias. Estou focando em melhorar minhas habilidades em front-end, Python e desenvolvimento de APIs.</p>

          <div class="projects" id="projects">
            <h2 style="margin:0">Projetos escolhidos</h2>

            <!-- Projeto 1 -->
            <a class="project" href="https://github.com/SEU_USUARIO/PROJETO1" target="_blank" rel="noopener noreferrer">
              <div class="thumb">WEB</div>
              <div>
                <h3>Nome do Projeto 1</h3>
                <p class="muted">Pequena descrição — tecnologias: HTML, CSS, JavaScript. Destaque: responsividade e componente X.</p>
              </div>
            </a>

            <!-- Projeto 2 -->
            <a class="project" href="https://github.com/SEU_USUARIO/PROJETO2" target="_blank" rel="noopener noreferrer">
              <div class="thumb">API</div>
              <div>
                <h3>Nome do Projeto 2</h3>
                <p class="muted">Pequena descrição — tecnologias: Python, Flask/FastAPI. Destaque: endpoints, testes e CI.</p>
              </div>
            </a>

          </div>

          <div style="margin-top:16px; display:flex; gap:8px; flex-wrap:wrap">
            <a class="btn" href="#contact">Baixar CV (PDF)</a>
            <a class="btn" href="https://github.com/SEU_USUARIO?tab=repositories" target="_blank" rel="noopener noreferrer">Ver repositórios</a>
          </div>
        </article>

        <article class="card" style="margin-top:12px">
          <h2>Experiência & Educação</h2>
          <p class="muted" style="margin-top:8px">Estudante — FATEC-Sorocaba (Análise e Desenvolvimento de Sistemas). Projetos acadêmicos e pessoais com foco em desenvolvimento web.</p>
          <ul class="muted" style="margin-top:8px">
            <li>Trabalho X (opcional) — breve descrição</li>
            <li>Monitoria/Projeto acadêmico — breve descrição</li>
          </ul>
        </article>
      </section>

      <aside class="side">
        <div class="card">
          <h3>Skills</h3>
          <div class="skills">
            <span class="skill">HTML</span>
            <span class="skill">CSS</span>
            <span class="skill">JavaScript</span>
            <span class="skill">React (básico)</span>
            <span class="skill">Python</span>
            <span class="skill">Git & GitHub</span>
          </div>
        </div>

        <div class="card contact" id="contact">
          <h3>Contato</h3>
          <p class="muted">Disponível para estágios e projetos freelance. Abra uma issue em algum repositório para feedback, ou envie e‑mail.</p>
          <div style="margin-top:8px">
            <a href="mailto:seu.email@exemplo.com">seu.email@exemplo.com</a>
            <a href="https://www.linkedin.com/in/SEU_PERFIL" target="_blank" rel="noopener noreferrer" style="display:block; margin-top:6px">LinkedIn</a>
          </div>
        </div>

        <div class="card">
          <h3>Dicas rápidas</h3>
          <ul class="muted" style="margin-top:8px">
            <li>Mantenha o README de cada repositório claro e com GIF/screenshot.</li>
            <li>Use issues e templates para organização.</li>
            <li>Adicione GitHub Actions para CI em projetos maiores.</li>
          </ul>
        </div>
      </aside>
    </main>

    <footer>
      Feito com ❤️ — personalize este template e publique via GitHub Pages.
    </footer>
  </div>
</body>
</html>


<!--
**kauezaun/kauezaun** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

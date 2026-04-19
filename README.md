
<style>
  @import url('https://fonts.googleapis.com/css2?family=Syne:wght@400;700;800&family=DM+Mono:wght@400;500&display=swap');

  .profile-root {
    font-family: 'Syne', sans-serif;
    padding: 2rem 0;
    max-width: 680px;
  }

  .header-section {
    display: flex;
    align-items: flex-start;
    gap: 1.5rem;
    margin-bottom: 2rem;
  }

  .avatar {
    width: 72px;
    height: 72px;
    border-radius: 50%;
    background: linear-gradient(135deg, #1D9E75, #185FA5);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 26px;
    font-weight: 800;
    color: #fff;
    flex-shrink: 0;
    letter-spacing: -1px;
  }

  .header-text h1 {
    font-size: 22px;
    font-weight: 800;
    margin: 0 0 4px;
    color: var(--color-text-primary);
    letter-spacing: -0.5px;
  }

  .header-text .roles {
    display: flex;
    gap: 8px;
    flex-wrap: wrap;
  }

  .role-badge {
    font-size: 12px;
    font-weight: 400;
    padding: 3px 10px;
    border-radius: 20px;
    font-family: 'DM Mono', monospace;
  }

  .role-dev { background: #E1F5EE; color: #0F6E56; }
  .role-full { background: #E6F1FB; color: #185FA5; }

  .divider {
    border: none;
    border-top: 0.5px solid var(--color-border-tertiary);
    margin: 1.5rem 0;
  }

  .links-row {
    display: flex;
    gap: 10px;
    flex-wrap: wrap;
    margin-bottom: 1.5rem;
  }

  .link-btn {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    padding: 7px 14px;
    border-radius: 8px;
    font-size: 13px;
    font-weight: 500;
    text-decoration: none;
    cursor: pointer;
    border: 0.5px solid var(--color-border-secondary);
    background: var(--color-background-primary);
    color: var(--color-text-primary);
    font-family: 'Syne', sans-serif;
    transition: background 0.15s, transform 0.1s;
  }
  .link-btn:hover { background: var(--color-background-secondary); }
  .link-btn:active { transform: scale(0.97); }

  .link-gmail { border-color: #D14836; color: #D14836; }
  .link-linkedin { border-color: #0077B5; color: #0077B5; }
  .link-portfolio { border-color: #0F6E56; color: #0F6E56; }

  .link-icon { width: 14px; height: 14px; }

  .section-label {
    font-size: 11px;
    font-weight: 500;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    color: var(--color-text-tertiary);
    font-family: 'DM Mono', monospace;
    margin-bottom: 12px;
  }

  .tech-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin-bottom: 1.5rem;
  }

  .tech-card {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 6px;
    padding: 14px 16px;
    border-radius: var(--border-radius-lg);
    border: 0.5px solid var(--color-border-tertiary);
    background: var(--color-background-primary);
    min-width: 72px;
    transition: border-color 0.15s, transform 0.1s;
    cursor: default;
  }
  .tech-card:hover {
    border-color: var(--color-border-primary);
    transform: translateY(-2px);
  }

  .tech-card img {
    width: 28px;
    height: 28px;
  }

  .tech-card span {
    font-size: 11px;
    color: var(--color-text-secondary);
    font-family: 'DM Mono', monospace;
  }

  .footer-quote {
    display: flex;
    align-items: center;
    gap: 10px;
    padding: 14px 16px;
    border-radius: var(--border-radius-md);
    background: var(--color-background-secondary);
    font-size: 13px;
    color: var(--color-text-secondary);
    margin-top: 0.5rem;
  }

  .quote-dot {
    width: 6px;
    height: 6px;
    border-radius: 50%;
    background: #1D9E75;
    flex-shrink: 0;
  }
</style>

<div class="profile-root">
  <div class="header-section">
    <div class="avatar">JP</div>
    <div class="header-text">
      <h1>Jonatas Prado</h1>
      <div class="roles">
        <span class="role-badge role-dev">Desenvolvedor Web</span>
        <span class="role-badge role-full">FullStack</span>
      </div>
    </div>
  </div>

  <div class="links-row">
    <a class="link-btn link-gmail" href="mailto:jonatasprado445@gmail.com">
      <svg class="link-icon" viewBox="0 0 24 24" fill="currentColor"><path d="M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/></svg>
      Gmail
    </a>
    <a class="link-btn link-linkedin" href="https://www.linkedin.com/in/jonatas-da-silva-prado-b03a81259/" target="_blank">
      <svg class="link-icon" viewBox="0 0 24 24" fill="currentColor"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/></svg>
      LinkedIn
    </a>
    <a class="link-btn link-portfolio" href="https://jonatasprado2610.github.io/Portfolio2.0/" target="_blank">
      <svg class="link-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="10"/><line x1="2" y1="12" x2="22" y2="12"/><path d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"/></svg>
      Portfólio
    </a>
  </div>

  <hr class="divider">

  <div class="section-label">Tecnologias &amp; Ferramentas</div>

  <div class="tech-grid">
    <div class="tech-card">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg" alt="JavaScript">
      <span>JavaScript</span>
    </div>
    <div class="tech-card">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="React">
      <span>React</span>
    </div>
    <div class="tech-card">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" alt="HTML5">
      <span>HTML5</span>
    </div>
    <div class="tech-card">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt="CSS3">
      <span>CSS3</span>
    </div>
    <div class="tech-card">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="C#">
      <span>C#</span>
    </div>
    <div class="tech-card">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg" alt="MySQL">
      <span>MySQL</span>
    </div>
  </div>

  <div class="footer-quote">
    <div class="quote-dot"></div>
    <span>Sempre buscando aprender e desenvolver projetos inovadores.</span>
  </div>
</div>

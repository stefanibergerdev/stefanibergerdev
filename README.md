<!--
  README de perfil — Tema: Cyberpunk / JARVIS — cores: rosa & preto
  - Compatível com GitHub (sem scripts externos ativos)
  - Coloque este README no repositório com nome igual ao seu username (stefanibergerdev) para que apareça no perfil
-->

<p align="center">
  <!-- BANNER SVG com efeito de inicialização (rosa/preto) -->
  <svg width="100%" height="240" viewBox="0 0 1200 240" preserveAspectRatio="xMidYMid slice" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Banner">
    <defs>
      <linearGradient id="g" x1="0" x2="1">
        <stop offset="0%" stop-color="#070007"/>
        <stop offset="50%" stop-color="#120014"/>
        <stop offset="100%" stop-color="#000000"/>
      </linearGradient>
      <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
        <feGaussianBlur stdDeviation="6" result="coloredBlur"/>
        <feMerge>
          <feMergeNode in="coloredBlur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>

    <rect width="1200" height="240" fill="url(#g)"/>

    <!-- grid lines -->
    <g opacity="0.04" stroke="#ff66b2" stroke-width="1">
      <line x1="0" y1="44" x2="1200" y2="44" />
      <line x1="0" y1="88" x2="1200" y2="88" />
      <line x1="0" y1="132" x2="1200" y2="132" />
      <line x1="0" y1="176" x2="1200" y2="176" />
    </g>

    <!-- Boot bars -->
    <g fill="#ff66b2" opacity="0.14">
      <rect x="40" y="180" width="520" height="2">
        <animate attributeName="opacity" values="0.0;0.14;0.0" dur="2.8s" repeatCount="indefinite" />
      </rect>
      <rect x="640" y="180" width="520" height="2">
        <animate attributeName="opacity" values="0.0;0.14;0.0" dur="3.2s" begin="0.9s" repeatCount="indefinite" />
      </rect>
    </g>

    <!-- Main Title -->
    <g transform="translate(40,36)" fill="#ffb3d9" font-family="Inter, 'Segoe UI', Roboto, Arial, Helvetica, sans-serif">
      <text x="0" y="40" font-size="36" font-weight="700" letter-spacing="1">stefanibergerdev</text>

      <!-- subtitle with typing effect (SVG animation reveals tspans) -->
      <text x="0" y="86" font-size="18" fill="#ff66b2" font-weight="500" >
        <tspan id="t1" opacity="0">Desenvolvedora • </tspan>
        <tspan id="t2" opacity="0">Python • </tspan>
        <tspan id="t3" opacity="0">Cibersegurança • </tspan>
        <tspan id="t4" opacity="0">Java</tspan>

        <animate
          xlink:href="#t1"
          attributeName="opacity"
          values="0;1"
          dur="0.6s"
          begin="0.4s"
          fill="freeze" />
        <animate
          xlink:href="#t2"
          attributeName="opacity"
          values="0;1"
          dur="0.6s"
          begin="1.2s"
          fill="freeze" />
        <animate
          xlink:href="#t3"
          attributeName="opacity"
          values="0;1"
          dur="0.6s"
          begin="2.0s"
          fill="freeze" />
        <animate
          xlink:href="#t4"
          attributeName="opacity"
          values="0;1"
          dur="0.6s"
          begin="2.8s"
          fill="freeze" />
      </text>
    </g>

    <!-- vertical scan -->
    <rect x="0" y="0" width="1200" height="240" opacity="0.02" fill="#ff66b2">
      <animate attributeName="y" values="0;240" dur="8s" repeatCount="indefinite" />
    </rect>

    <!-- Boot message -->
    <g transform="translate(40,140)" fill="#ffd6ea" font-family="'Fira Code', 'Roboto Mono', monospace" font-size="12" opacity="0.95">
      <text x="0" y="0">SISTEMA: Inicializando módulos...</text>
      <text x="0" y="20">• Carregando Interface IA •</text>
      <text x="0" y="40">• Sincronizando repositórios •</text>
      <text x="0" y="60" fill="#ff66b2">STATUS: PRONTO</text>
    </g>

  </svg>
</p>

<!-- Typing animation (SVG) -->
<p align="center">
  <svg width="640" height="48" viewBox="0 0 640 48" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Typing">
    <style>
      .t { font: 20px 'Inter', 'Segoe UI', Roboto, Arial, sans-serif; fill:#ffdff0; }
      .c { fill:#ff66b2; }
    </style>

    <text x="8" y="30" class="t">
      <tspan id="p1">Olá, eu sou Stefânia — </tspan>
      <tspan id="p2" class="c">criando soluções em Python / Java / segurança</tspan>
    </text>

    <!-- cursor blink -->
    <rect x="580" y="12" width="8" height="20" fill="#ff66b2">
      <animate attributeName="opacity" values="1;0;1" dur="1.2s" repeatCount="indefinite" />
    </rect>
  </svg>
</p>

---

## Sobre Mim
<p align="justify" style="color:#ffdff0">
  Olá — sou Stefânia. Trabalho com desenvolvimento em Python e Java e foco em cibersegurança aplicada (pentesting, automação e análise). Gosto de interfaces elegantes, automação segura e construir ferramentas que unem desempenho com governança. Meu perfil prioriza qualidade, segurança e automação.
</p>

---

## Tech Stack
<p>
  <img src="https://img.shields.io/badge/-Python-ff66b2?style=for-the-badge&logo=python&logoColor=fff" alt="Python"/>
  <img src="https://img.shields.io/badge/-Java-ff66b2?style=for-the-badge&logo=java&logoColor=fff" alt="Java"/>
  <img src="https://img.shields.io/badge/-Cybersecurity-ff66b2?style=for-the-badge&logo=owasp&logoColor=white" alt="Cibersegurança"/>
  <img src="https://img.shields.io/badge/-Docker-ff66b2?style=for-the-badge&logo=docker&logoColor=fff" alt="Docker"/>
  <img src="https://img.shields.io/badge/-Kubernetes-ff66b2?style=for-the-badge&logo=kubernetes&logoColor=fff" alt="K8s"/>
  <img src="https://img.shields.io/badge/-Linux-ff66b2?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
</p>

---

## Ferramentas
<p>
  <img src="https://img.shields.io/badge/-VSCode-ff66b2?style=for-the-badge&logo=visual-studio-code&logoColor=fff" alt="vscode" />
  <img src="https://img.shields.io/badge/-GitHub-ff66b2?style=for-the-badge&logo=github&logoColor=fff" alt="github" />
  <img src="https://img.shields.io/badge/-BurpSuite-ff66b2?style=for-the-badge&logo=burpsuite&logoColor=white" alt="burp" />
  <img src="https://img.shields.io/badge/-Metasploit-ff66b2?style=for-the-badge&logo=metasploit&logoColor=fff" alt="metasploit" />
  <img src="https://img.shields.io/badge/-Postman-ff66b2?style=for-the-badge&logo=postman&logoColor=fff" alt="postman" />
  <img src="https://img.shields.io/badge/-Jenkins-ff66b2?style=for-the-badge&logo=jenkins&logoColor=fff" alt="jenkins" />
</p>

---

## Projetos em Destaque
<table width="100%">
  <tr>
    <td width="33%" valign="top">
      <a href="https://github.com/stefanibergerdev/wpscan-automation" target="_blank">
        <img src="https://img.shields.io/badge/-WPScan_Auto-151515?style=for-the-badge&logo=wordpress&logoColor=white" alt="wpscan"/>
      </a>
      <p style="color:#ffdff0">Automação de varredura para WordPress com relatórios em HTML e alertas.</p>
      <p>
        <img src="https://img.shields.io/badge/Python-3.11-ff66b2?style=flat" alt="python" />
        <img src="https://img.shields.io/badge/Docker-Layout-ff66b2?style=flat" alt="docker" />
      </p>
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/stefanibergerdev/pentest-scripts" target="_blank">
        <img src="https://img.shields.io/badge/-Pentest_Scripts-0a0a0a?style=for-the-badge&logo=hackthebox&logoColor=white" alt="pentest"/>
      </a>
      <p style="color:#ffdff0">Coleção de scripts de pentest (scanners customizados, brute-forcers seguros, utils).</p>
      <p>
        <img src="https://img.shields.io/badge/Bash-Script-ff66b2?style=flat" alt="bash" />
        <img src="https://img.shields.io/badge/Python-3.11-ff66b2?style=flat" alt="python" />
      </p>
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/stefanibergerdev/java-backend-demo" target="_blank">
        <img src="https://img.shields.io/badge/-Java_Backend-ff66b2?style=for-the-badge&logo=openjdk&logoColor=white" alt="java"/>
      </a>
      <p style="color:#ffdff0">API RESTful em Java com autenticação e auditoria de segurança integrada.</p>
      <p>
        <img src="https://img.shields.io/badge/Spring-Boot-ff66b2?style=flat" alt="spring" />
        <img src="https://img.shields.io/badge/Postgres-ff66b2?style=flat" alt="postgres" />
      </p>
    </td>
  </tr>
</table>

---

## Objetivos Atuais (Terminal)
<div style="background:#0a0210;padding:14px;border-radius:12px;color:#ffdff0;font-family: 'Fira Code', 'Roboto Mono', monospace;">
  <div style="display:flex;align-items:center">
    <div style="width:10px;height:10px;border-radius:50%;background:#ff4da6;margin-right:8px"></div>
    <div style="width:10px;height:10px;border-radius:50%;background:#ffc0e6;margin-right:8px"></div>
    <div style="width:10px;height:10px;border-radius:50%;background:#ffb3d9"></div>
  </div>
  <pre style="margin-top:8px;color:#ffdff0">
$ ./mission_control.sh --status
>  [●] Finalizar automação de auditoria para pentests (Python)  [ETA: 2 semanas]
>  [●] Estudar e publicar PoC em cibersegurança (CVEs & hardening)  [ETA: 1 mês]
>  [○] Migrar demo Java para container multi-stage                    [ETA: 3 dias]
>  [○] Integrar pipeline CI/CD com checks de segurança automático   [ETA: 2 semanas]

$ echo "cursor:" && printf "\u25B6"
<span style="color:#ff66b2">_</span>
  </pre>
</div>

---

## Estatísticas & Atividade

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=stefanibergerdev&show_icons=true&theme=dark&hide_border=true&bg_color=000000" alt="GitHub Stats" />
  &nbsp;&nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=stefanibergerdev&layout=compact&theme=dark&hide_border=true&bg_color=000000" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=stefanibergerdev&theme=dark&hide_border=true" alt="streak" />
  &nbsp;
  <img src="https://activity-graph.herokuapp.com/graph?username=stefanibergerdev&theme=github-dark&area=true" width="420" alt="activity graph" />
</p>

---

## Troféus
<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=stefanibergerdev&theme=darkhub&no-frame=true&margin-w=10" alt="trophies" />
</p>

---

## Snake (Animação de Contributions)
<p align="center">
  <img src="https://raw.githubusercontent.com/Platane/snk/master/snake.svg?user=stefanibergerdev&theme=dark" width="100%" alt="snake" />
</p>

---

<!-- Redes sociais removidas conforme solicitado -->

---

<footer align="center" style="color:#ffb3d9">
  <p style="font-family: Inter, Arial, sans-serif; font-size:12px; color:#ffb3d9">
    Construído com ☕, Python, Java e foco em segurança — Design inspirado em interfaces de IA e estética Cyberpunk (Rosa & Preto).
  </p>
</footer>

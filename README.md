<div style="background-color: #0a0a0f; color: #00ff00; font-family: 'Courier New', monospace; padding: 20px;">
  <style>
    @keyframes glitch {
      0% { transform: translate(0) }
      20% { transform: translate(-2px, 2px) }
      40% { transform: translate(-2px, -2px) }
      60% { transform: translate(2px, 2px) }
      80% { transform: translate(2px, -2px) }
      100% { transform: translate(0) }
    }

    @keyframes neon-pulse {
      0% { text-shadow: 0 0 5px #00ff00, 0 0 10px #00ff00, 0 0 15px #00ff00; }
      50% { text-shadow: 0 0 10px #00ff00, 0 0 20px #00ff00, 0 0 30px #00ff00; }
      100% { text-shadow: 0 0 5px #00ff00, 0 0 10px #00ff00, 0 0 15px #00ff00; }
    }

    @keyframes scan-line {
      0% { transform: translateY(-100%) }
      100% { transform: translateY(100%) }
    }

    @keyframes typing {
      from { width: 0 }
      to { width: 100% }
    }

    .container {
      position: relative;
      overflow: hidden;
    }

    .container::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      height: 2px;
      background: rgba(0, 255, 0, 0.2);
      animation: scan-line 2s linear infinite;
    }

    .glitch {
      animation: glitch 0.5s infinite;
      animation-timing-function: steps(2);
    }

    .neon {
      animation: neon-pulse 2s infinite;
    }

    .typing {
      overflow: hidden;
      white-space: nowrap;
      border-right: 2px solid #00ff00;
      animation: typing 3.5s steps(40, end), blink-caret .75s step-end infinite;
    }

    .tech-icon {
      transition: transform 0.3s ease;
    }

    .tech-icon:hover {
      transform: scale(1.2);
      filter: drop-shadow(0 0 5px #00ff00);
    }

    .stats-card {
      border: 1px solid #00ff00;
      padding: 10px;
      margin: 10px;
      background: rgba(0, 255, 0, 0.1);
      transition: all 0.3s ease;
    }

    .stats-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 0 15px rgba(0, 255, 0, 0.5);
    }
  </style>

  <div class="container">
    <h1 class="glitch neon">_SYSTEM::ONLINE_ >> INITIATING_NEURAL_LINK [⚡]</h1>

    <div class="typing neon">>> IDENTITY_CONFIRMED: UTKARSH.GUPTA_v1.0</div>

    <h2 class="neon">NEURAL_SCAN.results</h2>

    <div class="stats-card">
      <p>>> SCANNING_SUBJECT_PROFILE...<br><br>
      🧠 STATUS: Final-year NetRunner specializing in digital architecture and system optimization<br><br>
      💾 CORE_SKILLS: <span class="neon">Neural Network Engineering (DSA)</span> && <span class="neon">Full-Stack Reality Construction</span><br><br>
      🔮 CURRENT_UPLOAD: Augmenting consciousness with <span class="neon">React</span> && <span class="neon">TypeScript</span> implementations<br><br>
      ⚡ DIRECTIVE: Seeking fellow hackers for reality-bending collaborations. Jack in and let's rewrite the matrix!</p>
    </div>

    <h2 class="neon">CYBERDECK_LOADOUT</h2>

    <div class="tech-stack">
      <img class="tech-icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="javascript.exe" />
      <img class="tech-icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="40" alt="typescript.sys" />
      <img class="tech-icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="40" alt="react.matrix" />
      <!-- [Previous tech stack icons remain the same] -->
    </div>

    <div class="stats-card">
      <div align="center">
        <img src="https://github-readme-stats.vercel.app/api?username=utkarsh240&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=synthwave&locale=en&hide_border=false&order=1" height="150" alt="neural.stats" />
        <img src="https://github-readme-stats.vercel.app/api/top-langs?username=utkarsh240&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=synthwave&hide_border=false&order=2" height="150" alt="code.matrix" />
      </div>
    </div>

    <div class="stats-card" align="center">
      <img src="https://profile-counter.glitch.me/utkarsh240/count.svg?" />
    </div>
  </div>
</div>

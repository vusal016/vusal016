<svg viewBox="0 0 1600 480" width="1600" height="480" xmlns="http://www.w3.org/2000/svg" font-family="Segoe UI, Helvetica, Arial, sans-serif">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0c0514"/>
      <stop offset="45%" stop-color="#140a24"/>
      <stop offset="100%" stop-color="#1b0b2e"/>
    </linearGradient>
    <linearGradient id="nameGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#c9a0ff"/>
      <stop offset="50%" stop-color="#9370DB"/>
      <stop offset="100%" stop-color="#8A2BE2"/>
    </linearGradient>
    <linearGradient id="lineGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#68217A" stop-opacity="0"/>
      <stop offset="30%" stop-color="#8A2BE2"/>
      <stop offset="70%" stop-color="#9370DB"/>
      <stop offset="100%" stop-color="#68217A" stop-opacity="0"/>
    </linearGradient>
    <radialGradient id="glow1" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#8A2BE2" stop-opacity="0.35"/>
      <stop offset="100%" stop-color="#8A2BE2" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="glow2" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#68217A" stop-opacity="0.45"/>
      <stop offset="100%" stop-color="#68217A" stop-opacity="0"/>
    </radialGradient>
    <linearGradient id="cardGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#241238"/>
      <stop offset="100%" stop-color="#170a26"/>
    </linearGradient>
  </defs>

  <!-- Background -->
  <rect width="1600" height="480" fill="url(#bg)"/>

  <!-- Ambient glows -->
  <circle cx="1450" cy="60" r="360" fill="url(#glow1)"/>
  <circle cx="120" cy="440" r="320" fill="url(#glow2)"/>
  <circle cx="850" cy="-80" r="300" fill="url(#glow2)"/>

  <!-- Subtle grid -->
  <g stroke="#9370DB" stroke-opacity="0.06" stroke-width="1">
    <line x1="0" y1="120" x2="1600" y2="120"/>
    <line x1="0" y1="240" x2="1600" y2="240"/>
    <line x1="0" y1="360" x2="1600" y2="360"/>
    <line x1="266" y1="0" x2="266" y2="480"/>
    <line x1="533" y1="0" x2="533" y2="480"/>
    <line x1="800" y1="0" x2="800" y2="480"/>
    <line x1="1066" y1="0" x2="1066" y2="480"/>
    <line x1="1333" y1="0" x2="1333" y2="480"/>
  </g>

  <!-- Floating code particles -->
  <g font-family="Consolas, Menlo, monospace" fill="#9370DB">
    <text x="70" y="70" font-size="15" fill-opacity="0.14">public sealed class BackendEngineer : IDeveloper</text>
    <text x="1090" y="420" font-size="14" fill-opacity="0.13">await app.RunAsync();</text>
    <text x="960" y="90" font-size="14" fill-opacity="0.11">services.AddScoped&lt;IUnitOfWork, UnitOfWork&gt;();</text>
    <text x="120" y="420" font-size="14" fill-opacity="0.12">dotnet build --configuration Release</text>
    <text x="620" y="450" font-size="15" fill-opacity="0.10">{ "architecture": "onion" }</text>
    <text x="1380" y="260" font-size="26" fill-opacity="0.14">{ }</text>
    <text x="40" y="250" font-size="26" fill-opacity="0.12">&lt;/&gt;</text>
    <text x="700" y="60" font-size="22" fill-opacity="0.10">;</text>
  </g>

  <!-- Hexagon accents (C# logo inspired) -->
  <g stroke="#8A2BE2" fill="none" stroke-width="1.5">
    <polygon points="1500,330 1540,353 1540,399 1500,422 1460,399 1460,353" stroke-opacity="0.35"/>
    <polygon points="1445,395 1473,411 1473,443 1445,459 1417,443 1417,411" stroke-opacity="0.2"/>
    <polygon points="90,95 118,111 118,143 90,159 62,143 62,111" stroke-opacity="0.25"/>
  </g>
  <text x="1478" y="387" font-size="26" font-weight="700" fill="#9370DB" fill-opacity="0.7" font-family="Consolas, monospace">C#</text>

  <!-- Left accent bar -->
  <rect x="96" y="150" width="5" height="130" rx="2.5" fill="url(#nameGrad)"/>

  <!-- Name & title -->
  <text x="130" y="205" font-size="64" font-weight="800" fill="url(#nameGrad)" letter-spacing="2">VUSAL MAMMADOV</text>
  <text x="132" y="252" font-size="26" font-weight="600" fill="#e8dcff" letter-spacing="6">.NET BACKEND DEVELOPER</text>
  <text x="132" y="295" font-size="17" fill="#a893c9" font-family="Consolas, Menlo, monospace">Building scalable, maintainable systems with ASP.NET Core &#8226; Onion Architecture &#8226; SQL Server</text>

  <!-- Stat cards -->
  <g>
    <rect x="130" y="330" width="230" height="92" rx="14" fill="url(#cardGrad)" stroke="#8A2BE2" stroke-opacity="0.5" stroke-width="1.5"/>
    <text x="152" y="372" font-size="30" font-weight="800" fill="#c9a0ff">30+</text>
    <text x="152" y="400" font-size="15" fill="#a893c9" letter-spacing="1">PUBLIC REPOSITORIES</text>

    <rect x="380" y="330" width="230" height="92" rx="14" fill="url(#cardGrad)" stroke="#8A2BE2" stroke-opacity="0.5" stroke-width="1.5"/>
    <text x="402" y="372" font-size="30" font-weight="800" fill="#c9a0ff">.NET 9</text>
    <text x="402" y="400" font-size="15" fill="#a893c9" letter-spacing="1">C# &#8226; EF CORE &#8226; WEB API</text>

    <rect x="630" y="330" width="230" height="92" rx="14" fill="url(#cardGrad)" stroke="#8A2BE2" stroke-opacity="0.5" stroke-width="1.5"/>
    <text x="652" y="372" font-size="30" font-weight="800" fill="#c9a0ff">5+</text>
    <text x="652" y="400" font-size="15" fill="#a893c9" letter-spacing="1">FEATURED PROJECTS</text>

    <rect x="880" y="330" width="230" height="92" rx="14" fill="url(#cardGrad)" stroke="#8A2BE2" stroke-opacity="0.5" stroke-width="1.5"/>
    <text x="902" y="372" font-size="30" font-weight="800" fill="#c9a0ff">100%</text>
    <text x="902" y="400" font-size="15" fill="#a893c9" letter-spacing="1">CLEAN ARCHITECTURE</text>
  </g>

  <!-- Bottom gradient line -->
  <rect x="0" y="474" width="1600" height="6" fill="url(#lineGrad)"/>

  <!-- Top thin line -->
  <rect x="0" y="0" width="1600" height="3" fill="url(#lineGrad)" opacity="0.6"/>
</svg>

<svg width="1180" height="610" viewBox="0 0 1180 610" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="accentGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#2563EB">
        <animate attributeName="stop-color" values="#2563EB;#06B6D4;#10B981;#2563EB" dur="8s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" stop-color="#06B6D4">
        <animate attributeName="stop-color" values="#06B6D4;#10B981;#2563EB;#06B6D4" dur="8s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#10B981">
        <animate attributeName="stop-color" values="#10B981;#2563EB;#06B6D4;#10B981" dur="8s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>

    <linearGradient id="asciiGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#2563EB">
        <animate attributeName="stop-color" values="#2563EB;#06B6D4;#2563EB" dur="5s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#06B6D4">
        <animate attributeName="stop-color" values="#06B6D4;#2563EB;#06B6D4" dur="5s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>

    <radialGradient id="glowBlue" cx="20%" cy="20%" r="60%">
      <stop offset="0%" stop-color="#2563EB" stop-opacity="0.28"/>
      <stop offset="100%" stop-color="#2563EB" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="glowCyan" cx="80%" cy="30%" r="55%">
      <stop offset="0%" stop-color="#06B6D4" stop-opacity="0.28"/>
      <stop offset="100%" stop-color="#06B6D4" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="glowEm" cx="50%" cy="90%" r="60%">
      <stop offset="0%" stop-color="#10B981" stop-opacity="0.28"/>
      <stop offset="100%" stop-color="#10B981" stop-opacity="0"/>
    </radialGradient>

    <filter id="softGlow" x="-60%" y="-60%" width="220%" height="220%">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <filter id="panelBlur" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="0.5"/>
    </filter>

    <clipPath id="canvasClip">
      <rect x="0" y="0" width="1180" height="610" rx="28"/>
    </clipPath>
    <clipPath id="leftClip">
      <rect x="24" y="24" width="410" height="562" rx="20"/>
    </clipPath>
  </defs>

  <g clip-path="url(#canvasClip)">
    <rect width="1180" height="610" fill="#FFFFFF"/>
    <rect width="1180" height="610" fill="url(#glowBlue)"/>
    <rect width="1180" height="610" fill="url(#glowCyan)"/>
    <rect width="1180" height="610" fill="url(#glowEm)"/>
    
        <circle cx="693" cy="184" r="1.6" fill="url(#accentGrad)" opacity="0.5">
          <animate attributeName="cy" values="184;138;184" dur="4.2s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.1;0.6;0.1" dur="4.2s" repeatCount="indefinite"/>
        </circle>
        <circle cx="222" cy="404" r="1.9" fill="url(#accentGrad)" opacity="0.5">
          <animate attributeName="cy" values="404;337;404" dur="8.5s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.1;0.6;0.1" dur="8.5s" repeatCount="indefinite"/>
        </circle>
        <circle cx="106" cy="118" r="1.7" fill="url(#accentGrad)" opacity="0.5">
          <animate attributeName="cy" values="118;43;118" dur="4.3s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.1;0.6;0.1" dur="4.3s" repeatCount="indefinite"/>
        </circle>
        <circle cx="899" cy="90" r="2.3" fill="url(#accentGrad)" opacity="0.5">
          <animate attributeName="cy" values="90;24;90" dur="4.6s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.1;0.6;0.1" dur="4.6s" repeatCount="indefinite"/>
        </circle>
        <circle cx="156" cy="436" r="1.1" fill="url(#accentGrad)" opacity="0.5">
          <animate attributeName="cy" values="436;391;436" dur="5.1s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.1;0.6;0.1" dur="5.1s" repeatCount="indefinite"/>
        </circle>
        <circle cx="302" cy="326" r="1.7" fill="url(#accentGrad)" opacity="0.5">
          <animate attributeName="cy" values="326;282;326" dur="6.7s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.1;0.6;0.1" dur="6.7s" repeatCount="indefinite"/>
        </circle>
        <circle cx="661" cy="215" r="1.2" fill="url(#accentGrad)" opacity="0.5">
          <animate attributeName="cy" values="215;147;215" dur="6.9s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.1;0.6;0.1" dur="6.9s" repeatCount="indefinite"/>
        </circle>
        <circle cx="792" cy="129" r="1.9" fill="url(#accentGrad)" opacity="0.5">
          <animate attributeName="cy" values="129;52;129" dur="4.3s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.1;0.6;0.1" dur="4.3s" repeatCount="indefinite"/>
        </circle>
        <circle cx="451" cy="538" r="2.1" fill="url(#accentGrad)" opacity="0.5">
          <animate attributeName="cy" values="538;478;538" dur="6.1s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.1;0.6;0.1" dur="6.1s" repeatCount="indefinite"/>
        </circle>
        <circle cx="983" cy="494" r="1.6" fill="url(#accentGrad)" opacity="0.5">
          <animate attributeName="cy" values="494;425;494" dur="5.2s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.1;0.6;0.1" dur="5.2s" repeatCount="indefinite"/>
        </circle>
        <circle cx="529" cy="113" r="1.9" fill="url(#accentGrad)" opacity="0.5">
          <animate attributeName="cy" values="113;54;113" dur="6.6s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.1;0.6;0.1" dur="6.6s" repeatCount="indefinite"/>
        </circle>
        <circle cx="949" cy="324" r="2.0" fill="url(#accentGrad)" opacity="0.5">
          <animate attributeName="cy" values="324;276;324" dur="4.4s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.1;0.6;0.1" dur="4.4s" repeatCount="indefinite"/>
        </circle>
        <circle cx="886" cy="198" r="2.2" fill="url(#accentGrad)" opacity="0.5">
          <animate attributeName="cy" values="198;149;198" dur="4.8s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.1;0.6;0.1" dur="4.8s" repeatCount="indefinite"/>
        </circle>
        <circle cx="893" cy="70" r="2.5" fill="url(#accentGrad)" opacity="0.5">
          <animate attributeName="cy" values="70;25;70" dur="4.4s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.1;0.6;0.1" dur="4.4s" repeatCount="indefinite"/>
        </circle>
        <circle cx="672" cy="378" r="2.1" fill="url(#accentGrad)" opacity="0.5">
          <animate attributeName="cy" values="378;335;378" dur="7.0s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.1;0.6;0.1" dur="7.0s" repeatCount="indefinite"/>
        </circle>
        <circle cx="964" cy="100" r="2.3" fill="url(#accentGrad)" opacity="0.5">
          <animate attributeName="cy" values="100;50;100" dur="8.7s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.1;0.6;0.1" dur="8.7s" repeatCount="indefinite"/>
        </circle>
        <circle cx="163" cy="92" r="2.2" fill="url(#accentGrad)" opacity="0.5">
          <animate attributeName="cy" values="92;48;92" dur="5.5s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.1;0.6;0.1" dur="5.5s" repeatCount="indefinite"/>
        </circle>
        <circle cx="942" cy="321" r="2.1" fill="url(#accentGrad)" opacity="0.5">
          <animate attributeName="cy" values="321;263;321" dur="8.4s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.1;0.6;0.1" dur="8.4s" repeatCount="indefinite"/>
        </circle>

    <!-- outer border shimmer -->
    <rect x="2" y="2" width="1176" height="606" rx="26" fill="none" stroke="url(#accentGrad)" stroke-width="1.4" opacity="0.6"/>

    <!-- LEFT PANEL: ASCII portrait -->
    <g clip-path="url(#leftClip)">
      <rect x="24" y="24" width="410" height="562" rx="20" fill="#F8FAFC" fill-opacity="0.85" filter="url(#panelBlur)"/>
      <rect x="24" y="24" width="410" height="562" rx="20" fill="none" stroke="rgba(15,23,42,.08)" stroke-width="1"/>
      <g>
        <animateTransform attributeName="transform" type="translate" values="0,0;0,-6;0,0" dur="4.5s" repeatCount="indefinite"/>
        
        <text x="70" y="150" font-family="'JetBrains Mono','Fira Code',monospace" font-size="15" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">     .-""""-.
          <animate attributeName="opacity" values="0;1" begin="0.5s" dur="0.5s" fill="freeze"/>
        </text>
        <text x="70" y="172" font-family="'JetBrains Mono','Fira Code',monospace" font-size="15" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">    /  _  _  \
          <animate attributeName="opacity" values="0;1" begin="0.78s" dur="0.5s" fill="freeze"/>
        </text>
        <text x="70" y="194" font-family="'JetBrains Mono','Fira Code',monospace" font-size="15" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">   |  (o)(o)  |
          <animate attributeName="opacity" values="0;1" begin="1.06s" dur="0.5s" fill="freeze"/>
        </text>
        <text x="70" y="216" font-family="'JetBrains Mono','Fira Code',monospace" font-size="15" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">   |    ..    |
          <animate attributeName="opacity" values="0;1" begin="1.34s" dur="0.5s" fill="freeze"/>
        </text>
        <text x="70" y="238" font-family="'JetBrains Mono','Fira Code',monospace" font-size="15" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">   |  '----'  |
          <animate attributeName="opacity" values="0;1" begin="1.62s" dur="0.5s" fill="freeze"/>
        </text>
        <text x="70" y="260" font-family="'JetBrains Mono','Fira Code',monospace" font-size="15" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">    \  ~~~~  /
          <animate attributeName="opacity" values="0;1" begin="1.9000000000000001s" dur="0.5s" fill="freeze"/>
        </text>
        <text x="70" y="282" font-family="'JetBrains Mono','Fira Code',monospace" font-size="15" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">     '-.__.-'
          <animate attributeName="opacity" values="0;1" begin="2.18s" dur="0.5s" fill="freeze"/>
        </text>
        <text x="70" y="304" font-family="'JetBrains Mono','Fira Code',monospace" font-size="15" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">    /|      |\
          <animate attributeName="opacity" values="0;1" begin="2.46s" dur="0.5s" fill="freeze"/>
        </text>
        <text x="70" y="326" font-family="'JetBrains Mono','Fira Code',monospace" font-size="15" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">   / |      | \
          <animate attributeName="opacity" values="0;1" begin="2.74s" dur="0.5s" fill="freeze"/>
        </text>
        <text x="70" y="348" font-family="'JetBrains Mono','Fira Code',monospace" font-size="15" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">  |  |      |  |
          <animate attributeName="opacity" values="0;1" begin="3.0200000000000005s" dur="0.5s" fill="freeze"/>
        </text>
        <text x="70" y="370" font-family="'JetBrains Mono','Fira Code',monospace" font-size="15" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">  |__|      |__|
          <animate attributeName="opacity" values="0;1" begin="3.3000000000000003s" dur="0.5s" fill="freeze"/>
        </text>
      </g>
      <!-- scanline sweep -->
      <rect x="24" y="24" width="410" height="4" fill="url(#accentGrad)" opacity="0.35">
        <animate attributeName="y" values="24;576;24" dur="6s" repeatCount="indefinite"/>
      </rect>
      <text x="70" y="440" font-family="'JetBrains Mono',monospace" font-size="14" fill="#475569">$ whoami_</text>
      <rect x="150" y="428" width="8" height="14" fill="#0F172A">
        <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite"/>
      </rect>
    </g>

    <!-- RIGHT PANEL: terminal -->
    <g>
      <rect x="458" y="24" width="698" height="562" rx="20" fill="#F8FAFC" fill-opacity="0.85" filter="url(#panelBlur)"/>
      <rect x="458" y="24" width="698" height="562" rx="20" fill="none" stroke="rgba(15,23,42,.08)" stroke-width="1"/>
      <rect x="458" y="24" width="698" height="562" rx="20" fill="none" stroke="url(#accentGrad)" stroke-width="1" opacity="0.5">
        <animate attributeName="opacity" values="0.2;0.6;0.2" dur="5s" repeatCount="indefinite"/>
      </rect>

      <!-- terminal top bar -->
      <circle cx="486" cy="52" r="6" fill="#EF4444"/>
      <circle cx="506" cy="52" r="6" fill="#F59E0B"/>
      <circle cx="526" cy="52" r="6" fill="#10B981"/>
      <text x="1130" y="57" text-anchor="end" font-family="'JetBrains Mono',monospace" font-size="12" fill="#475569">~/ibrahim-fakir</text>

      <text x="490" y="105" font-family="'Inter',sans-serif" font-size="22" fill="#0F172A">Hi 👋</text>
      <text x="490" y="140" font-family="'Inter',sans-serif" font-size="26" font-weight="700" fill="#0F172A">I'm Ibrahim Fakir</text>

      <text x="490" y="180" font-family="'JetBrains Mono',monospace" font-size="14" fill="#475569">$</text>
      
        <text x="660" y="180" font-family="'JetBrains Mono',monospace" font-size="19" font-weight="600" fill="#0F172A" opacity="0">
          <animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.05;0.85;1"
            begin="0.0s" dur="3.6s" repeatCount="indefinite"/>
          Full Stack Developer
        </text>
        <text x="660" y="180" font-family="'JetBrains Mono',monospace" font-size="19" font-weight="600" fill="#0F172A" opacity="0">
          <animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.05;0.85;1"
            begin="3.6s" dur="3.6s" repeatCount="indefinite"/>
          Open Source Contributor
        </text>
        <text x="660" y="180" font-family="'JetBrains Mono',monospace" font-size="19" font-weight="600" fill="#0F172A" opacity="0">
          <animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.05;0.85;1"
            begin="7.2s" dur="3.6s" repeatCount="indefinite"/>
          vibe coder
        </text>
      <rect x="960" y="165" width="9" height="18" fill="#0F172A">
        <animate attributeName="opacity" values="1;0;1" dur="0.9s" repeatCount="indefinite"/>
      </rect>

      
        <g opacity="0">
          <animate attributeName="opacity" values="0;1" begin="2.2s" dur="0.5s" fill="freeze"/>
          <text x="620" y="230" font-family="'Inter',sans-serif" font-size="14" fill="#475569">📍  Location:</text>
          <text x="785" y="230" font-family="'Inter',sans-serif" font-size="14" font-weight="600" fill="#0F172A">Pune, India</text>
        </g>
        <g opacity="0">
          <animate attributeName="opacity" values="0;1" begin="2.5500000000000003s" dur="0.5s" fill="freeze"/>
          <text x="620" y="262" font-family="'Inter',sans-serif" font-size="14" fill="#475569">🎓  Education:</text>
          <text x="785" y="262" font-family="'Inter',sans-serif" font-size="14" font-weight="600" fill="#0F172A">SYBCA · Indira University</text>
        </g>
        <g opacity="0">
          <animate attributeName="opacity" values="0;1" begin="2.9000000000000004s" dur="0.5s" fill="freeze"/>
          <text x="620" y="294" font-family="'Inter',sans-serif" font-size="14" fill="#475569">🎯  Current Focus:</text>
          <text x="785" y="294" font-family="'Inter',sans-serif" font-size="14" font-weight="600" fill="#0F172A">Full Stack Development</text>
        </g>
        <g opacity="0">
          <animate attributeName="opacity" values="0;1" begin="3.25s" dur="0.5s" fill="freeze"/>
          <text x="620" y="326" font-family="'Inter',sans-serif" font-size="14" fill="#475569">🔗  Portfolio:</text>
          <text x="785" y="326" font-family="'Inter',sans-serif" font-size="14" font-weight="600" fill="#0F172A">ibrahimfakir.dev</text>
        </g>
        <g opacity="0">
          <animate attributeName="opacity" values="0;1" begin="3.6s" dur="0.5s" fill="freeze"/>
          <text x="620" y="358" font-family="'Inter',sans-serif" font-size="14" fill="#475569">✉️  Email:</text>
          <text x="785" y="358" font-family="'Inter',sans-serif" font-size="14" font-weight="600" fill="#0F172A">hello@ibrahimfakir.dev</text>
        </g>
      
        <g opacity="0" transform="translate(620,405)">
          <animate attributeName="opacity" values="0;1" begin="3.5s" dur="0.4s" fill="freeze"/>
          <rect width="58" height="30" rx="15" fill="#F8FAFC" fill-opacity="0.85" stroke="url(#accentGrad)" stroke-width="1">
            <animate attributeName="stroke-width" values="1;1.6;1" dur="3s" begin="0.0s" repeatCount="indefinite"/>
          </rect>
          <text x="29.0" y="20.0" text-anchor="middle" font-family="'Inter',sans-serif" font-size="12.5" font-weight="600" fill="#0F172A">React</text>
        </g>
        <g opacity="0" transform="translate(688,405)">
          <animate attributeName="opacity" values="0;1" begin="3.62s" dur="0.4s" fill="freeze"/>
          <rect width="74" height="30" rx="15" fill="#F8FAFC" fill-opacity="0.85" stroke="url(#accentGrad)" stroke-width="1">
            <animate attributeName="stroke-width" values="1;1.6;1" dur="3s" begin="0.2s" repeatCount="indefinite"/>
          </rect>
          <text x="37.0" y="20.0" text-anchor="middle" font-family="'Inter',sans-serif" font-size="12.5" font-weight="600" fill="#0F172A">Next.js</text>
        </g>
        <g opacity="0" transform="translate(772,405)">
          <animate attributeName="opacity" values="0;1" begin="3.74s" dur="0.4s" fill="freeze"/>
          <rect width="74" height="30" rx="15" fill="#F8FAFC" fill-opacity="0.85" stroke="url(#accentGrad)" stroke-width="1">
            <animate attributeName="stroke-width" values="1;1.6;1" dur="3s" begin="0.4s" repeatCount="indefinite"/>
          </rect>
          <text x="37.0" y="20.0" text-anchor="middle" font-family="'Inter',sans-serif" font-size="12.5" font-weight="600" fill="#0F172A">Node.js</text>
        </g>
        <g opacity="0" transform="translate(856,405)">
          <animate attributeName="opacity" values="0;1" begin="3.86s" dur="0.4s" fill="freeze"/>
          <rect width="98" height="30" rx="15" fill="#F8FAFC" fill-opacity="0.85" stroke="url(#accentGrad)" stroke-width="1">
            <animate attributeName="stroke-width" values="1;1.6;1" dur="3s" begin="0.6000000000000001s" repeatCount="indefinite"/>
          </rect>
          <text x="49.0" y="20.0" text-anchor="middle" font-family="'Inter',sans-serif" font-size="12.5" font-weight="600" fill="#0F172A">TypeScript</text>
        </g>
        <g opacity="0" transform="translate(964,405)">
          <animate attributeName="opacity" values="0;1" begin="3.98s" dur="0.4s" fill="freeze"/>
          <rect width="82" height="30" rx="15" fill="#F8FAFC" fill-opacity="0.85" stroke="url(#accentGrad)" stroke-width="1">
            <animate attributeName="stroke-width" values="1;1.6;1" dur="3s" begin="0.8s" repeatCount="indefinite"/>
          </rect>
          <text x="41.0" y="20.0" text-anchor="middle" font-family="'Inter',sans-serif" font-size="12.5" font-weight="600" fill="#0F172A">Tailwind</text>
        </g>
        <g opacity="0" transform="translate(620,447)">
          <animate attributeName="opacity" values="0;1" begin="4.1s" dur="0.4s" fill="freeze"/>
          <rect width="66" height="30" rx="15" fill="#F8FAFC" fill-opacity="0.85" stroke="url(#accentGrad)" stroke-width="1">
            <animate attributeName="stroke-width" values="1;1.6;1" dur="3s" begin="1.0s" repeatCount="indefinite"/>
          </rect>
          <text x="33.0" y="20.0" text-anchor="middle" font-family="'Inter',sans-serif" font-size="12.5" font-weight="600" fill="#0F172A">Python</text>
        </g>
        <g opacity="0" transform="translate(696,447)">
          <animate attributeName="opacity" values="0;1" begin="4.22s" dur="0.4s" fill="freeze"/>
          <rect width="66" height="30" rx="15" fill="#F8FAFC" fill-opacity="0.85" stroke="url(#accentGrad)" stroke-width="1">
            <animate attributeName="stroke-width" values="1;1.6;1" dur="3s" begin="1.2000000000000002s" repeatCount="indefinite"/>
          </rect>
          <text x="33.0" y="20.0" text-anchor="middle" font-family="'Inter',sans-serif" font-size="12.5" font-weight="600" fill="#0F172A">Docker</text>
        </g>
        <g opacity="0" transform="translate(772,447)">
          <animate attributeName="opacity" values="0;1" begin="4.34s" dur="0.4s" fill="freeze"/>
          <rect width="42" height="30" rx="15" fill="#F8FAFC" fill-opacity="0.85" stroke="url(#accentGrad)" stroke-width="1">
            <animate attributeName="stroke-width" values="1;1.6;1" dur="3s" begin="1.4000000000000001s" repeatCount="indefinite"/>
          </rect>
          <text x="21.0" y="20.0" text-anchor="middle" font-family="'Inter',sans-serif" font-size="12.5" font-weight="600" fill="#0F172A">AWS</text>
        </g>
        <g opacity="0" transform="translate(824,447)">
          <animate attributeName="opacity" values="0;1" begin="4.46s" dur="0.4s" fill="freeze"/>
          <rect width="42" height="30" rx="15" fill="#F8FAFC" fill-opacity="0.85" stroke="url(#accentGrad)" stroke-width="1">
            <animate attributeName="stroke-width" values="1;1.6;1" dur="3s" begin="1.6s" repeatCount="indefinite"/>
          </rect>
          <text x="21.0" y="20.0" text-anchor="middle" font-family="'Inter',sans-serif" font-size="12.5" font-weight="600" fill="#0F172A">Git</text>
        </g>
        <g opacity="0" transform="translate(876,447)">
          <animate attributeName="opacity" values="0;1" begin="4.58s" dur="0.4s" fill="freeze"/>
          <rect width="58" height="30" rx="15" fill="#F8FAFC" fill-opacity="0.85" stroke="url(#accentGrad)" stroke-width="1">
            <animate attributeName="stroke-width" values="1;1.6;1" dur="3s" begin="1.8s" repeatCount="indefinite"/>
          </rect>
          <text x="29.0" y="20.0" text-anchor="middle" font-family="'Inter',sans-serif" font-size="12.5" font-weight="600" fill="#0F172A">Figma</text>
        </g>
      
        <g transform="translate(620,522)">
          <circle r="20" fill="#F8FAFC" fill-opacity="0.85" stroke="url(#accentGrad)" stroke-width="1.2" filter="url(#softGlow)">
            <animate attributeName="r" values="20;21.5;20" dur="2.6s" begin="0.0s" repeatCount="indefinite"/>
          </circle>
          <text x="0" y="5" text-anchor="middle" font-family="'Inter',sans-serif" font-size="11" font-weight="700" fill="#0F172A">GH</text>
        </g>
        <g transform="translate(676,522)">
          <circle r="20" fill="#F8FAFC" fill-opacity="0.85" stroke="url(#accentGrad)" stroke-width="1.2" filter="url(#softGlow)">
            <animate attributeName="r" values="20;21.5;20" dur="2.6s" begin="0.3s" repeatCount="indefinite"/>
          </circle>
          <text x="0" y="5" text-anchor="middle" font-family="'Inter',sans-serif" font-size="11" font-weight="700" fill="#0F172A">IN</text>
        </g>
        <g transform="translate(732,522)">
          <circle r="20" fill="#F8FAFC" fill-opacity="0.85" stroke="url(#accentGrad)" stroke-width="1.2" filter="url(#softGlow)">
            <animate attributeName="r" values="20;21.5;20" dur="2.6s" begin="0.6s" repeatCount="indefinite"/>
          </circle>
          <text x="0" y="5" text-anchor="middle" font-family="'Inter',sans-serif" font-size="11" font-weight="700" fill="#0F172A">TW</text>
        </g>
        <g transform="translate(788,522)">
          <circle r="20" fill="#F8FAFC" fill-opacity="0.85" stroke="url(#accentGrad)" stroke-width="1.2" filter="url(#softGlow)">
            <animate attributeName="r" values="20;21.5;20" dur="2.6s" begin="0.8999999999999999s" repeatCount="indefinite"/>
          </circle>
          <text x="0" y="5" text-anchor="middle" font-family="'Inter',sans-serif" font-size="11" font-weight="700" fill="#0F172A">PF</text>
        </g>
    </g>
  </g>
</svg>

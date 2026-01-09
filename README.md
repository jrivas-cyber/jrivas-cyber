<svg width="1200" height="300" viewBox="0 0 1200 300" xmlns="http://www.w3.org/2000/svg">

  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#0f2027"/>
      <stop offset="50%" stop-color="#203a43"/>
      <stop offset="100%" stop-color="#2c5364"/>
    </linearGradient>

    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="1200" height="300" fill="url(#bg)" />

  <!-- Credit Card -->
  <g transform="translate(160 150)" filter="url(#glow)">
    <rect x="-45" y="-30" rx="6" ry="6" width="90" height="60" fill="none" stroke="#00eaff" stroke-width="3"/>
    <rect x="-35" y="-10" width="50" height="6" fill="#00eaff"/>
    <text x="-20" y="20" font-size="14" fill="#00eaff" font-family="monospace">1234</text>
  </g>

  <!-- Dashed Line -->
  <line x1="250" y1="150" x2="950" y2="150" stroke="#00eaff" stroke-width="2" stroke-dasharray="8 10" opacity="0.4"/>

  <!-- Shield (Encryption) -->
  <g transform="translate(600 150)" filter="url(#glow)">
    <path d="M0 -42 L34 -26 V16 C34 38 0 60 0 60 C0 60 -34 38 -34 16 V-26 Z" fill="none" stroke="#00eaff" stroke-width="3"/>
    <rect x="-10" y="-2" width="20" height="18" rx="2" fill="#00eaff"/>
    <path d="M-6 -2 v-8 a6 6 0 0 1 12 0 v8" fill="none" stroke="#00eaff" stroke-width="2"/>
  </g>

  <!-- Server -->
  <g transform="translate(950 150)" filter="url(#glow)">
    <rect x="-35" y="-40" width="70" height="80" rx="4" fill="none" stroke="#00eaff" stroke-width="3"/>
    <rect x="-30" y="-35" width="60" height="12" rx="2" stroke="#00eaff" fill="none"/>
    <rect x="-30" y="-15" width="60" height="12" rx="2" stroke="#00eaff" fill="none"/>
    <rect x="-30" y="5" width="60" height="12" rx="2" stroke="#00eaff" fill="none"/>

    <circle cx="-25" cy="-29" r="2" fill="#00eaff"/>
    <circle cx="-15" cy="-29" r="2" fill="#00eaff"/>
    <circle cx="-5" cy="-29" r="2" fill="#00eaff"/>
    <circle cx="-25" cy="-9" r="2" fill="#00eaff"/>
    <circle cx="-15" cy="-9" r="2" fill="#00eaff"/>
    <circle cx="-5" cy="-9" r="2" fill="#00eaff"/>
    <circle cx="-25" cy="11" r="2" fill="#00eaff"/>
    <circle cx="-15" cy="11" r="2" fill="#00eaff"/>
    <circle cx="-5" cy="11" r="2" fill="#00eaff"/>
  </g>

  <!-- Animated Digits -->
  <g font-family="monospace" font-size="22" font-weight="bold" fill="#00eaff" text-anchor="middle">

    <!-- Digit 1 -->
    <text x="200" y="150">1
      <animate attributeName="x" values="200;560" dur="2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="1;0" dur="2s" repeatCount="indefinite"/>
    </text>
    <text x="560" y="150" opacity="0">*</
      <animate attributeName="x" values="560;950" dur="2s" begin="2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;1" dur="2s" begin="2s" repeatCount="indefinite"/>
    </text>

    <!-- Digit 2 -->
    <text x="220" y="155">2
      <animate attributeName="x" values="220;580" dur="2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="1;0" dur="2s" repeatCount="indefinite"/>
    </text>
    <text x="580" y="155" opacity="0">#
      <animate attributeName="x" values="580;970" dur="2s" begin="2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;1" dur="2s" begin="2s" repeatCount="indefinite"/>
    </text>

    <!-- Digit 3 -->
    <text x="240" y="145">3
      <animate attributeName="x" values="240;600" dur="2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="1;0" dur="2s" repeatCount="indefinite"/>
    </text>
    <text x="600" y="145" opacity="0">@ 
      <animate attributeName="x" values="600;990" dur="2s" begin="2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;1" dur="2s" begin="2s" repeatCount="indefinite"/>
    </text>

    <!-- Digit 4 -->
    <text x="260" y="150">4
      <animate attributeName="x" values="260;620" dur="2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="1;0" dur="2s" repeatCount="indefinite"/>
    </text>
    <text x="620" y="150" opacity="0">8
      <animate attributeName="x" values="620;1010" dur="2s" begin="2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;1" dur="2s" begin="2s" repeatCount="indefinite"/>
    </text>

  </g>

</svg>


<hr/>

# Welcome to my portfolio!

I have 4 years of working experience in PCI compliance and Cybersecurity. During my spare time, I enjoy tackling complex challenges through hands-on projects. From PCI compliance to vulnerability management and threat hunting, these projects allow me to keep up with evolving security threats and improve my skillset. Check out my work below!

<hr/>

| Skill                                                           | Associated project           |
|-----------------------------------------------------------------|------------------------------|
| Scoping your CDE                                                | <div align="center"><a href="https://github.com/jrivas-cyber/PCI-scoping-exercises">PCI Scoping Exercises</a></div> | 
| Managing roles & responsibilities (RACI)                        | <div align="center"><a href="https://github.com/jrivas-cyber/PCI-roles-responsibilities">PCI Roles & Responsibilities</a></div>|
| PCI security training for employees                              | <div align="center"><a href="https://github.com/jrivas-cyber/PCI-security-training">PCI Security Training</a></div>|
| Automate your PCI ASV scans                                     | <div align="center"><a href="https://github.com/jrivas-cyber/PCI-ASV-scans/blob/main/README.md">PCI ASV Scans</a></div>|
| Build a vulnerability management program                        | <div align="center"><a href="https://github.com/jrivas-cyber/vulnerability-management-program">Vulnerability Management Program</a></div>|
| Threat Hunting (Tor Browser Usage)                              | <div align="center"><a href="https://github.com/jrivas-cyber/Tor-browser-usage">Tor Browser Usage</a></div>|

## Connect with Me:
[<img align="left" alt="___________ | LinkedIn" width="100px" src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" />][linkedin]

[linkedin]: https://linkedin.com/in/jrivas-cyber/
<!--
<img width="35" alt="image" src="https://github.com/user-attachments/assets/2f41c7cd-5ea8-4475-b451-a37161b6c3fb"> 
<img width="35" alt="image" src="https://github.com/user-attachments/assets/77649969-9910-4994-8b96-74a116cfb2a8">
-->

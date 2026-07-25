<svg width="2100" height="700" viewBox="0 0 2100 700" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0" stop-color="#171021"/>
      <stop offset="0.55" stop-color="#110B18"/>
      <stop offset="1" stop-color="#0C0810"/>
    </linearGradient>
    <radialGradient id="amberGlow" cx="0.5" cy="0.5" r="0.5">
      <stop offset="0" stop-color="#E8A455" stop-opacity="0.34"/>
      <stop offset="0.55" stop-color="#B26E3A" stop-opacity="0.12"/>
      <stop offset="1" stop-color="#B26E3A" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="violetGlow" cx="0.5" cy="0.5" r="0.5">
      <stop offset="0" stop-color="#5A3E8C" stop-opacity="0.28"/>
      <stop offset="1" stop-color="#5A3E8C" stop-opacity="0"/>
    </radialGradient>
    <linearGradient id="nameAmber" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#F6C97C"/>
      <stop offset="0.55" stop-color="#E8A455"/>
      <stop offset="1" stop-color="#D98A3F"/>
    </linearGradient>
    <linearGradient id="nameIvory" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0" stop-color="#FBF6EC"/>
      <stop offset="1" stop-color="#D9CFC2"/>
    </linearGradient>
    <linearGradient id="glass" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0" stop-color="#2A1E3E" stop-opacity="0.92"/>
      <stop offset="0.5" stop-color="#1D1430" stop-opacity="0.92"/>
      <stop offset="1" stop-color="#241735" stop-opacity="0.92"/>
    </linearGradient>
    <linearGradient id="glassEdge" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0" stop-color="#F6C97C" stop-opacity="0.9"/>
      <stop offset="0.5" stop-color="#8A6BB0" stop-opacity="0.55"/>
      <stop offset="1" stop-color="#E8A455" stop-opacity="0.75"/>
    </linearGradient>
    <linearGradient id="cap" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0" stop-color="#F6C97C"/>
      <stop offset="0.5" stop-color="#D98A3F"/>
      <stop offset="1" stop-color="#A96326"/>
    </linearGradient>
    <linearGradient id="badgeFill" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#E8A455" stop-opacity="0.14"/>
      <stop offset="1" stop-color="#E8A455" stop-opacity="0.05"/>
    </linearGradient>
    <linearGradient id="mist" x1="0" y1="1" x2="0" y2="0">
      <stop offset="0" stop-color="#E8A455" stop-opacity="0.55"/>
      <stop offset="1" stop-color="#E8A455" stop-opacity="0"/>
    </linearGradient>
    <filter id="blur18" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="18"/>
    </filter>
    <filter id="blur6" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="6"/>
    </filter>
  </defs>

  <!-- ======== BACKGROUND ======== -->
  <rect width="2100" height="700" fill="url(#bg)"/>
  <ellipse cx="1640" cy="430" rx="560" ry="380" fill="url(#amberGlow)"/>
  <ellipse cx="120" cy="680" rx="520" ry="300" fill="url(#violetGlow)"/>
  <ellipse cx="2040" cy="60" rx="380" ry="260" fill="url(#violetGlow)"/>

  <!-- faint diffusion rings around the bottle -->
  <g fill="none" stroke="#E8A455">
    <circle cx="1640" cy="430" r="255" stroke-opacity="0.10" stroke-width="1.4"/>
    <circle cx="1640" cy="430" r="330" stroke-opacity="0.06" stroke-width="1.2"/>
    <circle cx="1640" cy="430" r="410" stroke-opacity="0.035" stroke-width="1.2"/>
  </g>

  <!-- sparse particles -->
  <g fill="#F6C97C">
    <circle cx="1258" cy="128" r="3.2" fill-opacity="0.5"/>
    <circle cx="1965" cy="205" r="2.6" fill-opacity="0.4"/>
    <circle cx="1330" cy="560" r="2.8" fill-opacity="0.35"/>
    <circle cx="2030" cy="470" r="3.4" fill-opacity="0.45"/>
    <circle cx="1520" cy="96" r="2.4" fill-opacity="0.35"/>
    <circle cx="1880" cy="640" r="2.6" fill-opacity="0.3"/>
  </g>
  <g fill="#8A6BB0">
    <circle cx="1150" cy="330" r="2.6" fill-opacity="0.45"/>
    <circle cx="1770" cy="120" r="3" fill-opacity="0.4"/>
    <circle cx="2058" cy="580" r="2.4" fill-opacity="0.4"/>
  </g>

  <!-- dot grid, bottom-left corner -->
  <g fill="#8A6BB0" fill-opacity="0.30">
    <circle cx="64" cy="600" r="2.4"/><circle cx="92" cy="600" r="2.4"/><circle cx="120" cy="600" r="2.4"/><circle cx="148" cy="600" r="2.4"/>
    <circle cx="64" cy="628" r="2.4"/><circle cx="92" cy="628" r="2.4"/><circle cx="120" cy="628" r="2.4"/><circle cx="148" cy="628" r="2.4"/>
    <circle cx="64" cy="656" r="2.4"/><circle cx="92" cy="656" r="2.4"/><circle cx="120" cy="656" r="2.4"/><circle cx="148" cy="656" r="2.4"/>
  </g>
  <!-- dot grid, top-right of left column -->
  <g fill="#E8A455" fill-opacity="0.28">
    <circle cx="1010" cy="70" r="2.4"/><circle cx="1038" cy="70" r="2.4"/><circle cx="1066" cy="70" r="2.4"/>
    <circle cx="1010" cy="98" r="2.4"/><circle cx="1038" cy="98" r="2.4"/><circle cx="1066" cy="98" r="2.4"/>
  </g>

  <!-- ================= LEFT : TEXT ================= -->

  <!-- eyebrow -->
  <rect x="120" y="99" width="52" height="4" rx="2" fill="#E8A455"/>
  <text x="192" y="110" font-family="JetBrains Mono" font-size="27" font-weight="500" letter-spacing="9" fill="#E8A455">FULL-STACK DEVELOPER</text>

  <!-- name -->
  <text x="114" y="222" font-family="Space Grotesk" font-size="112" font-weight="700" letter-spacing="1" fill="url(#nameIvory)">Mohamed</text>
  <text x="114" y="336" font-family="Space Grotesk" font-size="112" font-weight="700" letter-spacing="1" fill="url(#nameAmber)">Mahad Abdi</text>

  <!-- tagline -->
  <text x="120" y="404" font-family="Space Grotesk" font-size="35" font-weight="500" fill="#C9BFD6">Building complete products — web, mobile &amp; APIs</text>

  <!-- stack pills -->
  <g font-family="JetBrains Mono" font-size="24" font-weight="500">
    <rect x="120" y="446" width="132" height="52" rx="26" fill="#1C1428" stroke="#3A2B52" stroke-width="1.6"/>
    <text x="186" y="480" text-anchor="middle" fill="#EDE4F2">Node.js</text>

    <rect x="268" y="446" width="118" height="52" rx="26" fill="#1C1428" stroke="#3A2B52" stroke-width="1.6"/>
    <text x="327" y="480" text-anchor="middle" fill="#EDE4F2">React</text>

    <rect x="402" y="446" width="130" height="52" rx="26" fill="#1C1428" stroke="#3A2B52" stroke-width="1.6"/>
    <text x="467" y="480" text-anchor="middle" fill="#EDE4F2">Next.js</text>

    <rect x="548" y="446" width="132" height="52" rx="26" fill="#1C1428" stroke="#3A2B52" stroke-width="1.6"/>
    <text x="614" y="480" text-anchor="middle" fill="#EDE4F2">Flutter</text>

    <rect x="696" y="446" width="188" height="52" rx="26" fill="#1C1428" stroke="#3A2B52" stroke-width="1.6"/>
    <text x="790" y="480" text-anchor="middle" fill="#EDE4F2">PostgreSQL</text>
  </g>

  <!-- project badge -->
  <rect x="120" y="536" width="770" height="106" rx="22" fill="url(#badgeFill)" stroke="#E8A455" stroke-width="1.8" stroke-opacity="0.85"/>
  <!-- mini bottle icon -->
  <g>
    <rect x="152" y="566" width="46" height="52" rx="10" fill="none" stroke="#F6C97C" stroke-width="3"/>
    <rect x="166" y="552" width="18" height="10" rx="3" fill="#F6C97C"/>
    <path d="M161 596 h28" stroke="#F6C97C" stroke-width="3" stroke-linecap="round"/>
    <path d="M161 606 h18" stroke="#F6C97C" stroke-width="3" stroke-linecap="round" opacity="0.6"/>
  </g>
  <line x1="226" y1="560" x2="226" y2="618" stroke="#E8A455" stroke-opacity="0.45" stroke-width="1.6"/>
  <text x="252" y="586" font-family="Space Grotesk" font-size="36" font-weight="700" fill="#FBF6EC">misktayyib.store</text>
  <text x="252" y="624" font-family="Space Grotesk" font-size="26" font-weight="500" fill="#E8A455">multi-vendor fragrance marketplace — built by me</text>

  <!-- ================= RIGHT : PERFUME BOTTLE AS PRODUCT ================= -->

  <!-- mist rising from the bottle neck -->
  <g filter="url(#blur6)" fill="none" stroke="url(#mist)" stroke-width="5" stroke-linecap="round">
    <path d="M1640 250 C 1600 210, 1690 180, 1652 130 C 1625 96, 1668 70, 1650 40"/>
    <path d="M1668 252 C 1710 205, 1640 170, 1700 120 C 1735 92, 1706 60, 1726 30" opacity="0.7"/>
  </g>
  <g fill="#F6C97C">
    <circle cx="1648" cy="118" r="3.6" fill-opacity="0.8"/>
    <circle cx="1706" cy="86" r="2.8" fill-opacity="0.6"/>
    <circle cx="1662" cy="52" r="2.4" fill-opacity="0.5"/>
  </g>

  <!-- soft glow plate under bottle -->
  <ellipse cx="1640" cy="648" rx="270" ry="26" fill="#E8A455" fill-opacity="0.16" filter="url(#blur18)"/>

  <!-- cap + neck -->
  <rect x="1596" y="216" width="88" height="58" rx="12" fill="url(#cap)"/>
  <rect x="1596" y="238" width="88" height="6" fill="#7A4519" fill-opacity="0.55"/>
  <rect x="1613" y="272" width="54" height="34" rx="6" fill="#2A1E3E" stroke="url(#glassEdge)" stroke-width="2.4"/>

  <!-- bottle body -->
  <path d="M1520 342 Q1520 306 1556 306 L1724 306 Q1760 306 1760 342 L1760 600 Q1760 640 1720 640 L1560 640 Q1520 640 1520 600 Z"
        fill="url(#glass)" stroke="url(#glassEdge)" stroke-width="3"/>
  <!-- glass highlight -->
  <path d="M1544 350 Q1544 328 1566 328 L1580 328 L1580 618 L1566 618 Q1544 618 1544 596 Z" fill="#FBF6EC" fill-opacity="0.06"/>

  <!-- code inside the bottle: the marketplace's source -->
  <g stroke-linecap="round">
    <path d="M1552 372 h44"  stroke="#8A6BB0" stroke-width="9"/>
    <path d="M1606 372 h96"  stroke="#E8A455" stroke-width="9"/>
    <path d="M1568 400 h72"  stroke="#5FC6B0" stroke-width="9"/>
    <path d="M1650 400 h60"  stroke="#6E5F86" stroke-width="9"/>
    <path d="M1568 428 h120" stroke="#F6C97C" stroke-width="9"/>
    <path d="M1552 456 h58"  stroke="#6E5F86" stroke-width="9"/>
    <path d="M1620 456 h84"  stroke="#8A6BB0" stroke-width="9"/>
  </g>

  <!-- product label card inside the bottle -->
  <rect x="1550" y="492" width="180" height="122" rx="14" fill="#130D1E" stroke="#3A2B52" stroke-width="1.6"/>
  <rect x="1566" y="508" width="52" height="52" rx="10" fill="#2A1E3E"/>
  <path d="M1574 548 L1588 530 L1598 542 L1606 534 L1612 548 Z" fill="#E8A455"/>
  <circle cx="1580" cy="522" r="5" fill="#F6C97C"/>
  <path d="M1632 516 h84" stroke="#EDE4F2" stroke-width="8" stroke-linecap="round"/>
  <path d="M1632 538 h58" stroke="#6E5F86" stroke-width="7" stroke-linecap="round"/>
  <!-- stars -->
  <g font-family="Space Grotesk" font-size="21" fill="#F6C97C">
    <text x="1566" y="596">★★★★★</text>
  </g>
  <text x="1694" y="596" font-family="JetBrains Mono" font-size="20" font-weight="500" fill="#5FC6B0">$49</text>

  <!-- floating card: mini storefront window (top right) -->
  <g>
    <rect x="1840" y="118" width="216" height="150" rx="16" fill="#181026" stroke="#3A2B52" stroke-width="1.8"/>
    <circle cx="1864" cy="142" r="4.6" fill="#E8A455"/>
    <circle cx="1882" cy="142" r="4.6" fill="#8A6BB0"/>
    <circle cx="1900" cy="142" r="4.6" fill="#5FC6B0"/>
    <rect x="1858" y="162" width="86" height="64" rx="9" fill="#2A1E3E"/>
    <path d="M1870 214 L1886 192 L1898 204 L1906 196 L1914 214 Z" fill="#E8A455"/>
    <path d="M1956 172 h82" stroke="#EDE4F2" stroke-width="8" stroke-linecap="round"/>
    <path d="M1956 194 h58" stroke="#6E5F86" stroke-width="7" stroke-linecap="round"/>
    <rect x="1956" y="210" width="66" height="22" rx="11" fill="#E8A455"/>
    <path d="M1858 244 h180" stroke="#3A2B52" stroke-width="2"/>
  </g>

  <!-- floating card: cart / order chip (left of bottle) -->
  <g>
    <rect x="1332" y="238" width="150" height="66" rx="16" fill="#181026" stroke="#3A2B52" stroke-width="1.8"/>
    <path d="M1356 262 h8 l7 24 h26 l7 -18 h-36" fill="none" stroke="#F6C97C" stroke-width="3.4" stroke-linejoin="round" stroke-linecap="round"/>
    <circle cx="1374" cy="294" r="3.4" fill="#F6C97C"/>
    <circle cx="1398" cy="294" r="3.4" fill="#F6C97C"/>
    <path d="M1420 262 h40" stroke="#EDE4F2" stroke-width="7" stroke-linecap="round"/>
    <path d="M1420 282 h28" stroke="#6E5F86" stroke-width="6" stroke-linecap="round"/>
  </g>

  <!-- floating chip: code tag (bottom right) -->
  <g>
    <rect x="1874" y="428" width="120" height="82" rx="16" fill="#181026" stroke="#3A2B52" stroke-width="1.8"/>
    <text x="1934" y="482" text-anchor="middle" font-family="JetBrains Mono" font-size="34" font-weight="700" fill="#5FC6B0">&lt;/&gt;</text>
  </g>

  <!-- thin connector arcs -->
  <g fill="none" stroke="#E8A455" stroke-opacity="0.35" stroke-width="1.8" stroke-dasharray="2 9" stroke-linecap="round">
    <path d="M1482 288 C 1500 306, 1508 318, 1522 336"/>
    <path d="M1838 210 C 1800 240, 1780 268, 1758 306"/>
    <path d="M1872 462 C 1830 466, 1800 476, 1762 496"/>
  </g>
</svg>

# Software Developer/ Front-End/ Back-End/ UI UX and More...
## Hi, I’m Mohamed Mahad Abdi Aka MoHaji Abdi

I’m a Software Engineering Student & Developer passionate about building full-stack applications and learning cutting-edge technologies. I love working with both front-end and back-end, and I enjoy solving real-world problems with code.

# 🚀 Tech Stack

## Frontend:

###    1. HTML • CSS • JavaScript (ES6+)
  
###    2. React.js • Tailwind CSS • Bootstrap

## Backend:

  ###    1. Java (Spring Boot)
  
  ###    2. C# (.NET)
  
  ###    3. NodeJs

## Databases:

###    1. PostgreSQL • SQL Server
###    2. Mongo Db

## Other:

###   1.  Git • GitHub • REST APIs
###   2.  Git • GitLab •

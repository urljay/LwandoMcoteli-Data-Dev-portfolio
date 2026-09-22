A personal portfolio and resume site for Lwando Mcoteli (Urljay). The site has two switchable modes: Dev & Data (software development, AI automation, fintech infrastructure) and Accounting (finance/accounting-focused resume), toggled from a single UI without a page reload.

It showcases projects, technical skills, academic background, community work, hobbies, and an affiliate partners section for platforms used in trading and business operations (CFI Trade, Bridgement, Exness, Wise, Kinesis Money, XM.com, Binance, eToro).

Tech Stack

Built deliberately framework-free — no build step, no bundler, no dependencies to install:

HTML5 — semantic, single-page structure
CSS3 — custom properties (CSS variables) for theming, CSS Grid & Flexbox for layout, responsive breakpoints, no CSS framework
Vanilla JavaScript (ES6+) — no libraries or frameworks
IntersectionObserver for scroll-triggered reveal animations
HTML5 <canvas> for the animated hero circuit-particle background
Native DOM APIs for the mode switch (Dev/Accounting), mobile menu, scroll-spy navigation, and project filtering
Google Fonts — Space Grotesk, Inter, IBM Plex Mono
Hosting — static site, deployed via GitHub Pages

Project Structure
├── index.html      # Markup — all sections (hero, projects, skills, academic, community, affiliates, hobbies, about, contact)
├── style.css       # All styling, including CSS variables, animations, and responsive rules
└── script.js       # Content data, interactivity, and canvas animation
Why Vanilla?

No React, no build pipeline, no npm install — just open index.html in a browser or push to GitHub Pages and it works. Keeps the site fast, dependency-free, and easy to deploy or hand off.

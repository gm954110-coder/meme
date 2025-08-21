# SlothCoin ($SLOTH) Landing Page

A lightweight, responsive, SEO-friendly landing site for a meme cryptocurrency project. Built with plain HTML, TailwindCSS via CDN, and a tiny vanilla JS file. No build step required.

Features:
- Modern, mobile-first layout with smooth scrolling
- Sections: Header, Hero, About/Lore, Tokenomics (SVG donut), Roadmap, How to Buy, FAQ, Footer/Community
- Bright, fun color theme configured in Tailwind CDN setup
- Easy to customize text, colors, images, and links in code
- No frameworks, no dependencies; deploy on any static host

Quick Start:
- Open index.html directly in a browser, or serve the folder with a static server.
- Python: python3 -m http.server 8080 --directory /workspace
- Node: npx serve -l 8080 /workspace

Customize:
- Contract address: search for 0xYOURCONTRACTADDRESSHERE in index.html
- Ticker/Name: update SlothCoin and $SLOTH in index.html
- Colors: tweak Tailwind config in the tailwind.config block within index.html
- Mascot: replace emoji placeholders in Hero and Footer with your image/SVG
- Tokenomics: edit numbers and the SVG donut in the Tokenomics section
- Roadmap: update phases in the Roadmap cards
- How to Buy: set the DEX link URL
- Community links: set your X/Twitter, Discord, Telegram URLs in the footer

SEO:
- Edit <title>, <meta name="description">, and Open Graph tags in index.html
- Use a real social image for og:image

Notes:
- All text is inline in index.html for easy editing
- Tailwind is loaded via CDN; consider a build pipeline if you need advanced theming

License:
- MIT. Replace assets and branding with your own.
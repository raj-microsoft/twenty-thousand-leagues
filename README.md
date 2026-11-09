# Twenty Thousand Leagues

A cinematic, static literary descent with an original Canvas Nautilus. Live: https://raj-microsoft.github.io/twenty-thousand-leagues/

Open `index.html` directly or serve this directory. No install or build step. Deployed with GitHub Pages from main /.

## Guide research (2026-11-09)
Guide: **Divya's Themed AI Website Repos**, Divya — https://github.com/divyashrma18?tab=repositories

Studied two actual codebases, not screenshots:

- **batman** at `c128d36720cf470c742261d2c8ac5ce965a38b0a`: https://github.com/divyashrma18/batman/tree/c128d36720cf470c742261d2c8ac5ce965a38b0a/vite-project
  - Structure: Vite app, App → Hero → Navbar, component CSS, public image assets.
  - package.json: React 19.2.6, Vite 8.0.12, Framer Motion 12.40.0.
  - Hero.jsx: pointer coordinates smoothed in requestAnimationFrame; trail of circular masks; offscreen Canvas source-in compositing of two images. Staggered spring entrances for text and navbar.
  - Hero.css: theatrical display typography, serif supporting copy, whole-viewport image stage.
  - Adapted the principle of pointer-driven discovery and entrance orchestration. Did not copy code, imagery or franchise text.
- **stangerThings** at `16d960af742fe97499802f8e190c18a1a6686ee8`: https://github.com/divyashrma18/stangerThings/tree/16d960af742fe97499802f8e190c18a1a6686ee8/vite-project
  - Structure: same App/Hero/Navbar separation, two public images, component styles.
  - package.json: React 19.2.0, Vite 7.2.4, Framer Motion 12.23.26.
  - Hero.jsx: eased pointer movement driving CSS variables; hover/leave reveal state; staggered entrance variants.
  - Hero.css: overlapping radial mask-image gradients reveal a second world; large text and full-screen atmospheric backdrop.
  - Adapted soft-edged layered revelation as a searchlight that changes plankton color.

Neither inspected Hero implementation contains a loader, chapter scroll scenes or audio. These were checked explicitly, not assumed. This site adds its own scroll chapters and optional synthesized audio, and avoids a fake loading screen. Native Canvas, HTML/CSS and Web Animations replace the component framework and Framer Motion; no paid services were involved.

## Text and assets
Short quotes verified in Project Gutenberg ebook 164, https://www.gutenberg.org/ebooks/164 (text updated March 18, 2025). The catalog does not identify a translator. All four quotations are in Part I, Chapters X or XIII, cited on the page. Narrative writing and generated visuals are original. Depth is explicitly illustrative. Bodoni Moda and Figtree fonts are self-hosted with OFL licenses. No franchise IP or third-party image/music assets shipped.

## Verification
Headless Edge at 1440 × 900 and 390 × 900; screenshot inspection; no horizontal overflow; zero page errors; local fonts loaded; chapter anchor works; audio toggle and motion pause state work; reduced motion honored. Source links checked with HTTP GET. Impeccable detector run with findings corrected before publishing.

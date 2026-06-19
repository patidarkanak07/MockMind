# MockMind – AI‑Powered Mock Interview Coach

[![Live Demo](https://img.shields.io/badge/Live_Demo-Online-brightgreen?style=for-the-badge)](https://patidarkanak07.github.io/MockMind/)

## Overview
MockMind is a single‑page web app that lets you practice interview questions with AI feedback, webcam‑based body‑language telemetry, and a real‑time STAR‑method detector. All functionality lives in **`index.html`** – the CSS and JavaScript are inlined, so the app runs by simply opening the file in a browser.

## 🔗 Live Website Link
The working deployment of the website is available at:
**[https://patidarkanak07.github.io/MockMind/](https://patidarkanak07.github.io/MockMind/)**

---

## Features
- Choose a target role (e.g., Google, Oracle) and paste your resume.
- AI‑generated interview questions (7 questions by default).
- Real‑time answer quality meter and STAR‑method detection.
- Webcam telemetry panel that tracks posture, eye‑contact, and facial expressions.
- PDF feedback report card with scores, body‑language summary and improvement suggestions.

## How to Run Locally
1. **Clone the repository** (or download the ZIP) and open the folder.
   ```bash
   git clone https://github.com/patidarkanak07/MockMind.git
   cd MockMind
   ```
2. Open `index.html` in a modern browser (Chrome/Edge/Safari). No server is required.
3. Allow webcam access when prompted – the telemetry panel will appear on the left side.
4. Follow the on‑screen instructions to start an interview.

## Deployment
The app is hosted on **GitHub Pages**. To deploy any changes to GitHub Pages:
1. Push to the `main` branch:
   ```bash
   git push origin main
   ```
2. Make sure GitHub Pages is configured in your repository settings under **Settings > Pages** to deploy from the `/root` folder of the `main` branch.

## Development
If you wish to extend the app:
- Edit `index.html`; the CSS is in a `<style>` block and the JavaScript is in `<script>` tags.
- Add additional assets (images, fonts) to the repo and reference them with relative paths.
- Run `npm run dev` only if you convert the project to a framework later.

## License
MIT – feel free to fork and customize.


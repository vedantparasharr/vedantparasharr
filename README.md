<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=30&pause=1200&color=7BD0FF&center=true&vCenter=true&width=760&lines=Vedant+Parashar+|+Frontend+Developer;Exploring+the+MERN+Backend;Always+Learning+Through+Building" />

<br/>

<img src="https://github.com/vedantparasharr.png" alt="Vedant Parashar" width="128" style="border-radius:50%; border:3px solid rgba(123,208,255,0.18);" />

</div>

# Hi, I'm Vedant Parashar 👋

I am a frontend developer who is currently learning backend development with the MERN stack. I enjoy building real projects because that is how I understand concepts clearly and improve my skills.

---

## About Me

I come from a frontend background and spent my early learning days working with React. Tailwind was something I used occasionally in the beginning, but it has now become my go-to CSS framework because of its speed and clean workflow.

Right now, I am focused on backend development. I am connecting the frontend skills I already have with server logic, API design, authentication and databases. Every project helps me understand how a complete system works.

---

## Tech Stack

### Frontend

![HTML5](https://img.shields.io/badge/HTML5-F97316?style=for-the-badge\&logo=html5\&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-38BDF8?style=for-the-badge\&logo=css3\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-FEDE5D?style=for-the-badge\&logo=javascript\&logoColor=black)
![React](https://img.shields.io/badge/React-7BD0FF?style=for-the-badge\&logo=react\&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge\&logo=tailwind-css\&logoColor=white)

### Backend and Database

![Node.js](https://img.shields.io/badge/Nodejs-57A143?style=for-the-badge\&logo=node.js\&logoColor=white)
![Express](https://img.shields.io/badge/Express-1F2937?style=for-the-badge\&logo=express\&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-00ED64?style=for-the-badge\&logo=mongodb\&logoColor=white)

### Tools and Deployment

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge\&logo=git\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge\&logo=github\&logoColor=white)
![VSCode](https://img.shields.io/badge/VS%20Code-3C99D4?style=for-the-badge\&logo=visualstudiocode\&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-0D1117?style=for-the-badge\&logo=vercel\&logoColor=white)
![Render](https://img.shields.io/badge/Render-0D1117?style=for-the-badge\&logo=render\&logoColor=white)

---

## What I Build

I have completed several frontend projects using React. Recently, I started integrating backend features like routes, authentication and database operations. My pinned repositories include the projects I am most proud of, along with their source code and live demos.

---

## Currently Learning

I am currently learning backend development with the MERN stack.
Here are the things I am working on:

* MongoDB and Mongoose connection

* CRUD operations with real models

* Edit and update features

* Moving toward auth, roles, file uploads, and full backend projects

---

## GitHub Stats (updated widgets)

<div align="center">
<!-- streak widget -->
<img src="https://streak-stats.demolab.com?user=vedantparasharr&theme=tokyonight&hide_border=true" width="60%" />

<br/>

<img src="https://img.shields.io/github/followers/vedantparasharr?label=Follow&style=social" />

</div>

---

## Activity Heatmap

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=vedantparasharr&theme=github-dark&hide_border=true" />
</div>

---

## 3D / Snake Contribution Visual (working)

To make the 3D / snake animation work reliably the README should embed the generated SVG (or GIF) from a GitHub Action that runs daily and publishes the generated image to the `output` branch. Below is a ready-to-copy README snippet and a complete workflow you can add to your profile repository (the repository named exactly `vedantparasharr/vedantparasharr`).

### README embed (place where you want the snake to appear)

```html
<picture>
  <!-- dark-mode snake -->
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/vedantparasharr/vedantparasharr/output/github-contribution-grid-snake-dark.svg">
  <!-- light-mode snake -->
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/vedantparasharr/vedantparasharr/output/github-contribution-grid-snake.svg">
  <!-- fallback -->
  <img alt="GitHub Contribution Snake" src="https://raw.githubusercontent.com/vedantparasharr/vedantparasharr/output/github-contribution-grid-snake.svg" />
</picture>
```

> After the action finishes the two files (`github-contribution-grid-snake.svg` and `github-contribution-grid-snake-dark.svg`) will exist in the `output` branch and the `<picture>` tag above will automatically display them (dark/light aware).

### GitHub Actions workflow (add this as `.github/workflows/generate-snake.yml`)

```yaml
name: Generate Snake

# runs automatically and can also be triggered manually
on:
  schedule:
    - cron: '0 0 * * *' # runs daily at 00:00 UTC (change if you prefer more/less frequent)
  workflow_dispatch:

permissions:
  contents: write

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - name: Checkout
        uses: actions/checkout@v4

      - name: Run SNK (generate snake animation)
        uses: Platane/snk@v3
        with:
          # optional: pick output type svg or gif (default svg)
          format: svg
          # optional: set username; default is repository owner
          username: vedantparasharr

      - name: Commit and push to output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

**Notes & troubleshooting**

1. The workflow above uses `Platane/snk` (a well-known tool that converts your contribution grid into a snake animation). If you prefer a different action/template some community forks exist; the important part is that the action outputs files into a folder named `dist` and the `ghaction-github-pages` step copies that to the `output` branch.

2. If your action runs but the image looks wrong: check the Actions logs and make sure your repository permissions allow actions to write to the output branch (Repository Settings → Actions → Workflow permissions → "Allow GitHub Actions to create and approve pull requests" or set `contents: write`).

3. If the `output` branch is missing after a successful run, open the Action run logs; the `ghaction-github-pages` step will show whether it created/updated the `output` branch.

4. If you want a dark-only or custom-colored version, `Platane/snk` supports theme customization via environment variables or inputs — check the action's README for `--colors` style options.

---

## Featured Projects

Here are three projects that represent my recent work.

### 🛒 EasyStore

**A simple and clean ecommerce project**
GitHub: [https://github.com/vedantparasharr/EasyStore](https://github.com/vedantparasharr/EasyStore)

---

### 💬 AriaChat

**A basic chat style frontend UI with smooth interactions**
GitHub: [https://github.com/vedantparasharr/AriaChat](https://github.com/vedantparasharr/AriaChat)

---

### 🎬 CineTrack

**A movie discovery app with a clean interface**
GitHub: [https://github.com/vedantparasharr/CineTrack](https://github.com/vedantparasharr/CineTrack)

---

## Connect With Me

<div align="center">
<a href="https://github.com/vedantparasharr"><img src="https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="https://linkedin.com/in/vedantparasharr"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:iemvedant@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</div>

<br/>

<div align="center">
Made with patience and curiosity by <strong>Vedant Parashar</strong>
</div>

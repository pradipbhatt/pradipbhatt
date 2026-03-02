<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00f5d4,50:7c3aed,100:f59e0b&height=200&section=header&text=Pradip%20Bhatt&fontSize=50&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=Full%20Stack%20Developer%20%7C%20Computer%20Engineer%20%7C%20Nepal&descAlignY=55&descAlign=50&descSize=16" width="100%"/>
</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=pradipbhatt&label=PROFILE+VIEWS&color=00f5d4&style=for-the-badge&labelColor=0d1117"/>
  <img src="https://img.shields.io/github/followers/pradipbhatt?logo=github&style=for-the-badge&color=7c3aed&labelColor=0d1117"/>
  <img src="https://img.shields.io/github/stars/pradipbhatt?logo=github&style=for-the-badge&color=f59e0b&labelColor=0d1117"/>
  <br/>
  <img src="https://img.shields.io/badge/Available%20For%20Work-<svg xmlns='http://www.w3.org/2000/svg' width='16' height='16' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2'><path d='M22 11.08V12a10 10 0 1 1-5.93-9.14'></path><polyline points='22 4 12 14.01 9 11.01'></polyline></svg>-00f5d4?style=for-the-badge&labelColor=0d1117"/>
</div>

<br/>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=2800&pause=900&color=00f5d4&center=true&vCenter=true&width=700&lines=Hi%2C+I'm+Pradip+Bhatt;Full+Stack+Developer+%40+Hyperce;Building+Scalable+Web+Solutions;Open+Source+Enthusiast;Cloud+Technologies+Specialist;Clean+Code+%7C+Clean+Architecture+Advocate;Let's+Connect+and+Build+Together" alt="Typing SVG"/>
</div>

---

## <svg xmlns='http://www.w3.org/2000/svg' width='24' height='24' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2'><path d='M2 12s3-7 10-7 10 7 10 7-3 7-10 7-10-7-10-7Z'></path><circle cx='12' cy='12' r='3'></circle></svg> Contribution Snake

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/pradipbhatt/pradipbhatt/output/dist/github-contribution-grid-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/pradipbhatt/pradipbhatt/output/dist/github-contribution-grid-snake.svg"/>
    <img alt="Snake animation" src="https://raw.githubusercontent.com/pradipbhatt/pradipbhatt/output/dist/github-contribution-grid-snake.svg" width="100%"/>
  </picture>
</div>

<details>
<summary>⚙️ Setup: Click to copy the GitHub Action workflow</summary>

Create this file in your repo: `.github/workflows/snake.yml` 

```yaml
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 10
    steps:
      - name: Generate github-contribution-grid-snake.svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push snake SVG to output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

After saving the file → go to **Actions tab → Generate Snake Animation → Run workflow** ✅

</details>

---

## <svg xmlns='http://www.w3.org/2000/svg' width='24' height='24' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2'><path d='M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2'></path><circle cx='12' cy='7' r='4'></circle></svg> About Me

```typescript
const pradip = {
  name:       "Pradip Bhatt",
  location:   "Nepal",
  role:       "Full Stack Developer @ Hyperce",
  education:  "Computer Engineering",
  focus:      ["Scalable APIs", "Cloud Architecture", "Open Source"],
  hobbies:    ["Coding", "Technology", "Innovation"],
  available:   true, // Open to new opportunities!
  funFact:    "I turn coffee into code and ideas into reality",
};
```

<details>
<summary>📖 More about me...</summary>
<br>

- Currently working on **SOE Connect** & **SOE Intel** platforms
- Exploring **Cloud Architecture**, **Microservices** & **AI integrations**
- Looking to collaborate on **Open Source Projects**
- Ask me about **React, Node.js, Laravel, Docker, AWS**
- Reach me at **bhattsammar04@gmail.com**
- Fun fact: I can watch an entire Marvel movie while debugging

</details>

---

## <svg xmlns='http://www.w3.org/2000/svg' width='24' height='24' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2'><polygon points='13 2 3 14 12 14 11 22 21 10 12 10 13 2'></polygon></svg> Active Projects

| <svg xmlns='http://www.w3.org/2000/svg' width='16' height='16' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2'><polygon points='13 2 3 14 12 14 11 22 21 10 12 10 13 2'></polygon></svg> Project | <svg xmlns='http://www.w3.org/2000/svg' width='16' height='16' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2'><path d='M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z'></path><polyline points='14 2 14 8 20 8'></polyline><line x1='16' y1='13' x2='8' y2='13'></line><line x1='16' y1='17' x2='8' y2='17'></line><polyline points='10 9 9 9 8 9'></polyline></svg> Description | <svg xmlns='http://www.w3.org/2000/svg' width='16' height='16' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2'><path d='M14.7 6.3a1 1 0 0 0 0 1.4l1.6 1.6a1 1 0 0 0 1.4 0l3.77-3.77a6 6 0 0 1-7.94 7.94l-6.91 6.91a2.12 2.12 0 0 1-3-3l6.91-6.91a6 6 0 0 1 7.94-7.94l-3.76 3.76z'></path></svg> Stack | <svg xmlns='http://www.w3.org/2000/svg' width='16' height='16' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2'><circle cx='12' cy='12' r='10'></circle><polyline points='12 6 12 12 16 14'></polyline></svg> Status |
|---|---|---|---|
| [**SOE Intel**](https://soeintel.vercel.app/) | School of Engineering analytics platform | React, Node.js, MongoDB | ![Active](https://img.shields.io/badge/-Active-00f5d4?style=flat-square) |
| [**Team Celestials**](https://team-celestials.vercel.app/) | Developer team collaboration hub | React, Express, Tailwind | ![Active](https://img.shields.io/badge/-Active-00f5d4?style=flat-square) |
| [**SOE Connect**](https://soeconnect.vercel.app/) | Engineering student social network | MERN, Socket.io, JWT | ![Active](https://img.shields.io/badge/-Active-00f5d4?style=flat-square) |
| [**SOE Notes**](https://soenotes.vercel.app/) | Educational resource sharing platform | React, Firebase | ![Active](https://img.shields.io/badge/-Active-00f5d4?style=flat-square) |
| [**Portfolio**](https://pradipbhatt.com.np) | Personal developer portfolio | React, Tailwind, Vercel | ![Live](https://img.shields.io/badge/-Live-7c3aed?style=flat-square) |

---

## <svg xmlns='http://www.w3.org/2000/svg' width='24' height='24' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2'><rect x='2' y='3' width='20' height='14' rx='2' ry='2'></rect><line x1='8' y1='21' x2='16' y2='21'></line><line x1='12' y1='17' x2='12' y2='21'></line></svg> Tech Stack

### <svg xmlns='http://www.w3.org/2000/svg' width='20' height='20' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2'><path d='M14.7 6.3a1 1 0 0 0 0 1.4l1.6 1.6a1 1 0 0 0 1.4 0l3.77-3.77a6 6 0 0 1-7.94 7.94l-6.91 6.91a2.12 2.12 0 0 1-3-3l6.91-6.91a6 6 0 0 1 7.94-7.94l-3.76 3.76z'></path></svg> Languages & Frameworks

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
<br/>
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vue.js&logoColor=4FC08D)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&logo=express&logoColor=white)
<br/>
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)

</div>

### <svg xmlns='http://www.w3.org/2000/svg' width='20' height='20' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2'><ellipse cx='12' cy='5' rx='9' ry='3'></ellipse><path d='M21 12c0 1.66-4 3-9 3s-9-1.34-9-3'></path><path d='M3 5v14c0 1.66 4 3 9 3s9-1.34 9-3V5'></path></svg> Databases & Cloud

<div align="center">

![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![AWS](https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
<br/>
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Heroku](https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white)

</div>

### <svg xmlns='http://www.w3.org/2000/svg' width='20' height='20' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2'><path d='M12 2L2 7v10c0 5.55 3.84 10.74 9 12 5.16-1.26 9-6.45 9-12V7l-10-5z'></path></svg> Frontend & Styling

<div align="center">

![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

</div>

### <svg xmlns='http://www.w3.org/2000/svg' width='20' height='20' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2'><path d='M14.7 6.3a1 1 0 0 0 0 1.4l1.6 1.6a1 1 0 0 0 1.4 0l3.77-3.77a6 6 0 0 1-7.94 7.94l-6.91 6.91a2.12 2.12 0 0 1-3-3l6.91-6.91a6 6 0 0 1 7.94-7.94l-3.76 3.76z'></path></svg> Tools & Platforms

<div align="center">

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
<br/>
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0A0FFF?style=for-the-badge&logo=jira&logoColor=white)
![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)

</div>

---

## <svg xmlns='http://www.w3.org/2000/svg' width='24' height='24' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2'><line x1='18' y1='20' x2='18' y2='10'></line><line x1='12' y1='20' x2='12' y2='4'></line><line x1='6' y1='20' x2='6' y2='14'></line></svg> GitHub Analytics

<div align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=pradipbhatt&show_icons=true&theme=tokyonight&count_private=true&include_all_commits=true&hide_border=true&rank_icon=github&title_color=00f5d4&icon_color=7c3aed"/>
  <img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=pradipbhatt&theme=tokyonight&hide_border=true&ring=00f5d4&fire=f59e0b&currStreakLabel=00f5d4"/>
</div>

<div align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=pradipbhatt&layout=compact&theme=tokyonight&hide_border=true&hide=html,css&langs_count=8&title_color=00f5d4"/>
  <img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=pradipbhatt&theme=tokyonight&utcOffset=5.75"/>
</div>

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=pradipbhatt&theme=tokyonight" width="100%"/>
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=pradipbhatt&theme=tokyo-night&hide_border=true&area=true&custom_title=Pradip%27s%20Contribution%20Graph&color=00f5d4&line=7c3aed&point=f59e0b" width="100%"/>
</div>

---

## <svg xmlns='http://www.w3.org/2000/svg' width='24' height='24' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2'><path d='M6 9l6 6 6-6'></path></svg> GitHub Trophies

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=pradipbhatt" width="100%"/>
</div>

---

## <svg xmlns='http://www.w3.org/2000/svg' width='24' height='24' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2'><circle cx='12' cy='12' r='10'></circle><path d='M8 14s1.5 2 4 2 4-2 4-2'></path><line x1='9' y1='9' x2='9.01' y2='9'></line><line x1='15' y1='9' x2='15.01' y2='9'></line></svg> Holopin Badges

<div align="center">
  <a href="https://holopin.io/@pradipbhatt">
    <img src="https://holopin.me/pradipbhatt" alt="Holopin Badges" width="100%"/>
  </a>
</div>

---

## <svg xmlns='http://www.w3.org/2000/svg' width='24' height='24' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2'><path d='M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z'></path></svg> Dev Quote

<div align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" width="80%"/>
</div>

---

## <svg xmlns='http://www.w3.org/2000/svg' width='24' height='24' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2'><path d='M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z'></path><rect x='2' y='9' width='4' height='12'></rect><circle cx='4' cy='4' r='2'></circle></svg> Connect With Me

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-pradipbhatt-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/pradipbhatt)
[![Portfolio](https://img.shields.io/badge/Portfolio-pradipbhatt.com.np-00f5d4?style=for-the-badge&logo=google-chrome&logoColor=white)](https://pradipbhatt.com.np)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/your-linkedin-profile)
[![Twitter](https://img.shields.io/badge/Twitter-Follow-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/your-twitter-handle)
[![Gmail](https://img.shields.io/badge/Gmail-bhattsammar04@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bhattsammar04@gmail.com)

</div>

---

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00f5d4,50:7c3aed,100:f59e0b&height=100&section=footer" width="100%"/>
  
  <div align="center" style="margin-top: 20px; margin-bottom: 10px;">
    <img src="https://img.shields.io/badge/Thanks%20for%20visiting!-<svg xmlns='http://www.w3.org/2000/svg' width='16' height='16' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2'><polygon points='12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2'></polygon></svg>-00f5d4?style=for-the-badge&labelColor=0d1117"/>
    <img src="https://img.shields.io/badge/Star%20the%20repo-<svg xmlns='http://www.w3.org/2000/svg' width='16' height='16' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2'><polygon points='12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2'></polygon></svg>-f59e0b?style=for-the-badge&labelColor=0d1117"/>
    <img src="https://img.shields.io/badge/Let's%20Connect-<svg xmlns='http://www.w3.org/2000/svg' width='16' height='16' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2'><path d='M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z'></path><rect x='2' y='9' width='4' height='12'></rect><circle cx='4' cy='4' r='2'></circle></svg>-7c3aed?style=for-the-badge&labelColor=0d1117"/>
  </div>
  
  <div align="center" style="margin: 15px 0;">
    <a href="https://github.com/pradipbhatt">
      <img src="https://img.shields.io/badge/GitHub-pradipbhatt-181717?style=for-the-badge&logo=github&logoColor=white"/>
    </a>
    <a href="https://pradipbhatt.com.np">
      <img src="https://img.shields.io/badge/Portfolio-pradipbhatt.com.np-00f5d4?style=for-the-badge&logo=google-chrome&logoColor=white"/>
    </a>
    <a href="mailto:bhattsammar04@gmail.com">
      <img src="https://img.shields.io/badge/Email-bhattsammar04@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
    </a>
  </div>
  
  <div align="center" style="margin: 10px 0;">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=14&duration=2000&pause=500&color=00f5d4&center=true&vCenter=true&width=400&lines=Let's%20build%20something%20amazing%20together!" alt="Footer typing"/>
  </div>
  
  <div align="center" style="margin-top: 15px;">
    <sub>
      <img src="https://img.shields.io/badge/Crafted%20with-<svg xmlns='http://www.w3.org/2000/svg' width='16' height='16' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2'><path d='M20.84 4.61a5.5 5.5 0 0 0-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 0 0-7.78 7.78l1.06 1.06L12 21.23l7.78-7.78 1.06-1.06a5.5 5.5 0 0 0 0-7.78z'></path></svg>-e74c3c?style=flat-square&labelColor=0d1117"/>
      <img src="https://img.shields.io/badge/Powered%20by-Coffee%20<svg xmlns='http://www.w3.org/2000/svg' width='16' height='16' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2'><path d='M18 8h1a4 4 0 0 1 0 8h-1'></path><path d='M2 8h16v9a4 4 0 0 1-4 4H6a4 4 0 0 1-4-4V8z'></path><line x1='6' y1='1' x2='6' y2='4'></line><line x1='10' y1='1' x2='10' y2='4'></line><line x1='14' y1='1' x2='14' y2='4'></line></svg>%20<svg xmlns='http://www.w3.org/2000/svg' width='16' height='16' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2'><path d='M9 18V5l12-2v13'></path><circle cx='6' cy='18' r='3'></circle><circle cx='18' cy='16' r='3'></circle></svg>-8b4513?style=flat-square&labelColor=0d1117"/>
      <img src="https://img.shields.io/badge/Built%20using-React%20%7C%20Node.js%20%7C%20Tailwind-61dafb?style=flat-square&labelColor=0d1117"/>
    </sub>
  </div>
  
  <div align="center" style="margin-top: 10px;">
    <sub style="color: #00f5d4; font-size: 14px;">
      📧 <a href="mailto:bhattsammar04@gmail.com" style="color: #00f5d4;">bhattsammar04@gmail.com</a> 
      | 🌐 <a href="https://pradipbhatt.com.np" style="color: #00f5d4;">pradipbhatt.com.np</a> 
      | 📍 Kathmandu, Nepal
    </sub>
  </div>
  
  <div align="center" style="margin-top: 10px;">
    <sub style="color: #7c3aed; font-size: 12px;">
      © 2025 Pradip Bhatt | All rights reserved | Made with <svg xmlns='http://www.w3.org/2000/svg' width='16' height='16' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2'><rect x='2' y='3' width='20' height='14' rx='2' ry='2'></rect><line x1='8' y1='21' x2='16' y2='21'></line><line x1='12' y1='17' x2='12' y2='21'></line></svg> and <svg xmlns='http://www.w3.org/2000/svg' width='16' height='16' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2'><path d='M18 8h1a4 4 0 0 1 0 8h-1'></path><path d='M2 8h16v9a4 4 0 0 1-4 4H6a4 4 0 0 1-4-4V8z'></path><line x1='6' y1='1' x2='6' y2='4'></line><line x1='10' y1='1' x2='10' y2='4'></line><line x1='14' y1='1' x2='14' y2='4'></line></svg>
    </sub>
  </div>
</div>

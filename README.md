
<style>
  /* Global Reset */
  * {
    box-sizing: border-box;
  }

  body {
    margin: 0;
    padding: 0;
    background-color: #0d1117;
    color: #00FF41;
    font-family: 'Fira Code', monospace;
    text-align: center;
  }

  img {
    max-width: 100%;
    height: auto;
  }

  /* Responsive Headings */
  h2, h3, h4, h5 {
    word-wrap: break-word;
  }

  /* Responsive Two-Column Layout */
  .responsive-section {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 2rem;
    margin: 2rem auto;
    width: 90%;
  }

  .column {
    flex: 1 1 400px;
    background: #0d1117;
    padding: 1rem;
    border: 1px solid #00FF41;
    border-radius: 10px;
  }

  /* Responsive Tech Grid */
  .tech-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
    gap: 1rem;
    justify-items: center;
    margin: 2rem auto;
    width: 90%;
  }

  /* GitHub Stats Section */
  .stats {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 1rem;
  }

  .stats img {
    flex: 1 1 300px;
    max-width: 48%;
  }

  /* Featured Repositories */
  .repos {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 1rem;
  }

  .repos a img {
    width: 100%;
    max-width: 420px;
  }

  /* Responsive Badges and Links */
  .badges, .social-links {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 1rem;
    margin: 1rem auto;
  }

  /* Animated Separator */
  .separator {
    width: 100%;
    margin: 2rem 0;
  }

  /* Media Queries for Mobile */
  @media (max-width: 768px) {
    .column {
      flex: 1 1 100%;
    }

    .stats img {
      max-width: 100%;
    }

    h2 {
      font-size: 1.5rem;
    }

    h3 {
      font-size: 1.2rem;
    }
  }

  @media (max-width: 480px) {
    body {
      font-size: 14px;
    }

    .tech-grid {
      grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
    }

    .repos a img {
      max-width: 100%;
    }
  }
</style>

<div align="center">

  <!-- Header -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,6,12,20&height=250&section=header&text=ASHISH%20P.&fontSize=60&fontColor=00ff41&animation=twinkling&fontAlignY=35&desc=⚡%20Tier-3%20BTech%20Kid%20→%20Big%20Tech%20Dreams%20⚡&descSize=18&descAlignY=55" alt="Header">

  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=00FF41&center=true&vCenter=true&width=700&lines=%F0%9F%92%BB+Java+%2B+Python+Developer;%F0%9F%9A%80+DSA+%2B+MERN+Stack+Enthusiast;%E2%9A%A1+Building+Projects%2C+Breaking+Limits;%F0%9F%94%A5+No+Spoon-Fed+BS+%7C+Just+Raw+Code" alt="Typing SVG">

  <img class="separator" src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif">
</div>

<!-- WHO AM I + CURRENT MISSION -->
<section class="responsive-section">
  <div class="column">
    <h2>💀 WHO AM I?</h2>
    <p><b>🎯 Identity:</b> Tier-3 BTech CSE Student</p>
    <p><b>💡 Mindset:</b> Big Tech Dreams + Ruthless Execution</p>
    <p><b>🛠️ Tech Stack:</b> Java | Python | MERN | DSA</p>
    <blockquote><em>"No shortcuts. No excuses. Just code."</em></blockquote>
  </div>

  <div class="column">
    <h2>🚀 CURRENT MISSION</h2>
    <div class="tech-grid">
      <div><img src="https://img.icons8.com/fluency/96/java-coffee-cup-logo.png" width="50"><br><b>Java</b></div>
      <div><img src="https://img.icons8.com/color/96/python--v1.png" width="50"><br><b>Python</b></div>
      <div><img src="https://img.icons8.com/color/96/code.png" width="50"><br><b>DSA</b></div>
      <div><img src="https://img.icons8.com/color/96/mongodb.png" width="50"><br><b>MERN</b></div>
      <div><img src="https://img.icons8.com/fluency/96/github.png" width="50"><br><b>Git</b></div>
      <div><img src="https://img.icons8.com/color/96/console.png" width="50"><br><b>CLI</b></div>
    </div>
  </div>
</section>

<!-- TECH ARSENAL -->
<h2>⚙️ TECH ARSENAL ⚙️</h2>
<div class="badges">
  <img src="https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=black&color=00FF41" alt="Java">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=black&color=00D9FF" alt="Python">
  <img src="https://img.shields.io/badge/React-%2320232a.svg?style=for-the-badge&logo=react&logoColor=black&color=00D9FF" alt="React">
  <img src="https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=black&color=00FF41" alt="MongoDB">
</div>

<!-- FEATURED REPOS -->
<h2>🌟 FEATURED REPOSITORIES</h2>
<div class="repos">
  <a href="https://github.com/imstillashish/complete-python-notes">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=imstillashish&repo=complete-python-notes&theme=radical&bg_color=0d1117&title_color=00FF41&text_color=00D9FF&icon_color=FF006E&border_color=00FF41">
  </a>
  <a href="https://github.com/imstillashish/Python_for_DSA">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=imstillashish&repo=Python_for_DSA&theme=radical&bg_color=0d1117&title_color=00FF41&text_color=00D9FF&icon_color=FF006E&border_color=00D9FF">
  </a>
</div>

<!-- GITHUB STATS -->
<h2>📈 GITHUB STATS</h2>
<div class="stats">
  <img src="https://github-readme-stats.vercel.app/api?username=imstillashish&show_icons=true&theme=radical&bg_color=0d1117&title_color=00FF41&text_color=00D9FF&icon_color=FF006E&border_color=00FF41">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=imstillashish&theme=radical&background=0d1117&ring=00FF41&fire=FF006E&currStreakLabel=00D9FF&border=00FF41">
</div>

<!-- CONNECT -->
<h2>🌐 CONNECT WITH ME</h2>
<div class="social-links">
  <a href="https://linkedin.com/in/imstillashish"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=black&color=00FF41"></a>
  <a href="https://twitter.com/imstillashish"><img src="https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=Twitter&logoColor=black&color=00D9FF"></a>
  <a href="https://github.com/imstillashish"><img src="https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=00FF41&color=0d1117"></a>
</div>

<br>

<!-- Footer -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,6,12,20&height=120&section=footer" width="100%">

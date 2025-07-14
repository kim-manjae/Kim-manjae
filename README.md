<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>김만재 포트폴리오</title>
  <style>
    * { margin:0; padding:0; box-sizing:border-box; }
    body { font-family:sans-serif; color:#333; line-height:1.6; }
    header { background:#222; color:#fff; position:sticky; top:0; }
    nav { display:flex; max-width:1000px; margin:auto; padding:1rem; }
    nav a { color:#fff; margin-right:1rem; text-decoration:none; }
    section { padding:4rem 1rem; max-width:1000px; margin:auto; }
    h1,h2 { margin-bottom:1rem; }
    .card-grid { display:grid; grid-template-columns:repeat(auto-fill,minmax(200px,1fr)); gap:1rem; }
    .card { border:1px solid #ccc; padding:1rem; border-radius:4px; }
    .card img { width:100%; height:auto; border-radius:4px; }
    footer { text-align:center; padding:2rem 1rem; font-size:.9rem; color:#666; }
  </style>
</head>
<body>

<header>
  <nav>
    <a href="#home">홈</a>
    <a href="#projects">개발 프로젝트</a>
    <a href="#ppt">PPT 자료</a>
    <a href="#code">연습 코드</a>
    <a href="#portfolio3d">3D 포트폴리오</a>
    <a href="#contact">연락처</a>
  </nav>
</header>

<section id="home">
  <h1>안녕하세요, 프론트엔드 개발자 김만재입니다.</h1>
  <p>React · Vue · Three.js · Flutter 경험</p>
</section>

<section id="projects">
  <h2>개발 프로젝트</h2>
  <div class="card-grid">
    <div class="card">
      <h3>Team 3 앱 (프론트엔드 참여)</h3>
      <p>Vue.js · Flutter · FastAPI 연동</p>
      <p>
        <a href="https://github.com/kim-manjae/team_3" target="_blank">GitHub 레포</a> ·
        <a href="https://kim-manjae.github.io/team_3/" target="_blank">Live Demo</a>
      </p>
    </div>
    <!-- 다른 개발 프로젝트가 있으면 여기에 카드 추가 -->
  </div>
</section>

<section id="ppt">
  <h2>PPT & 발표 자료</h2>
  <iframe src="https://docs.google.com/presentation/d/e/슬라이드ID/embed?start=false&loop=false" 
          frameborder="0" width="100%" height="400px" allowfullscreen>
  </iframe>
  <p><a href="docs/portfolio_presentation.pdf" download>원본 PPT 다운로드</a></p>
</section>

<section id="code">
  <h2>연습 코드 샘플</h2>
  <div class="card-grid">
    <div class="card">
      <h3>HTML/CSS 레이아웃 연습</h3>
      <p><a href="https://github.com/kim-manjae/html-css-exercises" target="_blank">GitHub</a></p>
    </div>
    <div class="card">
      <h3>JavaScript 알고리즘 풀이</h3>
      <p><a href="https://github.com/kim-manjae/js-algorithm" target="_blank">GitHub</a></p>
    </div>
    <div class="card">
      <h3>Flutter 위젯 샘플</h3>
      <p><a href="https://github.com/kim-manjae/flutter-widget-examples" target="_blank">GitHub</a></p>
    </div>
  </div>
</section>

<section id="portfolio3d">
  <h2>3D 모델링 포트폴리오</h2>
  <div class="card-grid">
    <div class="card">
      <img src="images/3dthumb1.jpg" alt="3D 모델 샘플 1">
      <p><a href="https://your-3d-model-site.com" target="_blank">전체 3D 포트폴리오 바로가기</a></p>
    </div>
    <!-- 추가 이미지/링크 필요 시 카드 추가 -->
  </div>
</section>

<section id="contact">
  <h2>연락처</h2>
  <p>이메일: <a href="mailto:you@example.com">you@example.com</a></p>
  <p>GitHub: <a href="https://github.com/kim-manjae" target="_blank">github.com/kim-manjae</a></p>
  <p>LinkedIn: <a href="https://linkedin.com/in/your-profile" target="_blank">linkedin.com/in/your-profile</a></p>
</section>

<footer>
  © 2025 김만재. All rights reserved.
</footer>

</body>
</html>

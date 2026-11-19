<!-- =========================================================
  v6 · Bento Grid (표를 타일처럼 써서 칸칸이 정리한 대시보드형)
========================================================== -->

<!-- 제목 태그(h1~h6)를 쓰면 GitHub이 🔗 링크 아이콘을 붙이므로, 큰 글씨는 테마별 SVG 이미지로 표시 -->
<p align="center">
  <img src="https://emojis.slackmojis.com/emojis/images/1531849430/4246/blob-sunglasses.gif?1531849430" width="32"/>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/hello-dark.svg"/>
    <h1>Hello World! Welcome to my GitHub.</h1>
  </picture>
</p>

<!-- ───────── Row 1 : 프로필 카드 ───────── -->
<table>
  <tr>
    <td width="38%" align="center" valign="middle">
      <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="200"/>
    </td>
    <td width="62%" valign="middle">
      <p></p><!-- 처음·끝의 빈 <p></p>는 위아래 여백 균형용 -->
      <p>
        <picture>
          <h4>SeokJun Kim</h4>
        </picture>
      </p>
      <p><b><i>AI-native Software Engineer</i></b></p>
      <p>🎓 Computer Engineering @ <b>Kookmin University, Korea</b></p>
      <p>I'm interested in AI-Native SW engineering, AI agent, infrastructure and cloud computing.
      I also enjoy meeting people and doing new things, so feel free to contact me!</p>
      <p>
        <a href="https://www.linkedin.com/in/seokjun1021"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
        <a href="https://mail.google.com/mail/?view=cm&fs=1&to=kimsj6978@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
        <a href="https://sonnyseokjun.github.io/my-website-ko/"><img src="https://img.shields.io/badge/Website-1B9AF7?style=flat-square&logo=safari&logoColor=white"/></a>
      </p>
      <p></p>
    </td>
  </tr>
</table>

<!-- ───────── Row 2 : 기술 스택 타일 (셀 처음·끝의 빈 <p></p>는 위아래 여백 균형용) ───────── -->
<table>
  <tr>
    <td width="50%" valign="top">
      <p></p>
      <p><b>💬 Languages</b><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
      <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
      <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white"/>
      </p>
      <p><b>⚙️ Backend & Framework</b><br/>
      <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white"/>
      <img src="https://img.shields.io/badge/DRF-A30000?style=for-the-badge&logo=django&logoColor=white"/>
      <img src="https://img.shields.io/badge/Redis-DD0031?style=for-the-badge&logo=redis&logoColor=white"/>
      </p>
      <p><b>🤖 AI</b><br/>
      <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge&logo=claude&logoColor=white"/>
      <img src="https://img.shields.io/badge/AWS%20Kiro-7C3AED?style=for-the-badge&logoColor=white"/>
      </p>
      <p></p>
    </td>
    <td width="50%" valign="top">
      <p></p>
      <p><b>☁️ Infra & DevOps</b><br/>
      <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white"/>
      <img src="https://img.shields.io/badge/AWS%20EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white"/>
      <img src="https://img.shields.io/badge/AWS%20S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white"/>
      <img src="https://img.shields.io/badge/AWS%20Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white"/>
      <img src="https://img.shields.io/badge/AWS%20SQS-FF4F8B?style=for-the-badge&logo=amazonsqs&logoColor=white"/>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
      </p>
      <p><b>🔧 Tools</b><br/>
      <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
      <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
      <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white"/>
      <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white"/>
      </p>
      <p></p>
    </td>
  </tr>
</table>

<!-- ───────── Row 3 : 프로젝트 타일 (2x2) ─────────
  · 셀 처음과 끝의 빈 <p></p>는 위아래 여백을 같게 맞추는 용도
  · 태그 안 &nbsp;는 "AWS Lightsail" 같은 태그가 중간에서 줄바꿈되지 않게 함
─────────────────────────────────────────── -->
<table>
  <tr>
    <td width="50%" valign="top">
      <p></p>
      <p><b>📊 <a href="https://github.com/sonnyseokjun/DART-project">DART-AI</a></b><br/>
      DART 전자공시를 AI가 쉬운 언어로 요약해 주는 웹서비스 · <a href="https://dartaisite.duckdns.org">운영 중</a></p>
      <p><code>Python</code> <code>Django</code> <code>OpenAI&nbsp;GPT</code> <code>Docker</code> <code>AWS&nbsp;Lightsail</code></p>
      <p></p>
    </td>
    <td width="50%" valign="top">
      <p></p>
      <p><b>📚 <a href="https://github.com/kmu-software-engineering-project/backend">Reading</a></b><br/>
      하네스 엔지니어링을 적용하여 개발한 AI 기반 도서 추천 통합 플랫폼</p>
      <p><code>Python</code> <code>Django</code> <code>DRF</code> <code>OpenAI&nbsp;GPT</code> <code>Kakao&nbsp;Map&nbsp;API</code> <code>Naver&nbsp;API</code></p>
      <p></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <p></p>
      <p><b>🎤 <a href="https://github.com/kmu-aws-capstone-team-4/backend">Mefit · Backend</a></b><br/>
      AI 가상 면접 플랫폼 백엔드 개발</p>
      <p><code>Python</code> <code>Django</code> <code>DRF</code> <code>AWS&nbsp;EC2</code></p>
      <p></p>
    </td>
    <td width="50%" valign="top">
      <p></p>
      <p><b>🕸️ <a href="https://github.com/kmu-aws-capstone-team-4/scraping">Mefit · Scraping</a></b><br/>
      채용공고 페이지 정보 추출, 스크래핑 파이프라인</p>
      <p><code>Python</code> <code>OpenAI&nbsp;GPT</code> <code>Langchain</code> <code>Playwright</code></p>
      <p></p>
    </td>
  </tr>
</table>

<br/>
<p align="center"><b>Thanks for visiting! 👋</b></p>

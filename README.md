<!-- 타이핑 애니메이션 헤더 -->
<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=28&pause=1000&color=D2691E&center=true&vCenter=true&width=600&lines=안녕하세요%2C+jungwoogyun+입니다;백엔드+개발자입니다;항상+성장하는+중입니다" alt="Typing SVG" />
  </a>
</div>

<br/>

<!-- 방문자 수 -->
<div align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=jungwoogyun.jungwoogyun&left_color=3d2817&right_color=D2691E&left_text=visitors" />
</div>

<br/>

---

## 자기소개

```text
백엔드 개발자
Java / Spring 을 주로 사용합니다
Docker, AWS 기반 클라우드 환경에 관심이 많습니다
항상 성장하는 중입니다
```

---

## 기술 스택

**Backend**

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Frontend**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)

**Database**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**DevOps / Cloud**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)

**Language**

![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white)

---

## GitHub 통계

<div align="left">
  <img height="165px" width="400px" src="https://github-readme-stats.vercel.app/api?username=jungwoogyun&show_icons=true&theme=radical&title_color=D2691E&text_color=CD853F&icon_color=D2691E&bg_color=1a1a1a&hide_border=true&include_all_commits=true&count_private=true" />
  <img height="165px" width="300px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jungwoogyun&layout=compact&theme=radical&title_color=D2691E&text_color=CD853F&bg_color=1a1a1a&hide_border=true" />
</div>

<br/>

<!-- 연속 커밋 스트릭 -->
<div align="center">
  <img src="https://streak-stats.demolab.com?user=jungwoogyun&theme=radical&hide_border=true&locale=ko&ring=D2691E&fire=D2691E&currStreakLabel=D2691E" />
</div>

---

## 트로피

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=jungwoogyun&theme=onedark&no-frame=true&no-bg=true&margin-w=4&row=1" />
</div>

---

## 활동 그래프

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=jungwoogyun&theme=radical&hide_border=true&area=true&color=D2691E&bg_color=1a1a1a&line=CD853F&point=D2691E" />
</div>

---

---

## 뱀 커밋 애니메이션

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/jungwoogyun/jungwoogyun/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/jungwoogyun/jungwoogyun/output/github-snake.svg" />
    <img alt="github-snake" src="https://raw.githubusercontent.com/jungwoogyun/jungwoogyun/output/github-snake.svg" />
  </picture>
</div>

> 뱀 애니메이션은 GitHub Actions 설정이 필요합니다.
> 아래 파일을 `.github/workflows/snake.yml` 에 추가해 주세요.

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: jungwoogyun
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark
            dist/github-snake.svg?color_snake=D2691E
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```
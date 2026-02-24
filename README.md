<!-- Trophy -->
<div align="center">
  <a href="https://github.com/ryo-ma/github-profile-trophy">
    <img src="https://github-profile-trophy.vercel.app/?username=gusgh075&theme=radical&column=7&margin-w=10&margin-h=10" alt="gusgh075's trophies" />
  </a>
</div>

---

<!-- Header -->
<div align="center">

# 👋 Hey there! I'm **gusgh075** (정현호)

### 🚀 Backend-focused Junior Developer | Java & Spring Enthusiast

> _"코드 한 줄이 세상을 바꾼다고 믿으며, 오늘도 한 줄씩 성장합니다."_

[![Velog Badge](https://img.shields.io/badge/Velog-20C997?style=for-the-badge&logo=velog&logoColor=white)](https://velog.io/@gusgh075/posts)
[![GitHub Badge](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/gusgh075)

</div>

---

<!-- Most Used Languages -->
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=gusgh075&layout=compact&theme=radical&langs_count=8&hide_border=true" alt="Most Used Languages" />
</div>

---

## 🛠️ Tech Stack

### Backend
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Framework](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![JPA](https://img.shields.io/badge/JPA%20%2F%20Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-005571?style=for-the-badge&logo=fastapi&logoColor=white)
![MSA](https://img.shields.io/badge/MSA-FF6C37?style=for-the-badge&logo=apachekafka&logoColor=white)

### Frontend
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Database
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![JDBC](https://img.shields.io/badge/JDBC-007396?style=for-the-badge&logo=java&logoColor=white)

### DevOps & Tools
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![ngrok](https://img.shields.io/badge/ngrok-1F1E37?style=for-the-badge&logo=ngrok&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## 🌟 Project Highlights

### 🍳 [Empty the Fridge](https://github.com/gusgh075/Empty_the_fridge)
> 냉장고 재료 기반 레시피 추천 애플리케이션

냉장고에 남은 재료들을 입력하면 만들 수 있는 레시피를 추천해주는 Java 기반 애플리케이션입니다.
식재료 낭비를 줄이고 요리 아이디어를 제공하는 실용적인 프로젝트입니다.

`Java` `Spring Boot` `JPA`

---

### 🗺️ [MapLog](https://github.com/20251029-hanhwa-swcamp-22th/be22-4st-team1-project)
> 지도 위에 기록하는 나만의 소셜 다이어리 서비스 | **CI/CD 인프라 전담**

방문한 장소를 지도에 핀으로 표시하고 일기를 남기는 위치 기반 소셜 다이어리 앱입니다.
친구 공개 / 비공개 설정, 일기 스크랩, 알림 시스템 등을 갖춘 풀스택 팀 프로젝트입니다.

**🔧 담당 역할 — CI/CD 자동화 파이프라인 구축 (전담)**

- **Jenkinsfile 직접 작성**: `빌드 → Docker 이미지 빌드 & Push → K8s 매니페스트 자동 업데이트` 전 과정 파이프라인 설계 및 구현
- **GitOps 구조 설계**: K8s 매니페스트를 전용 레포([k8s-manifests](https://github.com/gusgh075/k8s-manifests))로 분리하고 ArgoCD가 자동 감지·배포하는 GitOps 플로우 구축
- **Kubernetes 리소스 작성**: MariaDB · Backend · Frontend에 대한 `Deployment`, `Service`, `ArgoCD Application` YAML 전체 작성
- **시크릿 관리 고도화**: `.env` 파일 의존에서 벗어나 K8s `envFrom` / `secretRef` 기반 환경변수 주입 방식으로 전환
- **파이프라인 개선**: 중복 빌드 단계 제거, JDK 도구 설정 정정, 매니페스트 워크스페이스 충돌 수정 등 파이프라인 안정화
- **ngrok CORS 해결**: `AllowedOriginPatterns` 적용으로 Kubernetes 외부 접근 테스트 시 발생한 403 오류 해결
- **GitHub Webhook 연동**: Jenkins 자동 트리거 설정 및 검증

`Java 21` `Spring Boot 3.5` `Spring Security` `JWT` `JPA` `MariaDB` `Vue 3` `Docker` `Kubernetes` `Jenkins` `ArgoCD` `ngrok` `AWS S3`

---

## 📈 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=gusgh075&show_icons=true&theme=radical&hide_border=true&include_all_commits=true&count_private=true" alt="gusgh075's GitHub Stats" height="165" />
  &nbsp;
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=gusgh075&theme=radical&hide_border=true" alt="gusgh075's GitHub Streak" height="165" />
</div>

---

## 🎯 Currently Learning

- 🐳 **Docker & Jenkins** — CI/CD 파이프라인 구축 및 컨테이너 기반 배포 자동화
- ☁️ **MSA (Microservices Architecture)** — 서비스 분리와 확장 가능한 아키텍처 설계
- 🌐 **Vue.js 3** — 프론트엔드 역량 강화로 풀스택 개발자로 성장 중

---

## 📝 Blog Posts

기술 블로그에서 학습 내용을 기록하고 있습니다.

[![Velog](https://img.shields.io/badge/Visit%20My%20Velog-20C997?style=for-the-badge&logo=velog&logoColor=white)](https://velog.io/@gusgh075/posts)

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=gusgh075&color=blueviolet&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile Views" />

  <br/><br/>

  ⭐ **피드백과 협업은 언제나 환영합니다!** ⭐

  _"꾸준함이 실력이 된다"_
</div>

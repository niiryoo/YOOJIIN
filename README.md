<h1 align="center">안녕하세요, 유지인입니다 👋</h1>

<p align="center">
  <em><strong>OLTP/OLAP 분리 아키텍처부터 RAG 파이프라인까지 직접 구현해본<br/>
  AI Application 백엔드 엔지니어</strong></em>
</p>

<p align="center">
  <a href="mailto:yoojikol@gmail.com">
    <img src="https://img.shields.io/badge/Email-yoojikol@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://github.com/niiryoo">
    <img src="https://img.shields.io/badge/GitHub-@niiryoo-181717?style=flat-square&logo=github" alt="GitHub"/>
  </a>
</p>

---

## 👨‍💻 About Me

LLM·RAG·Agent 워크플로우를 실제 서비스 백엔드에 안정적으로 녹여내는 일에 관심이 많습니다.
단순히 LLM API를 호출하는 수준을 넘어, **검색 품질·응답 속도·운영 비용**까지 책임질 수 있는 시스템을 설계·구현해 왔습니다.

- 🤖 **AI/LLM Backend** — RAG 파이프라인 End-to-End 설계, Agent 오케스트레이션, LLM 서비스 백엔드
- 🏗 **Cloud-Native Architecture** — GCP 기반 OLTP/OLAP 분리 설계, 서버리스 백엔드
- 🤝 **Team Collaboration** — PM + Backend 듀얼 롤 수행, 코드리뷰 표준화 경험

---

## 🛠 Tech Stack

### Languages
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

### Backend
![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)

### AI / LLM
![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/-Gemini-8E75B2?style=flat-square&logo=google-gemini&logoColor=white)
![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
`LangGraph` `LangSmith` `Chroma` `bge-m3 Embedding`

### Database & Search
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/-Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![BigQuery](https://img.shields.io/badge/-BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)

### Cloud & DevOps
![GCP](https://img.shields.io/badge/-GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
`CI/CD` `Cloud Run` `Cloud SQL` `Cloud Build`

### Collaboration
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![Jira](https://img.shields.io/badge/-Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![Notion](https://img.shields.io/badge/-Notion-000000?style=flat-square&logo=notion&logoColor=white)
![Swagger](https://img.shields.io/badge/-Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)

---

## 🚀 Featured Projects

### 🐱 [메디냥 (Medi냥) — 내 손 안의 개인화된 AI 건강 파트너](https://github.com/KNU-OldMan/medinyang-spring)
> 의료 기록을 OCR로 디지털화하고, RAG 기반 LLM 챗봇이 개인의 건강 데이터를 근거로 맞춤형 답변을 제공하는 AI 헬스케어 서비스

`Java` `Spring Boot` `Elasticsearch` `OpenAI API` `Clova OCR` `bge-m3` `RAG`

🏆 **강원대학교 창업 AI+X 해커톤(AX 챌린지) 우수상 수상**

- RAG 파이프라인 End-to-End 직접 설계: 임베딩 → 하이브리드 검색(Vector + BM25) → 프롬프트 → 안전가드
- 의료 도메인 특화 안전가드(진단·처방 금지 룰)로 LLM 환각·위험 답변 차단

---

### 🐝 [인사이트비 (InsightBee) — 취준생을 위한 기업 인사이트 AI 리포트](https://github.com/Mungwani/InsightBee)
> 관심 기업명을 검색하면 최근 3개월 뉴스를 자동 수집·LLM 분석하여 핵심 키워드·트렌드·이슈 타임라인 인사이트 리포트를 제공

`Python` `FastAPI` `BigQuery` `Cloud Run` `Gemini Pro` `Selenium` `asyncio`

- 6인 팀 **PM + Backend 듀얼 롤** 수행 (아키텍처 설계·일정 관리·코드 리뷰)
- **OLTP(Cloud SQL) ↔ OLAP(BigQuery) 분리 아키텍처** 직접 설계·구현
- KOSPI 시총 상위 50대 기업 일 단위 약 800건 양질 기사 자동 수집·분석

---

### 📄 [견적이지 (Quotation Easy) — 사내 견적서 통합 관리 시스템](https://quotationeasy.com)
> 외주 작업 견적 요청을 한 사이트에서 통합 관리하기 위한 사내 시스템 (주식회사 아이들 백엔드 인턴십)

`TypeScript` `Node.js` `MySQL` `RESTful API`

- 6개월 백엔드 인턴십, 시니어와 1:1 멘토링 협업
- 워크플로우/DB/UI 설계부터 RESTful API 구현까지 전 과정 참여
- 회사 대표가 직접 사용하는 프로덕션 서비스로 배포·운영 중

---

## 🏆 Certifications & Education

| 구분 | 내용 |
|------|------|
| **자격증** | 정보처리기사 (Engineer Information Processing) |
| **어학** | TOEIC 875 |
| **교육** | **KT AIVLE School 9기** 수료 |
| **학력** | 강원대학교 컴퓨터공학과 |

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=niiryoo&show_icons=true&theme=default&hide_border=true" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=niiryoo&layout=compact&theme=default&hide_border=true" />
</p>

---

## 📫 Get in Touch

- 📧 **Email**: yoojikol@gmail.com
- 💼 **GitHub**: [@niiryoo](https://github.com/niiryoo)

<p align="center">
  <em>Thanks for visiting! 🙌</em>
</p>

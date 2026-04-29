![header](https://capsule-render.vercel.app/api?type=wave&color=0:91C8E4,100:4682A9&height=280&section=header&text=hyeryeong&fontSize=82&fontColor=ffffff)

<div align="center">

## 👩🏻‍💻 Frontend Developer

### AI 결과와 복잡한 사용자 흐름을  
### 사용자가 이해하고 조작할 수 있는 화면으로 구현합니다.

React · TypeScript · WPF · AI Service UI  
UX Flow Design · State Management · API Integration

</div>

---

## 🏆 Awards & Certifications

- **SSAFY 특화 프로젝트 최종 발표 1등 수상**  
  EyeSpeak / Frontend

- **삼성 SW 역량테스트 IM 등급**
- **정보처리기사**
- **SQLD**

---

## ✨ Highlights

- React/TypeScript 기반으로 **라우팅, 상태 관리, 인증 흐름, API 연동 구조**를 설계하고 구현합니다.
- AI 분석 결과, 시선 추적 결과, 3D 콘텐츠처럼 **비정형 데이터를 사용자 화면으로 구조화**한 경험이 있습니다.
- API 명세 불일치와 응답 구조 혼재 상황에서 **FE 모델 표준화와 매퍼 구조**를 통해 안정적인 연동을 지향합니다.
- 팀장으로서 Jira 이슈 관리, 기능 우선순위 조율, FE-BE-AI 연동 범위 정리 경험이 있습니다.
- 단순히 화면을 구현하는 것보다 **사용자 흐름, 예외 상태, 유지보수 가능한 구조**를 함께 고민합니다.

---

## 🎓 Education & Bootcamp

- **울산대학교**  
  프랑스어 전공 / IT공학 복수전공

- **KT AIVLE School 5기**

- **SSAFY 14기**

---

## ⭐ Featured Projects

### 1) P2U — AI 기반 P&ID 도면 분석 결과 검토 데스크톱 애플리케이션

> Current Project

P2U는 산업용 도면에서 주요 심볼과 연결 정보를 분석하고, 사용자가 AI 인식 결과를 원본 도면 위에서 확인·검토할 수 있도록 지원하는 WPF 기반 데스크톱 애플리케이션입니다.

- **Role**: 팀장 / Frontend
- **Keywords**: P&ID · AI 결과 검토 UI · WPF · 도면 분석 · 결과 시각화
- **Contribution**
  - WPF 기반 데스크톱 앱 화면 구조 설계
  - 도면 업로드 → 분석 진행 → 결과 검토 MVP 흐름 구성
  - AI 분석 결과를 도면 영역, 객체 표시, 상세 정보 패널로 나누어 시각화
  - Mock JSON 기반 결과 검토 UI 선구현
  - FE-BE-AI 간 결과 데이터 구조 조율
- **Tech**: C# WPF, XAML, REST API, FastAPI 연동, Jira

---

### 2) EyeSpeak — 시선 입력 기반 ALS 환자 보조 의사소통 서비스

> SSAFY 특화 프로젝트 최종 발표 1등 수상

EyeSpeak는 손 사용이 어려운 환자가 시선 입력을 통해 의사 표현, 보호자 호출, 여가 기능을 사용할 수 있도록 지원하는 보조 의사소통 서비스입니다.

- **Role**: Frontend
- **Keywords**: Eye Tracking · AAC · Accessibility UX · Patient Mode · AI-FE Integration
- **Contribution**
  - 환자모드 전체 UI 구조 및 라우팅 설계
  - 2×3 시선 입력 그리드 기반 화면 인터랙션 구현
  - 대화하기, 호출, 여가, 즐겨찾기 등 핵심 환자 기능 화면 구현
  - 전역 메뉴, 뒤로가기, 선택 피드백 등 공통 시선 UX 레이어 설계
  - AI 시선 추적 런타임과 프론트엔드 화면 간 연동 구조 정리
  - 추천 문장, TTS, WebSocket 등 AI·실시간 기능 연동
- **Tech**: React, TypeScript, Vite, Zustand, Axios, WebSocket/STOMP, TailwindCSS
- **Links**: [Repo](https://github.com/hyeryeongeda/eyespeak)

---

### 3) ARNNECT — 신진 예술가와 사용자를 연결하는 예술 큐레이션 플랫폼

ARNNECT는 사용자가 작품을 발견하고, 저장·리뷰·댓글·팔로우 등의 상호작용을 통해 취향을 확장할 수 있는 예술 플랫폼입니다.

- **Role**: Frontend
- **Keywords**: Art Curation · 3D Exhibition · Role-based Routing · API Mapping
- **Contribution**
  - React Router 기반 페이지 라우팅 및 레이아웃 구조 설계
  - 일반 사용자/예술가 역할 기반 접근 제어 구현
  - JWT 인증 흐름 연동 및 로그인 상태 관리
  - 작품, 리뷰, 댓글, 팔로우, 팬레터, 티켓/컬렉트북 등 주요 API 연동
  - Three.js 기반 3D 전시관 뷰어 구현 및 작품 이미지 동적 반영 구조 설계
  - API 응답 필드명과 이미지 경로가 불안정한 상황에서 매퍼/유틸 레이어로 UI 안정성 개선
- **Tech**: React, TypeScript, Vite, React Router, Zustand, Axios, Three.js, @react-three/fiber
- **Links**: [Repo](https://github.com/hyeryeongeda/ARNNECT)

---

## 🧩 Problem Solving

### AI 결과를 사용자가 검토 가능한 UI로 구조화

P2U에서는 AI 분석 결과가 JSON 또는 좌표 데이터로만 제공될 경우, 사용자가 원본 도면과 비교해 이해하기 어려운 문제가 있었습니다.  
이를 해결하기 위해 도면 영역, 결과 객체 표시, 상세 정보 패널, 확대/축소 흐름을 분리해 검토 중심 UI를 설계했습니다.

---

### 시선 입력 UX의 공통 정책 정리

EyeSpeak에서는 사용자가 마우스나 터치가 아닌 시선으로 서비스를 조작해야 했기 때문에 일반적인 클릭 UX를 그대로 적용할 수 없었습니다.  
2×3 그리드, 선택 피드백, 전역 메뉴, 뒤로가기 정책을 공통 UX 시스템으로 정리해 환자모드 주요 기능을 일관된 흐름으로 사용할 수 있게 구성했습니다.

---

### 불안정한 API 응답 구조 대응

ARNNECT에서는 백엔드 응답의 필드명, 이미지 경로, 타입이 화면마다 달라 컴포넌트가 복잡해지는 문제가 있었습니다.  
이를 UI에서 직접 처리하지 않고 매퍼와 URL 정규화 유틸을 통해 화면 모델로 변환하여, 컴포넌트가 안정적인 데이터 구조를 기준으로 렌더링되도록 개선했습니다.

---

## 🎯 Currently Focusing On

- React/TypeScript 기반 프론트엔드 구조 설계
- WPF 기반 데스크톱 UI 구현
- Zustand 기반 상태 관리와 화면 흐름 정리
- API 응답 모델링과 매퍼 구조 개선
- AI 결과를 사용자 친화적인 UI로 시각화하는 방식
- 사용자 흐름, 예외 상태, 인터랙션 정책 정리

---

## 🛠 Tech Stack

<div align="center">

<!-- Core Frontend -->
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=000"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=fff"/>
<img src="https://img.shields.io/badge/JavaScript-FFE873?style=for-the-badge&logo=javascript&logoColor=000"/>
<img src="https://img.shields.io/badge/WPF-512BD4?style=for-the-badge&logo=dotnet&logoColor=fff"/>

<br/>

<!-- Frontend Tools -->
<img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=fff"/>
<img src="https://img.shields.io/badge/React%20Router-CA4245?style=for-the-badge&logo=reactrouter&logoColor=fff"/>
<img src="https://img.shields.io/badge/Zustand-000000?style=for-the-badge&logo=ghost&logoColor=fff"/>
<img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=fff"/>

<br/>

<!-- UI / Visualization -->
<img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=fff"/>
<img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=fff"/>
<img src="https://img.shields.io/badge/r3f-000000?style=for-the-badge&logo=react&logoColor=fff"/>

<br/>

<!-- Collaboration -->
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=fff"/>
<img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=fff"/>
<img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=fff"/>
<img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=000"/>

</div>

---

## 💻 Algorithm

<div align="center">

[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=gaeryeong)](https://solved.ac/gaeryeong)

</div>

---

## 📊 GitHub Stats

<div align="center">

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=hyeryeongeda&layout=compact&theme=tokyonight)

</div>

---

## 📝 Writing

[Blog](https://premiereneige.tistory.com/)

---

## 📬 Contact

<div align="center">

[![Email](https://img.shields.io/badge/Email-ADD8E6?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gaeryeongeda@naver.com)

</div>

---

<div align="center">

꾸준히 기록하고, 사용자에게 더 나은 흐름을 제공하는 프론트엔드 개발자로 성장하고 있습니다.

</div>

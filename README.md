<div align="center">

# 신영빈 · Youngbin Shin

**PM형 빌더 · Product Engineer**

사용자 문제를 검증하고 제품·운영 성과로 연결합니다.<br/>
AI의 불확실성은 제품 구조 안에서 제어합니다.

<br/>

`한양대학교 컴퓨터소프트웨어학부` · `문제 정의 → 검증 → 실행 → 개선`

<a href="mailto:youngbin03@hanyang.ac.kr"><img src="https://img.shields.io/badge/Email-youngbin03@hanyang.ac.kr-24292f?style=flat-square&logo=gmail&logoColor=white" alt="email" /></a>
<a href="https://github.com/youngbin03"><img src="https://img.shields.io/badge/GitHub-@youngbin03-24292f?style=flat-square&logo=github&logoColor=white" alt="github" /></a>

</div>

---

## About

개발은 머릿속 아이디어를 **'내 것'으로 직접 만들어내는 도구**였습니다. 0에서 1을 만들 수 있다는 감각, 그리고 그렇게 만든 것이 누군가에게 실제로 필요해지는 순간이 저를 계속 만들게 했습니다.

그래서 기능 구현에서 멈추지 않고 **사용자가 반복해서 겪는 불편을 제품 구조로 줄이는 개발**에 집중합니다. 여러 서비스를 직접 기획·개발·운영했고, 동아리 대표·팀 리드로서 기획·디자인·개발 사이를 조율했습니다. 정답이 없는 상태에서도 문제를 빠르게 구조화하고, 작은 실험으로 판단 근거를 만듭니다.

최근에는 AI를 제품에 녹일 때의 핵심을 **"AI 생성 결과의 불확실성을 제품 구조 안에서 어떻게 제어할지"** 로 보고, 슬라이드 합성 엔진 **Stencil**에서 이를 실험하고 있습니다.

---

## Featured Work

> 문제를 검증하고, 만들고, 운영하고, **끝내는 결정까지** — 중요한 순서대로.

### 떠리 (Thurry) · 제품 · 운영 · BM
`2024.12 – 2025.09` · `5인 팀 리드` · `Flutter · Firebase`

마감임박 베이커리 할인 서비스. 오픈채팅 설문에서 **70% 이용 의향**을 확인한 뒤 착수해 4개월 만에 월 매출을 2배로 키웠습니다. 전액 패스 할인으로 결제액이 0원이 되는 경로를 **sentinel 키 패턴**으로 설계해, 분기 없이 유·무료 결제를 하나의 파이프라인으로 통합했습니다. 패스권 BM 검증에서 350명 중 11%만 구매·재구매 2명이라는 행동 데이터를 근거로 **서비스를 종료**했습니다.

→ [github.com/youngbin03/thurry-client](https://github.com/youngbin03/thurry-client)

### CLIP (클립) · 제품 구조 설계
`2025.07 – 2025.12` · `2인` · `Next.js 15 · Gemini · Google Calendar`

동아리 운영관리 서비스. 데모 30명·4개 팀 테스트에서 이탈 원인을 **기능 부족보다 진입장벽**으로 재정의했습니다. 튜토리얼을 더하는 대신 **AI 채팅**을 도입해 "이번 주 5명 모일 시간 찾아줘"처럼 자연어로 일정을 조율하게 했고, **모바일=참여자 / 웹=운영자**로 역할을 분리한 협업 캘린더 구조 전환을 주도했습니다.

→ [github.com/youngbin03/clip-landing](https://github.com/youngbin03/clip-landing)

### Stencil · AI 시스템 설계
`2026` · `개인` · `Anthropic SDK · TypeScript · Next.js`

슬라이드 합성 엔진. **"AI는 의미를 판단하고, 코드는 픽셀을 책임진다"** 는 원칙으로 좌표·측정·충돌 회피는 결정론 코드가, 의미 해석만 모델이 처리합니다. 생성 결과를 **7개 품질 지표**로 채점해 기준 미달은 자동 수정하거나 폐기하는 평가 루프(Evaluator–optimizer)를 설계했고, Vision-in-the-loop로 렌더링에서 깨지는 결과까지 픽셀 단위로 검증합니다.

→ [github.com/youngbin03/stencil](https://github.com/youngbin03/stencil) · [Live](https://stencil-web.vercel.app/) · [Report](https://youngbin03.github.io/stencil/)

### 오늘의 식냥 · 정보 구조 · 운영
`2024.02 – 2024.09` · `Flutter`

식당별로 흩어진 한양대 서울캠퍼스 학식 정보를 한 화면에 통합해 **2,000+ 사용자**가 7개월간 안정적으로 사용했습니다. 메뉴 이미지 지연 시 화면 신뢰도가 떨어지는 문제를 스케줄러·스크래핑·히스토리 DB로 해결해, 이미지가 늦을 때 과거 유사 메뉴를 대체 노출하며 빈 화면 없이 정보를 제공했습니다.

→ [github.com/youngbin03/daily-hyu-menu-frontend](https://github.com/youngbin03/daily-hyu-menu-frontend)

---

## Stack

**Frontend**
<br/>
<img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" />
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />

**Language**
<br/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />

**AI · Backend**
<br/>
<img src="https://img.shields.io/badge/Anthropic_SDK-D97757?style=flat-square&logo=anthropic&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white" />

**Tools**
<br/>
<img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white" />
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />

---

<div align="center">
<sub>© 2026 신영빈 · 한양대학교 컴퓨터소프트웨어학부</sub>
</div>

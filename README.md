# 🤟 TEAM ALL_IS_WELL
<br>

**0.9 version**
<br>
**업데이트 일자: 2025.09.14**


### 📌 개요
해당 레포지토리는 **2025년 2학기 이화여자대학교 컴퓨터공학과**  
**‘캡스톤디자인과창업프로젝트A’** 과목의 **3팀, ‘세얼간이’** 가 웹서비스 구현을 목표로 수행하는 프로젝트입니다.

---

### 🎯 프로젝트 목표
- 소규모 팀(5~6인)을 대상으로 협업 과정에서 발생하는 **소통의 어려움과 참여 불균형 문제를 해소**
- **AI 기반 피드백 및 참여도 분석**을 통해 팀원 간 갈등을 완화하고, 직접적으로 하기 어려운 피드백을 대신 전달하도록 지원
- 회의록 기록 자동화, 발화 비율 분석, 기여도 시각화 등 다양한 도구를 제공하여 **프로젝트 진행 상황 관리 지원**
- 리더는 팀의 건강도 및 상태를 쉽게 관리하고, 팀원 개개인에게 **보다 공정하고 효율적인 협업 환경**을 제공

---
### 🔑 주요 기능

1. **AI 대리 피드백 기능**
    - 익명 또는 AI를 통한 간접 피드백 제공
    - 갈등 상황을 완화하고, 소극적인 팀원도 의견을 표현할 수 있도록 지원
2. **참여도 및 기여도 시각화**
    - 회의 상 팀원 별 발화 비율 그래프 제공
    - GitHub 커밋, 공지 반응 적극도 등 팀 활동 지표를 분석하여 리포트 형태로 제공
3. **회의록 및 기록 관리**
    - 회의 발언 내용을 자동 정리하여 회의록 생성
    - 회의 단계 별 확인(체크) 기능으로 팀원 간 이해 차이를 줄임
4. **프로젝트 리포트 자동 생성**
    - 일정 지연, 참여도, 피드백 내용을 종합한 주간/월간 리포트 제공
    - 프로젝트 종료 후 최종 회고 리포트를 자동으로 생성하여 팀 성장을 돕는 자료로 활용

---



### ⚙️ Tech Stack

<div align="center">

**Frontend**  
<img src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=white&style=for-the-badge"/> 
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black&style=for-the-badge"/>

**Backend**  
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?logo=springboot&logoColor=white&style=for-the-badge"/>
<img src="https://img.shields.io/badge/Java-007396?logo=java&logoColor=white&style=for-the-badge"/>

**Database**  
<img src="https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white&style=for-the-badge"/>

**AI API**  
<img src="https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white&style=for-the-badge"/> 
<img src="https://img.shields.io/badge/HuggingFace-FFAE00?logo=huggingface&logoColor=black&style=for-the-badge"/>  

**Collaboration Tools**  
<img src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white&style=for-the-badge"/> 
<img src="https://img.shields.io/badge/Slack-4A154B?logo=slack&logoColor=white&style=for-the-badge"/> 
<img src="https://img.shields.io/badge/Notion-000000?logo=notion&logoColor=white&style=for-the-badge"/> 
<img src="https://img.shields.io/badge/Discord-5865F2?logo=discord&logoColor=white&style=for-the-badge"/>
</div>


---
### 👽 팀원 소개

<table>
  <tbody>
    <tr>
      <td align="center">
        <img src="https://img.shields.io/badge/Team%20Member-fb69a3" /><br> <a href="https://github.com/monshelle"><img src="https://github.com/monshelle.png" width="100px;" alt="강민지"/></a> </td>
      <td align="center">
        <img src="https://img.shields.io/badge/Team%20Member-04e0d5" /><br> <a href="https://github.com/WHITENOISE523"><img src="https://github.com/WHITENOISE523.png" width="100px;" alt="임이랑"/></a> </td>
            <td align="center">
        <img src="https://img.shields.io/badge/Team%20Leader-8629f9" /><br> <a href="https://github.com/yoozafree"><img src="https://github.com/yoozafree.png" width="100px;" alt="정서윤"/></a> </td>
    </tr>
    <tr>
      <td align="center"><b>강민지</b></td> 
      <td align="center"><b>임이랑</b></td> 
      <td align="center"><b>정서윤</b></td>
    </tr>
    <tr>
      <td align="center">BE</td>
      <td align="center">FE</td>
      <td align="center">BE</td>
    </tr>
  </tbody>
</table>

---

### 🗓 진행 일정
- **2025.09 ~ 2025.12.21**: 기획 및 프로토타입

---
### 📂 레포지토리 구조
```
aiw/
├── backend/ # Spring 서버 코드
├── frontend/ # React 프론트엔드 코드
├── docs/ # 회의록, 설계 문서
├── .github/ # 워크플로우 및 이슈 템플릿
└── README.md
```

---

### 🧾 코드 컨벤션

커밋 메시지는 다음 규칙에 맞춰 작성합니다

> 📌 예시: **`✨ feat: sign up complete`**

---

| 태그                | 설명                                      |
|-------------------|-----------------------------------------|
| ✨ **feat**        | 새로운 기능 추가                               |
| 🐛 **fix**        | 버그 수정                                   |
| 📝 **docs**       | 문서 수정 (README 등)                        |
| 💄 **style**      | 코드 포맷팅, 세미콜론 누락, 코드 변경 없음               |
| ♻️ **refactor**   | 코드 리팩토링 (기능 변화 없이 구조 개선)                |
| ✅ **test**        | 테스트 코드 추가, 기존 테스트 리팩토링                  |
| 🔧 **chore**      | 빌드 설정 변경, 패키지 매니저 설정 등                  |
| 🔀 **merge**      | 브랜치 병합 (예: `merge: main` → main과 병합했음) |
| 📍 **checkpoint** | 진행중(체크포인트)                              |
| 🎨 **design**     | 뷰 디자인 변경                                |

---


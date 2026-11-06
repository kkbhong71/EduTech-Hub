# 🌿 열정맨 에듀테크 허브

> **오성중학교 EduTech Hub** — 교육 행정 시스템부터 데이터 사이언스까지, 학교를 위한 디지털 솔루션

🔗 **사이트 바로가기:** [https://kkbhong71.github.io/EduTech-Hub/](https://kkbhong71.github.io/EduTech-Hub/)

---

## 📋 프로젝트 소개

이 포털은 오성중학교에서 AI 바이브 코딩을 활용하여 개발한 다양한 교육용 웹앱과 도구를 한 곳에서 관리하고 공유하기 위해 만들어졌습니다.

### 카테고리

| 카테고리 | 설명 |
|---------|------|
| 🏫 학교 업무 효율화 | 동료장학, 장학금, 동아리, 방과후학교 등 행정 시스템 |
| 📊 학력 데이터 분석 | 성적 대시보드, 기초학력 향상 모니터링 |
| 📚 프로그램 개발 가이드 | Flask 배포 가이드, 앱 개발 절차 설명서 |
| 🎯 데이터 사이언스 | LottoPro-AI, LOTTO ORACLE 등 데이터 분석 프로젝트 |
| 💡 유용한 앱 | 교육 현장에서 활용 가능한 유틸리티 앱 |
| 🎓 교육용 웹앱 | 학생 교육 목적의 인터랙티브 웹앱 |

> 카테고리는 관리자 패널에서 자유롭게 추가/수정/삭제할 수 있습니다.

---

## 🛠️ 기술 스택

- **프론트엔드:** HTML, CSS, JavaScript (순수 바닐라 — 프레임워크 없음)
- **호스팅:** GitHub Pages (무료)
- **데이터 관리:** `projects.json` + GitHub API 자동 커밋
- **개발 방식:** AI 바이브 코딩 (Claude 활용)

---

## ⚙️ 관리자 패널 사용법

사이트 우측 하단의 ⚙️ 버튼을 클릭하면 관리자 패널에 접근할 수 있습니다.

### 관리자 패널에서 가능한 작업

- ✅ 프로젝트 추가 / 수정 / 삭제
- ✅ 카테고리 추가 / 수정 / 삭제 (이름, 아이콘 변경 가능)
- ✅ 변경 사항이 GitHub에 자동 커밋

### 사전 준비: GitHub Token 발급

관리자 패널에서 프로젝트를 관리하려면 **GitHub Personal Access Token**이 필요합니다 (최초 1회 설정).

#### 1단계: 토큰 생성 페이지 이동

브라우저에서 아래 주소로 접속합니다:

```
https://github.com/settings/tokens
```

또는 수동 경로:
> GitHub 우측 상단 **프로필 사진** → **Settings** → 왼쪽 메뉴 맨 아래 **Developer settings** → **Personal access tokens** → **Tokens (classic)**

⚠️ **주의:** 저장소 Settings (`github.com/kkbhong71/EduTech-Hub/settings`)가 **아닌**, 개인 계정 Settings (`github.com/settings`)로 가야 합니다!

#### 2단계: 토큰 생성

**Generate new token** → **Generate new token (classic)** 클릭 후 설정:

| 항목 | 설정값 |
|------|--------|
| **Note** | `EduTech Hub 관리용` |
| **Expiration** | `No expiration` (만료 없음) |
| **Select scopes** | `repo` 체크 ✅ (하위 항목 자동 체크됨) |

설정 후 **Generate token** 클릭

#### 3단계: 토큰 복사

> ⚠️ **이 페이지를 벗어나면 토큰을 다시 볼 수 없습니다!**

`ghp_`로 시작하는 토큰을 📋 복사 아이콘으로 복사하고, 안전한 곳에 백업 저장합니다.

#### 4단계: 에듀테크 허브에 등록

1. [에듀테크 허브](https://kkbhong71.github.io/EduTech-Hub/) 접속
2. 우측 하단 ⚙️ → 비밀번호 입력 → 로그인
3. 🔑 GitHub 토큰 입력란에 붙여넣기 → **저장**
4. "✅ 토큰 설정 완료" 확인

---

## 📂 파일 구조

```
EduTech-Hub/
├── index.html        ← 메인 포털 사이트 (관리자 패널 내장)
├── projects.json     ← 프로젝트 데이터 (관리자 패널에서 자동 관리)
└── README.md         ← 이 문서
```

---

## 🔒 보안 참고

- 관리자 패널은 비밀번호로 보호됩니다
- GitHub Token은 브라우저의 localStorage에 저장됩니다 (서버 전송 없음)
- 학생 개인정보가 포함된 대시보드는 별도 비밀번호 잠금이 적용되어 있습니다

---

## 📌 참고 사항

- **토큰 분실 시:** `github.com/settings/tokens`에서 새로 발급 → 관리자 패널에서 "변경"
- **만료된 토큰:** 목록에서 Delete로 삭제 가능
- **다른 기기:** 토큰은 브라우저별로 저장되므로, 다른 기기에서는 다시 입력 필요

---

<p align="center">
  <strong>🌿 Oseong Vibe Coding EduHub</strong><br>
  <sub>Made with 💚 by 열정맨 · 오성중학교 · AI 바이브 코딩으로 제작</sub>
</p>

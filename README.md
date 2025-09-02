# 📦 Vision Price Manage
OCR과 API를 활용한 **실시간 상품 최저가 비교 애플리케이션**

---

## ✨ 프로젝트 소개
이 프로젝트는 사용자가 상품 이미지를 업로드하면  
OCR을 통해 텍스트를 추출하고, 여러 쇼핑몰 API와 연동하여  
해당 상품의 **실시간 최저가를 비교/조회**할 수 있도록 하는 서비스입니다.

---

## 👥 팀 소개
- **팀명**: Vision Price Manage
- **구성원**: 2명
  - 👩‍💻 Member A : 앱/프론트엔드 개발
  - 👨‍💻 Member B : 서버/백엔드 개발  
  (역할은 상황에 따라 유동적으로 변경될 수 있음)

---

## 🛠️ 기술 스택
- **Frontend**: Kotlin (Android, Jetpack Compose)
- **Backend**: (예정 – Flask, Spring, 또는 FastAPI 중 선택 가능)
- **Database**: MySQL / RoomDB
- **API & Services**: Google Cloud Vision API
- **협업 도구**: GitHub Projects, Notion

---

## 📂 프로젝트 구조
.github/ # 협업용 GitHub 템플릿 (Issue, PR)
app/ # Android 앱 코드
server/ # 서버 코드 (예정)
docs/ # 문서 및 발표 자료
README.md

---

## 🚀 주요 기능
- 📷 상품 이미지 업로드 → OCR 텍스트 추출
- 🔎 API 연동을 통한 상품 가격 정보 수집
- 💰 최저가 비교 및 결과 제공
- 📊 GitHub Projects + Notion을 통한 일정 관리

---

## 📌 협업 규칙
- **Issue 관리**  
  - 기능 추가: `✨ 기능 추가` 템플릿 사용  
  - 버그 수정: `🐞 버그 제보` 템플릿 사용  
  - 코드 개선: `🛠️ 리팩토링` 템플릿 사용  

- **브랜치 규칙**  
  - `main` : 안정적인 버전  
  - `feature/*` : 새로운 기능 개발  
  - `fix/*` : 버그 수정  
  - `docs/*` : 문서 작업  

- **PR 규칙**  
  - 반드시 관련 Issue 연결 (`Closes #번호`)  
  - PR 템플릿을 사용하여 작업 내역 작성  
  - 최소 1명 확인 후 Merge

---

## 📅 진행 상황
- [x] GitHub 협업 환경 세팅 (Issue, PR 템플릿)
- [ ] Android 기본 프로젝트 세팅
- [ ] Google Cloud Vision API 연동
- [ ] 가격 비교 로직 구현
- [ ] UI/UX 디자인 적용
- [ ] 최종 테스트 및 배포

---

## 📖 참고 자료
- [Google Cloud Vision API Docs](https://cloud.google.com/vision/docs)
- [GitHub Projects Guide](https://docs.github.com/en/issues/planning-and-tracking-with-projects)

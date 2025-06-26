# 이재민 포트폴리오 웹사이트

깔끔하고 미니멀한 디자인의 개인 포트폴리오 웹사이트입니다.

## 🌟 특징

- **반응형 디자인** : 모바일, 태블릿, 데스크톱 모든 기기에서 최적화
- **미니멀 디자인** : 깔끔하고 읽기 쉬운 인터페이스
- **빠른 로딩** : 정적 HTML/CSS/JS로 구성되어 빠른 성능
- **SEO 최적화** : 메타 태그와 시맨틱 HTML 구조

## 📁 파일 구조

```
/
├── index.html                    # 메인 페이지 (Hero 섹션)
├── about.html                    # 소개 페이지 (기술 스택, 타임라인)
├── projects.html                 # 프로젝트 페이지 (포트폴리오)
├── insights.html                 # 개발 철학 페이지
├── contact.html                  # 연락처 페이지
├── project-studyon.html          # StudyOn 프로젝트 상세 페이지
├── project-board.html            # Spring Boot 게시판 프로젝트 상세 페이지
├── project-card-car.html         # 법인카드·차량 관리 프로젝트 상세 페이지
├── project-card-enjoyfood.html   # EnjoyFood 프로젝트 상세 페이지
├── project-coffee.html           # J's Coffee 프로젝트 상세 페이지
├── project-set-calculator.html   # 제품 세트 계산기 프로젝트 상세 페이지
├── css/
│   └── style.css                 # 메인 스타일시트
├── js/
│   └── main.js                   # JavaScript 기능
└── assets/                       # 이미지 및 기타 자산
    ├── studyon.png              # StudyOn 프로젝트 스크린샷
    ├── card_car_used.png        # 법인카드·차량 관리 스크린샷
    ├── coffee.png               # J's Coffee 스크린샷
    ├── enjoyfood.png            # EnjoyFood 스크린샷
    ├── set_calculator.png       # 제품 세트 계산기 스크린샷
    └── spring_board.png         # Spring Boot 게시판 스크린샷
```

## 🚀 Netlify 배포 방법

### 1. GitHub 연동 배포 (권장)

1. [Netlify](https://netlify.com)에 로그인
2. "New site from Git" 클릭
3. GitHub 연결 후 `qwer123toy/webpage` 저장소 선택
4. 배포 설정:
   - **Build command**: 비워두기 (정적 사이트)
   - **Publish directory**: `/` (루트 디렉토리)
5. "Deploy site" 클릭

### 2. 드래그 앤 드롭 배포

1. 프로젝트 폴더의 모든 파일을 압축
2. Netlify 대시보드에서 "Deploy manually" 선택
3. 압축 파일을 드래그 앤 드롭

## 🛠️ 기술 스택

- **Frontend** : HTML5, CSS3, JavaScript (ES6+)
- **스타일링** : CSS Grid, Flexbox, CSS Variables
- **반응형** : Mobile-first 접근법
- **호스팅** : Netlify (정적 사이트 호스팅)

## ✨ 주요 기능

- **네비게이션** : 고정 헤더와 모바일 햄버거 메뉴
- **Hero 섹션** : 큰 타이포그래피와 CTA 버튼
- **프로젝트 카드** : Hover 효과가 있는 인터랙티브 카드
- **연락처** : 이메일 링크와 소셜 미디어 연결
- **스무스 스크롤** : 부드러운 페이지 내 이동

## 🎨 디자인 참고

- [Gary Sheng's Stack](https://stack.garysheng.com/)
- [Matt Will Dev](https://mattwilldev.com/)

## 📱 반응형 브레이크포인트

- **모바일** : 480px 이하
- **태블릿** : 768px 이하
- **데스크톱** : 768px 이상

## 🔧 커스터마이징

### 색상 변경
`css/style.css` 파일에서 CSS 변수를 수정하여 색상을 변경할 수 있습니다.

### 내용 수정
각 HTML 파일을 직접 편집하여 개인 정보와 프로젝트 내용을 업데이트하세요.

### 새로운 페이지 추가
1. 새 HTML 파일 생성
2. 네비게이션 메뉴에 링크 추가
3. 동일한 헤더/푸터 구조 유지

## 📞 연락처

- **Email** : qwer123toy@gmail.com
- **GitHub** : [github.com/qwer123toy](https://github.com/qwer123toy)

---

© 2025 Jaemin Lee. All rights reserved. 

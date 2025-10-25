# 디지털 명함 홈페이지 🎴

현대적이고 세련된 디자인의 개인 명함 웹사이트입니다.

## 프로젝트 개요

이 프로젝트는 개인 브랜딩을 위한 디지털 명함 웹사이트로, 프로필, 기술 스택, 연락처 정보를 매력적으로 표현합니다.

## 주요 기능

### ✅ 구현된 기능

1. **반응형 디자인**
   - 모바일, 태블릿, 데스크톱 모든 기기에 최적화
   - 미디어 쿼리를 활용한 적응형 레이아웃

2. **프로필 섹션**
   - 프로필 이미지 (UI Avatars API 사용)
   - 이름, 직함, 간단한 소개

3. **기술 스택 표시**
   - JavaScript, React, Vue.js, TypeScript 등
   - 호버 시 인터랙티브 애니메이션

4. **연락처 정보**
   - 이메일, 전화번호
   - GitHub, LinkedIn 링크
   - 클릭 가능한 링크로 즉시 연결

5. **소셜 미디어 링크**
   - GitHub, LinkedIn, Twitter, Instagram
   - 원형 아이콘 버튼으로 표현

6. **명함 저장 기능**
   - vCard(.vcf) 형식으로 다운로드
   - 스마트폰 연락처에 바로 추가 가능

7. **인터랙티브 효과**
   - 3D 카드 틸트 효과
   - 마우스 추적 배경 애니메이션
   - 부드러운 호버 트랜지션
   - 알림 토스트 메시지

8. **배경 애니메이션**
   - 그라데이션 배경
   - 플로팅 도형 애니메이션
   - 마우스 인터랙션

## 기술 스택

- **HTML5**: 시맨틱 마크업
- **CSS3**: 
  - CSS Variables
  - Flexbox
  - Grid Layout
  - Animations & Transitions
  - 반응형 디자인
- **JavaScript (Vanilla JS)**:
  - DOM 조작
  - 이벤트 핸들링
  - LocalStorage
  - Blob API
- **외부 라이브러리**:
  - Font Awesome 6.4.0 (아이콘)
  - Google Fonts - Noto Sans KR (한글 폰트)

## 파일 구조

```
.
├── index.html          # 메인 HTML 파일
├── css/
│   └── style.css      # 스타일시트
├── js/
│   └── script.js      # JavaScript 인터랙션
└── README.md          # 프로젝트 문서
```

## 주요 페이지 경로

- **메인 페이지**: `/index.html`
  - 모든 콘텐츠가 단일 페이지에 표시
  - 원페이지 스크롤 디자인

## 사용 방법

### 정보 수정하기

1. **개인 정보 변경** (`index.html`):
   - 이름: `.name` 클래스의 내용 수정
   - 직함: `.title`, `.subtitle` 클래스의 내용 수정
   - 소개글: `.intro-text` 클래스의 내용 수정

2. **연락처 수정** (`index.html`):
   - 이메일: `mailto:` 링크의 주소 변경
   - 전화번호: `tel:` 링크의 번호 변경
   - SNS 링크: `href` 속성의 URL 변경

3. **기술 스택 수정** (`index.html`):
   - `.skill-tag` 요소 추가/삭제/수정

4. **프로필 이미지 변경**:
   - 현재: UI Avatars API 사용 (자동 생성)
   - 변경: `<img src="">` 의 주소를 원하는 이미지 URL로 변경

5. **색상 테마 변경** (`css/style.css`):
   ```css
   :root {
       --primary-color: #667eea;    /* 메인 색상 */
       --secondary-color: #764ba2;   /* 보조 색상 */
   }
   ```

### vCard 다운로드 정보 수정

`js/script.js`의 `downloadVCard()` 함수에서 정보 수정:
```javascript
const vCardData = `BEGIN:VCARD
VERSION:3.0
FN:본인 이름
N:성;이름;;;
TITLE:직함
TEL;TYPE=CELL:전화번호
EMAIL:이메일
...
END:VCARD`;
```

## 브라우저 호환성

- Chrome (최신 버전)
- Firefox (최신 버전)
- Safari (최신 버전)
- Edge (최신 버전)
- 모바일 브라우저 완벽 지원

## 라이선스

이 프로젝트는 자유롭게 사용, 수정, 배포할 수 있습니다.

## 제작 정보

- **제작일**: 2024
- **버전**: 1.0.0
- **제작자**:  (하재영)

---

💡 **팁**: 모든 정보를 본인의 것으로 변경하여 사용하세요!

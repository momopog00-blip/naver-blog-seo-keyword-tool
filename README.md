# 네이버 블로그 SEO 키워드 추천 도구 🚀

[![GitHub License](https://img.shields.io/github/license/momopog00-blip/naver-blog-seo-keyword-tool)](https://github.com/momopog00-blip/naver-blog-seo-keyword-tool/blob/main/LICENSE)
[![GitHub Pages](https://img.shields.io/badge/demo-live-brightgreen)](https://momopog00-blip.github.io/naver-blog-seo-keyword-tool/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat&logo=chart.js&logoColor=white)](https://www.chartjs.org/)

> 블로거들이 상위 노출에 유리한 키워드를 쉽게 찾을 수 있는 실용적인 SEO 도구입니다.

## 🌟 주요 기능

### 🎯 핵심 기능
- **스마트 키워드 생성**: 입력한 키워드를 기반으로 30개의 연관 키워드 자동 생성
- **SEO 점수 분석**: 1-100점 척도의 SEO 최적화 점수 제공
- **검색량 예측**: 상/중/하 단계별 예상 검색량 표시
- **경쟁도 분석**: 쉬움/보통/어려움 난이도 평가

### 📊 시각화 기능
- **키워드 클라우드**: 상위 키워드를 시각적으로 표현
- **점수 분포 차트**: Chart.js 기반 도넛차트로 키워드 점수 분포 시각화
- **반응형 디자인**: 모바일, 태블릿, 데스크톱 모든 디바이스 최적화

### 🔧 편의 기능
- **카테고리별 추천**: 음식, 여행, 뷰티, 취미, IT 분야별 특화 키워드
- **정렬 기능**: 점수순, 검색량순, 경쟁도순, 키워드순 정렬
- **즐겨찾기**: 관심 키워드 북마크 기능
- **검색 히스토리**: 최근 검색한 키워드 10개 자동 저장
- **데이터 내보내기**: CSV, Excel 파일로 결과 다운로드

## 🛡️ 보안 특징

### OWASP Top 10 준수
- **XSS 방지**: 모든 사용자 입력에 대한 HTML 이스케이프 처리
- **CSP 정책**: Content Security Policy 헤더 적용
- **입력 검증**: 패턴 매칭을 통한 안전한 데이터 처리
- **SRI 해시**: 외부 라이브러리 무결성 검증
- **안전한 DOM 조작**: innerHTML 대신 안전한 DOM API 사용

### 데이터 보호
- **클라이언트 사이드**: 모든 데이터 처리가 브라우저에서 수행
- **개인정보 수집 없음**: 서버로 전송되는 개인데이터 없음
- **localStorage 암호화**: 로컬 데이터의 안전한 저장

## 🚀 사용법

### 기본 사용법
1. **키워드 입력**: 검색창에 원하는 키워드를 입력
2. **카테고리 선택**: 전체 또는 특정 분야 카테고리 선택
3. **분석 시작**: "키워드 분석" 버튼 클릭
4. **결과 확인**: 생성된 키워드 목록과 점수 확인

### 고급 기능 활용
- **정렬**: 헤더의 정렬 버튼으로 원하는 순서로 정렬
- **즐겨찾기**: ♥ 버튼으로 중요한 키워드 저장
- **내보내기**: CSV나 Excel로 결과 다운로드
- **히스토리**: 과거 검색 키워드 클릭으로 빠른 재검색

### 테스트 키워드 예시
프로젝트 배포 후 다음 키워드로 동작을 확인해보세요:
- `치킨` - 음식 관련 키워드
- `제주도` - 여행 관련 키워드  
- `다이어트` - 건강 관련 키워드
- `인테리어` - 라이프스타일 키워드

## 🛠️ 기술 스택

### Frontend
- **HTML5**: 시맨틱 마크업과 현대적 웹 표준
- **CSS3**: Flexbox, Grid, 애니메이션, 반응형 디자인
- **JavaScript (ES6+)**: 모듈화, 클래스 기반 아키텍처

### 라이브러리
- **Chart.js (v4.4.0)**: 데이터 시각화
- **XLSX (v0.18.5)**: Excel 파일 생성
- **SRI 해시**: 라이브러리 무결성 보장

### 스토리지
- **localStorage**: 검색 히스토리 및 즐겨찾기 저장
- **클라이언트 사이드**: 완전한 오프라인 작동

## 📁 프로젝트 구조

```
naver-blog-seo-keyword-tool/
├── index.html          # 메인 애플리케이션 파일
├── README.md           # 프로젝트 문서
└── LICENSE            # MIT 라이선스
```

## 🚀 배포 및 호스팅

### GitHub Pages 배포
이 프로젝트는 GitHub Pages를 통해 자동 배포됩니다.

**라이브 데모**: [https://momopog00-blip.github.io/naver-blog-seo-keyword-tool/](https://momopog00-blip.github.io/naver-blog-seo-keyword-tool/)

### 로컬 실행
```bash
# 저장소 클론
git clone https://github.com/momopog00-blip/naver-blog-seo-keyword-tool.git

# 디렉토리 이동
cd naver-blog-seo-keyword-tool

# 브라우저에서 index.html 실행
# 또는 로컬 서버 실행 (예: Live Server)
```

## 🤝 개발팀

- **민호**: 핵심 기능 개발 및 UI/UX 설계
- **준호**: 품질 보증 및 테스트 검증
- **진수**: 보안 검토 및 취약점 패치

## 📝 라이선스

이 프로젝트는 [MIT 라이선스](LICENSE) 하에 배포됩니다.

## 🔄 업데이트 로그

### v1.0.0 (2025-08-02)
- 초기 릴리즈
- 키워드 생성 엔진 구현
- SEO 점수 알고리즘 개발
- 보안 강화 (OWASP Top 10 준수)
- 반응형 UI/UX 완성
- Chart.js 시각화 구현
- CSV/Excel 내보내기 기능

## 🎯 향후 계획

- [ ] 실제 검색 데이터 API 연동
- [ ] 키워드 트렌드 분석 기능
- [ ] 다국어 지원 (영어, 일본어)
- [ ] PWA (Progressive Web App) 지원
- [ ] 키워드 성과 추적 기능

## 🐛 버그 리포트 & 기능 요청

버그를 발견하거나 새로운 기능을 제안하고 싶다면 [Issues](https://github.com/momopog00-blip/naver-blog-seo-keyword-tool/issues)에 등록해주세요.

---

<div align="center">

**⭐ 이 프로젝트가 도움이 되었다면 Star를 눌러주세요! ⭐**

Made with ❤️ for Korean Bloggers

</div>
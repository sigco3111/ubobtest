# ubob_webtest

Web testing project for ubob application.

## 배포 정보 (Deployment Information)

### 🔗 실제 배포 페이지
**GitHub Pages**: https://sigco3111.github.io/ubobtest/

> ⭐ **주요**: 이 프로젝트는 Vercel을 통해 테스트되었으나, 실제 배포는 GitHub Pages를 통해 이루어집니다.

### Vercel 테스트
- Vercel 배포 테스트 환경
- 정적 페이지 호스팅 테스트용
- 빌드 최적화 및 설정 테스트

## 파일 구조

```
ubob_webtest/
├── index.html          # 메인 페이지
├── default.htm          # 원본 HTML 파일
├── aaa.htm             # 추가 HTML 페이지
├── package.json          # 프로젝트 설정
├── vercel.json          # Vercel 배포 설정
└── README.md            # 프로젝트 문서
```

## 배포 설정

### Vercel 설정
- `vercel.json` 파일을 통한 라우팅 설정
- 모든 경로를 `index.html`로 리다이렉트
- 정적 호스팅 최적화

### GitHub Pages 설정
- GitHub 리포지터리를 통한 배포
- `sigco3111.github.io/ubobtest/` 경로로 접속
- 자동 배포 설정 가능

## 기술 정보

- **언어**: HTML, CSS, JavaScript
- **배포**: Vercel, GitHub Pages
- **호스팅**: 정적 사이트 호스팅
- **빌드**: 필요 없는 순수 HTML 프로젝트

## 사용 방법

1. GitHub에서 소스 코드 다운로드
2. 로컬에서 `index.html` 파일 오픈
3. 또는 배포 URL에서 확인:
   - https://sigco3111.github.io/ubobtest/
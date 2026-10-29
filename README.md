# 오이비누 OIBnu

오이비누 회사 소개 홈페이지입니다. 소프트웨어 제작·유지보수 서비스와 개발 중인 사내 메신저를 소개합니다.

## 구성

- `index.html`: 홈페이지
- `styles.css`: 반응형 스타일
- `favicon.svg`: 브랜드 아이콘

빌드 단계가 없는 정적 사이트입니다.

## 로컬 확인

```bash
python3 -m http.server 4173 --bind 127.0.0.1
```

브라우저에서 `http://127.0.0.1:4173`을 엽니다.

## 배포

GitHub 저장소: `kimjh-developer/oibnu`

정적 웹 호스팅에 저장소 루트의 파일을 배포합니다. Vercel을 사용하는 경우 Framework Preset은 `Other`, Build Command는 비움, Output Directory는 `.`로 설정합니다.

이 저장소에 코드를 올리는 것과 실제 웹 호스팅 배포는 별도입니다.

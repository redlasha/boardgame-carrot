# 🥕 당근 카드뽑기

보드게임 "당근" 카드뽑기 PWA.

## 배포

이 저장소는 GitHub Pages로 배포됩니다. `main` 또는 `claude/deploy-github-pages-ZjQoP` 브랜치에 푸시되면 `.github/workflows/deploy.yml` 워크플로우가 자동으로 실행됩니다.

### Pages 활성화 방법

1. GitHub 저장소 → **Settings** → **Pages**
2. **Source**를 `GitHub Actions`로 설정
3. 워크플로우 실행 후 표시되는 URL로 접속

## 파일 구성

- `index.html` — 앱 본체
- `manifest.json` — PWA 매니페스트
- `sw.js` — 서비스 워커 (오프라인 캐시)
- `.nojekyll` — Jekyll 처리 비활성화

## 알림

`manifest.json`에서 참조하는 `icon-192.png`, `icon-512.png` 아이콘 파일은 아직 추가되지 않았습니다. PWA 설치 시 기본 아이콘이 사용됩니다.

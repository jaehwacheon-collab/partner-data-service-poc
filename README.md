# 팀무신사 인사이트 PoC

파트너 구독형 데이터 서비스 프로토타입.

## 데모

GitHub Pages 활성화 시: `https://<username>.github.io/partner-data-service-poc/`

로컬에서 열 경우: `index.html` 더블클릭

## 구조

- `index.html` / `final-prototype.html` — 통합 마스터 프로토타입 (진입점)
- `ia-wireframe.html` — IA (Information Architecture) 다이어그램
- 기본 페이지 (자유 탐색)
  - `base-uc1-ds1-wireframe.html` — DS#1 상품 성과 진단
  - `base-uc2-ds2-wireframe.html` — DS#2 고객 프로파일 진단
  - `base-uc3-ds3-wireframe.html` — DS#3 고객 반응 모니터링
- 모드 (워크플로우 가이드)
  - 매출 부진 360°: `ds1` → `ds3` → `ds2-wireframe.html` (UC1/2/3)
  - 베스트셀러 360°: `uc4` → `uc5` → `uc6-wireframe.html`
  - 라인업 정리 360°: `uc7` → `uc8` → `uc9-wireframe.html`
  - 신상품 사전 360°: `uc10` → `uc11` → `uc12-wireframe.html`

## IA 3-Layer

1. 진입점 (홈/대시보드 + 모드 카드)
2. 기본 페이지 (DS#1/2/3)
3. 데이터 깊이 (Basic / Deep / Market Layer ↔ Basic / Standard / Premium 요금제)

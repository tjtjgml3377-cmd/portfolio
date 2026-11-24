# 서재연 포트폴리오

![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-배포-0b3f3a) ![HTML](https://img.shields.io/badge/HTML%20·%20CSS-정적%20페이지-e9b949)

> 감 대신 데이터로, 아산 부동산을 읽습니다.

아산테크노밸리 현대공인중개사 대표 서재연의 포트폴리오입니다.
15년 현장 중개 경험과 Python · QGIS로 한 공공데이터 분석 작업을 한 페이지에 정리했습니다.
(서울사이버대학교 GitHub포트폴리오 수업 과제)

🌐 **사이트:** https://tjtjgml3377-cmd.github.io/portfolio/

## 페이지 구성

| 순서 | 섹션 | 내용 |
|---|---|---|
| 01 | 소개 | 하는 일과 데이터 공부를 시작한 이유 |
| 02 | 하는 일 | 부동산 중개 · 공간 데이터 분석 · 업무 자동화 |
| 03 | 프로젝트 | 터무늬 대시보드(화면 4장 · 코드 예시), 실거래가 히트맵, 주소 좌표 변환 프로그램 |
| 04 | 관심 프로젝트 | Korean Law MCP, admdongkor |
| 05 | 경력 · 학력 | 현대공인중개사 대표, 서울사이버대학교 |
| 06 | 연락 | 사무소 · GitHub · 대시보드 |

## 폴더 구조

```
portfolio/
├── index.html          # 페이지 전체
├── assets/
│   ├── style.css       # 디자인 (색: 터무늬 대시보드와 같은 녹색 · 금색)
│   └── img/            # 대시보드 화면, 등고선 배경
└── README.md
```

## 내 컴퓨터에서 보기

빌드 과정이 없는 정적 페이지라 `index.html`을 브라우저로 열면 됩니다.
또는 이 폴더에서 아래 명령을 실행한 뒤 http://localhost:8000 에 접속합니다.

```bash
python -m http.server
```

## 배포

GitHub Pages — `main` 브랜치의 루트 폴더를 그대로 배포합니다.

## 업데이트 기록

- **2026-11-24 1차 완성본** — 프로젝트 상세(개요 · 목표 · 주요 기능 · 데이터), 대시보드 화면 4장, 코드 예시, 관심 프로젝트 추가
- **2026-11-18 초안** — 개발자형 템플릿 대신 부동산 · 데이터형 디자인으로 변경

## 사용한 것

- 글꼴: [Pretendard](https://github.com/orioncactus/pretendard) (SIL Open Font License)
- 화면 이미지: 직접 만든 [터무늬 부동산 인텔리전스](https://tjtjgml3377-cmd.github.io/) 대시보드

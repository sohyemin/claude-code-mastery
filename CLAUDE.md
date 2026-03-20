# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 프로젝트 개요

이 저장소는 Claude Code를 학습하고 실험하기 위한 **교육용 워크스페이스**입니다. 실제 애플리케이션 코드보다는 Claude Code 설정과 출력 스타일 구성에 중점을 두고 있습니다.

## Claude Code 설정 구조

```
.claude/
├── settings.json          # 프로젝트 수준 설정 (권한, 출력 스타일)
├── settings.local.json    # 로컬 전용 설정 (gitignore 권장)
└── output-styles/
    └── beginner.md        # 초보자 친화적 출력 스타일 정의
```

### 출력 스타일

- **Beginner Friendly** 스타일이 기본으로 적용됨 (`settings.local.json`)
- 코드를 한 줄씩 설명하고, 한글 주석 사용, 쉬운 용어 사용이 원칙

### 권한 설정

- `settings.json`: `Bash` 명령 허용
- `settings.local.json`: PowerShell 스크립트 및 상태표시줄 관련 명령 허용

## 파일 현황

- `index.html` / `main.js` — 현재 비어 있는 플레이스홀더 파일 (실습용으로 사용 예정)

## 개발 환경

- 빌드 시스템, 패키지 매니저, 테스트 프레임워크 없음
- 순수 HTML/JS 실험을 위한 공간으로 사용
- 플랫폼: Windows 11, Shell: bash

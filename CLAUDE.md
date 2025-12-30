# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

로컬 브라우저에서 실행되는 쇼핑 리스트 웹 앱. 순수 HTML/CSS/JavaScript로 구현되어 별도 빌드 과정 없이 `index.html`을 브라우저에서 직접 열어 사용.

## Build & Development Commands

```bash
# 실행 (Windows)
start index.html

# 실행 (macOS)
open index.html

# 실행 (Linux)
xdg-open index.html
```

빌드나 의존성 설치 불필요.

## Architecture

- **단일 파일 구조**: `index.html`에 HTML, CSS, JavaScript 모두 포함
- **데이터 저장**: `localStorage`를 사용하여 브라우저에 데이터 영구 저장
- **기능**: 아이템 추가, 삭제, 체크(완료 표시)

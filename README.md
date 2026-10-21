# 나의 기록

Jekyll과 Minima 테마를 사용하는 GitHub Pages 블로그입니다.

블로그 주소: https://kyk9462429kyk.github.io

## 글 작성

`_posts` 폴더에 `YYYY-MM-DD-영문-제목.md` 파일을 추가합니다.

```markdown
---
layout: post
title: "새 글 제목"
date: 2026-10-22 09:00:00 +0900
categories: [기록]
---

여기부터 Markdown으로 본문을 작성합니다.
```

작성한 파일을 커밋하고 GitHub에 push하면 Pages에서 다시 빌드합니다.
미래 날짜의 글은 해당 날짜가 지난 후 다시 빌드되어야 표시됩니다.

## 설정

- `_config.yml`: 블로그 제목, 설명, 주소
- `about.md`: 블로그 소개
- `_posts/`: 게시글

## 로컬 미리보기

Ruby와 Bundler가 설치된 환경에서 실행합니다.

```sh
bundle install
bundle exec jekyll serve
```

http://127.0.0.1:4000 에서 확인할 수 있습니다.

## GitHub Pages

저장소의 Settings → Pages에서 `Deploy from a branch`, `main`, `/ (root)`를 선택합니다.
저장소에 올리는 파일과 게시글은 공개됩니다.

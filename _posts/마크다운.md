---
layout: post
title: MarkDown
tags: markdown
date: 2022-12-06 18:42 +0800
---

마크다운(Markdown)이란 웹 상에서 글을 작성하는 사람들을 위한 글쓰기 도구
마크다운을 통해 HTML 형식으로 글을 변환할 수 있다.
단, 간단하기 때문에 모든 HTML을 지원하지는 않는다. 
마크다운은 쉽게 글을 쓰고 읽게 해 주는 서식(포맷)이다.

[Move Text](#header-헤더)
[Move Text](#horizontal-rules-수평선)
[Move Text](#line-breaks-줄바꿈)
[Move Text](#emphasis-강조)
[Move Text](#blockquotes-인용)
[Move Text](#list-목록)
[Move Text](#backslash-escapes)
[Move Text](#image-이미지)
[Move Text](#links-링크)

# 마크다운 (MarkDown) 문법
## Header 헤더
- /#으로 시작하는 텍스트
- /#은 하나부터 여섯개까지 가능
- 이때, H1은 ===로 H2는 ---로 만들기 가능

# h1 헤더
## h2 헤더
### h3 헤더
#### h4 헤더
##### h5 헤더
###### h6 헤더

h1 헤더
===
h2 헤더
---

## Horizontal Rules 수평선
- /- 또는 * 또는 _을 3개 이상
- 단, -을 사용하는 경우에는 header로 인식할 ㅅ 있기 때문에 전 라인은 비워놔야 가능 

## Line Breaks 줄바꿈
- <br>을 사용하여 줄바꿈 가능

## Emphasis 강조
- *기울여쓰기(italic)* : * 또는 _로 감싼 텍스트
- **두껍게 쓰기(bold)** : ** 또는 __로 감싼 텍스트
- ~~취소선~~ : ~~로 감싼 텍스트
- 이때, 기울여쓰기와 두껍게쓰기를 동시에 사용 가능

## Blockquotes 인용
- />으로 시작하는 텍스트
- />는 3개까지 가능
- 인용구 안에 다른 문법들도 사용 가능

## List 목록
### 순서가 없는 리스트
- *, +, -를 이용한 순서가 없는 목록
- 들여쓰기를 하는 경우 모양이 바뀜
### 순서가 있는 리스트
- 숫자 입력시 순서가 있는 목록
- 들여쓰기를 하는 경우 모양이 바뀜
- 리스트 안에 추가 리스트를 사용할 경우 들여쓰기와 숫자 1번 부터 다시 적용
### 혼합 리스트

## Backslash Escapes 
- 특수문자를 표현할 떄, 표시할 문자 앞에 \를 넣고 특수문자 입력

## image 이미지
- 앞에 !가 붙음
- 인라인 이미지 ![alt text](/test.png)
- 링크 이미지 ![alt text](image_URL)
- 이미지 사이즈 변경 <img width="OOOpx" height="OOOpx"></img> 수정

## Links 링크

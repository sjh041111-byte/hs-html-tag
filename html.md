HTML 주요 태그 정리 Guide

HTML 문서 작성에 자주 사용되는 주요 태그들을 기능별로 정리한 요약 문서입니다.

1. 기본 및 문서 구조 (Structure)

태그

설명

<!DOCTYPE html>

HTML5 문서임을 정의하는 선언문

<html>

HTML 문서의 최상위(Root) 엘리먼트

<head>

문서의 메타데이터(제목, 스타일, 스크립트 등)를 포함

<title>

웹 페이지의 제목을 설정 (브라우저 탭에 표시)

<body>

실제 브라우저 화면에 표시되는 본문 영역

<meta>

문자셋(UTF-8), 검색엔진 키워드, 뷰포트 설정 등 메타데이터 정의

<link>

외부 파일(CSS, 파비콘 등)을 연결

<script>

JavaScript 코드를 작성하거나 외부 JS 파일을 연결

2. 시맨틱 구조 태그 (Semantic Layout)

태그

설명

<header>

상단 헤더 영역 (로고, 머리말, 검색 등)

<nav>

네비게이션 링크 메뉴 영역

<main>

문서의 핵심 메인 콘텐츠 영역 (문서 내 유일)

<article>

독립적으로 분리하여 재사용 가능한 콘텐츠 (블로그 글, 뉴스 등)

<section>

주제별 콘텐츠 영역 단락 구분

<aside>

주요 내용과 연관된 사이드바/부가 정보 영역

<footer>

하단 푸터 영역 (저작권, 연락처, 푸터 메뉴 등)

3. 텍스트 및 서식 (Text Formatting)

태그

설명

<h1> ~ <h6>

제목(Heading)을 나타냄 (<h1>이 가장 큼)

<p>

문단(Paragraph) 구분

<span>

인라인 텍스트 스타일링용 영역 구획

<div>

블록 단위 영역 구획

<br>

줄바꿈 (Line break)

<hr>

수평선 (주제 전환/구분)

<strong>

중요한 텍스트 강조 (굵게 표시)

<em>

텍스트 강조 (기울임꼴)

<a>

다른 페이지나 URL로 이동하는 하이퍼링크 생성

4. 목록 (Lists)

태그

설명

<ul>

순서가 없는 목록 (Bullet points)

<ol>

순서가 있는 목록 (Numbered list)

<li>

목록의 각 항목 (Item)

5. 멀티미디어 (Media)

태그

설명

<img>

이미지 삽입 (src, alt 속성 사용)

<audio>

오디오 재생

<video>

비디오 재생

<iframe>

다른 HTML 페이지를 내장 (유튜브 퍼가기 등)

6. 표 (Table)

태그

설명

<table>

표 전체를 감싸는 태그

<thead>

표의 헤더 행 그룹

<tbody>

표의 본문 데이터 행 그룹

<tr>

표의 행 (Row)

<th>

표의 헤더 셀 (기본 굵은 글씨, 가운데 정렬)

<td>

표의 일반 데이터 셀

7. 폼 및 입력 (Forms & Inputs)

태그

설명

<form>

사용자 입력을 서버로 전송하기 위한 양식 영역

<input>

다양한 타입의 입력 필드 (text, password, checkbox, radio 등)

<textarea>

여러 줄 입력이 가능한 텍스트 상자

<button>

클릭 가능한 버튼

<select>

드롭다운 선택 메뉴

<option>

드롭다운 내 각 항목

<label>

입력 요소(input)에 대한 설명 이름 표기

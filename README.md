## HTML 이란 무엇인가? ##

* `콘텐츠의 구조를 정의 하는 마크업 언어이다.`

## HTML 요소 분석 ##

1.**여는 태그 (Opening tag)**<br>
2.**닫는 태그  (Closing tag)**<br>
3.**콘텐츠 (Content)**<br>
4.**요소 (Element)**

## 요소 중첩 ##

* 쉽게 말해서 `<p>My cat is <strong>very</strong> grumpy.</p>` 라고 써야 되고 <br>
   `<p>My cat is <strong>very grumpy.</p></strong>` 라고 쓰면 틀리게 됨 

## 빈요소 ##

* `내용을 갖지 않는 요소 닫는 태그가 없음`

## HTML 문서 해부 ##

* `<!DOCTYPE html>` 반드시 적어야 하는 필수 서약 <br>
* `<html></html>` 페이지 전체를 감싸며, 루트 요소라고도 불림 <br>
* `<head></head>` 검색 결과에 표시되길 원하는 페이지 설명, 콘텐츠를 꾸미기 위한 CSS, 문자 집합 선언등이 역할이 되는 요소<br>
* `<meta charset="utf-8">`  사용할 수 있는 어떠한 문자 콘텐츠도 다룰 수 있게 만드는 요소<br>
* `<title></title>` 페이지의 제목을 나타내는 요소<br>
* `<body></body` 웹 사용자들에게 보여주길 원하는 모든 컨텐츠를 쓸수 있는 요소

# 문자를 나타 내는 요소들 #

## 제목을 나타 내는 요소 ##

* `크기순으로 <h1>부터 <h6> 까지 있다.`

## 문단 요소 ##

* `<p></p> 로 사용 가능하며 문단을 추가하는 요소이다.`

## 목록 요소 ##

* `순서 없는 목록`은  `<ul></ul>` 로 둘러 쌓아 만들 수 있다.<br>
* `순서 있는 목록`은  `<ol></ol>` 로 둘러 쌓아 만들 수 있다.

## 링크 요소 ##

* `<a></a>`로 감싸고 앞에 앞 태그에 `href 속성`을 넣고 =주소를 입력해 링크를 추가 할 수 있다.<br>

### 예시 <br>

` <a href="https://www.mozilla.org/en-US/about/manifesto/">Mozilla Manifesto</a> ` 와 같은 방식으로 쓴다.



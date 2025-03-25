<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>3월 20일</title>
</head>
<body>
<h3>링크 만들기</h3>
<hr>
포털 사이트
<ul>
<li><a href="http://www.naver.com" target="_blank">네이버</a></li> <!--새창-->
<li><a href="http://www.google.com" target="_parent">구글</a></li>
<li><a href="https://smc.sen.hs.kr/" target="_self">세명컴고</a></li> <!--현재창-->
<li><a href="http://www.daum.net" target="_top">다음</a></li>
</ul>
<a id="ex">구글 바로가기</a><br>
<a href="http://www.google.com" target="_blank"><img src="구글.png" width="100px"></a>
<hr>
<h3>비디오 태그</h3>
<video src="beach.mp4" width="300" controls autoplay></video>
<video src="school song.mp4" width="500" controls loop></video>
<hr>
<h3>오디오 태그</h3>
<audio src="song.mp3" controls loop></audio>
<a href="#ex">구글 바로가기</a><!--앵커설정(html 페이지 내의 특정 위치)-->
<hr>
<h3>map 태그</h3>
<img src="map.jpg" width="300" usemap="#map">
<map name="map">
<area shape="circle" coords="80,280,30" href="http://www.jeju.go.kr"
target="_blank" title="제주도">
<area shape="rect" coords="120,70,30,30"
href="http://www.seoul.go.kr" target="_blank" title="서울시">
</map>
</body>
</html>

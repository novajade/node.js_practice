REST API를 사용하면서 몰랐던 Node.js
?	What is Node.js?
?	자바스크립트로 서버 프로그래밍을 하는 Platform. (some people call it Framework & Engine) JAVASCRIPT BASE
?	Platform to allows run JS on PC or Server.
?	Can Read, Delete, Update files in REALLY FAST way (V8 Engine & non-blocking I/O)
?	Node.JS is written in C++…. WHAT? So V8 is embedded in Node.JS, which written in C++. So JS language through Node.js and go to Machine code which makes it faster.
?	Event-driven 식 처리방식과 non-blocking I/O 모델임
?	Non-Blocking I/O란?
?	싱글 스레드
?	10,000 개의 Concurrent (동시에 발생) 커넥션 지원
?	이벤트 루프
 
?	Node.js로 할 수 있는 것은?
?	REST APIs & 백엔드 Applications
?	Real-Time Services (chat, games…)
?	Blogs, Social Applications
?	Non CPU-intensive한 것들

Node can tell where the file is. 
Found out NodeJS kinda similar with python variable concept..

MODULE
?	module.exports -> js 파일에 있는 function을 다른 파일에서 사용할 수 있도록? 
그 뒤 사용하고자 하는 파일에서 var로 function을 require 하면 사용가능. 오브젝트 생성과 비슷한 개념. 대신 추출 가능한 오브젝트를 설정할 수 있고 미리 파일 안에서 결정지어서 타 파일에서 접근 혼선이 없도록 할 수 있는 것 같음

# 자바 스크립트 기초 (k디지털역량)
## Loop
* for 반복문 : `for(초기문;조건문;증감){반복할 코드}`
* `<script> for(var i = 0;i<=10; i += 2){document.write(i+'br>')} </script>`
* while 반복문 : `while(조건문){//반복 증감}`
* `<script> var i= 0; while(i<=10){document.write(i+'<br>'); i+= 2;} </script>`
* do while : `초기문; do{//반복 //증감}  while(조건);`
* `var i = 0; do{document.write(i+'<br>'); i+2= 2;} while(i<=10);`
* forEach 반복문 : 배열의 원소에서만 사용 가능
* `var arr = ['a', 'b', 'c', 'd'];`
*  `arr.forEach(function(item,index,all))`
* ` {document.write(item+'는 전체배열'+all+'에서'+index);}`
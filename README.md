## jQuery란?
- jQuery는 자바스크립트 라이브러리
  브라우저 간 호환성을 제공하며 자바스크립트를 쉽게 사용할 수 있게 도와줌
- HTML, CSS, DOM 조작과 이벤트 처리, 애니메이션 등을 간단한 코드로 구현 가능 <br/>

------------
- HTML/DOM 조작
요소와 변경이 쉬움
```
$("#myDiv").text("Hello, jQuery!"); // 특정 ID를 가진 div의 텍스트 변경
```
- 이벤트 처리
클릭, 마우스 오버 등 
```
$("#myButton").click(function() {
    alert("Button clicked!");
});
```
- 애니메이션 효과
간단한 애니메이션 효과
```
$("#myDiv").fadeOut(); // 특정 요소를 서서히 사라지게 함
```

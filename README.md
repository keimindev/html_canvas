### 1. Canvas API 
HTML과 javascript을 사용하여 그래픽을 그릴 수 있게 도와준다. </br>
HTML에서 `<canvas>` 태그를 사용해서 작성하고 자바스크립트 엘리먼트 인터페이스를 이용해서 그린다. </br>
비트맵 데이터의 픽셀 하나하나를 조작할 수 있고 그래픽 처리 성능이 상대적으로 좋다. </br>
canvas는 비트맵, SVG는 벡터이미지다. </br>
canvas는 비트맵이기 때문에 픽셀 개수가 많아질 수록 용량이 커진다. <br/>
</br>
### 2. 브라우저가 canvas를 지원하는지 확인하기 
Modernizer 라이브러리를 사용해서 캔버스 지원 여부 확인 <br/>
</br>
### 3. 캔버스 사이즈 설정하기
canvas의 사이즈를 CSS에서 조절하는 것과 html속성 값을 주는 것은 의미가 다르다.<br/>
같은 좌표를 찍었지만 css에서 사이즈를 맞춰서 나오는게 달라진다. <br/>
고해상도를 위해서 html속성을 배로 만들고 css에서 조절한다. 이게 좋은 것만은 아닌게
그만큼 연산할 내용이 는다는 소리니 적절하게 잘 써야한다.<br/>
<br/>
### 4. 캔버스 사용하기
- html `<canvas>` element를 작성한다.<br/>
- 자바스크립트에서 `<canvas>` element를 가져온다.<br/>
- 자바스크립트에서 `getContext()`메소드를 호출해서 context객체를 가져온다.<br/>
캔버스는 기본적으로 색상을 갖고 있지 않기 때문에 css로 배경을 칠해 놓고 작업하는 것이 편하다.<br/># html_canvas

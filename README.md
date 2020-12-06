# Create a simple chrome app.

VanillaJS 를 기반으로 Todo 기능이 있는 크롬앱을 구현했습니다.

### screen

<img src="https://user-images.githubusercontent.com/59306143/101284770-06905600-3825-11eb-86de-36590321f1ec.gif" alt="제목-없음-3" width="600" height="400"/>

### explanation

- background image 는 animation 을 이용하여 좀 더 자연스럽게 나타나도록 했습니다.

- 시계는 Date 객체를 생성하여 시, 분, 초 를 나타냈습니다.

- setInterval() 을 이용하여 1000ms 로 매초마다 갱신되게 했습니다.

- openweathermap.org 에서 API 를 이용하여 위치정보 동의 뒤에 지역의 이름과 온도가 나오게 했습니다.

- API units 는 온도를 섭씨로 나타내기 위해 metric 을 사용했습니다.

- 페이지를 꺼도 todo 목록이 저장되게 하기 위해 sessionStorage 대신 localStorage를 사용했습니다.

- ❌ 를 클릭하면 목록이 삭제 되도록, addEventListener() 를 사용하여 (click 이벤트에 대한 리스너)deleteToDo 가 실행되게 했습니다.

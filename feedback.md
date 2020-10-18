# 1차 클론코딩 피드백

* 네브바는 ul보다 nav 
* img 태그 내 widht height는 쓰는 경우도 있는데 지양
* 만약 중요한 내용에 bold체다 하면 b 대신 strong태그도 고려
* html태그도 같이 포함해서 초기화 코드 + * {box-sizing: border-box}
* nav바 같은경우 top position에 고정되어있으므로 position 속성을 이용해서 스크롤을 내려도 고정시키는 연습
* nav같은 요소에 vh를 주면 안좋음, vw를 주면 기기에 따라서 네브는 일반적으로 다 채우니까 상관이 없는데, vh는 기기마다 너무 차이가 커서
nav가 본의아니게 정말 두꺼워 질수 있음==>height를 고정
* tag내에서 margin으로 간격을 띄우는게 여러번 발생하면 차라리 padding
* nav내부에 요소를 li로 주는 경우가 잇는데 그러면 list-style을 제거해줘야하므로 짜피 나중에 link로 이동할 버튼이므로 a tag로 사용해버리자
* flex-direction : row니까 굳이 디폴트 들은 생략해줘도 댈듯
* 특정 방향만 먹일때는 PADDING-TOP 이런거 쓰면 한눈에 더 잘들어옴

* container의 min-height는 정하는게 좋음 vh로 정하면 스크롤이나 히든될수 있으니까 min-height를 정하고(만약 div나 페이지내 요소가 부족할때
나중에 footer가 올라올수도 있음 , 아래 공백이 생긴다던가,) 
* vertical-align 블로그나 외국 좀 된 자료에서 쓰라는데 잘 안먹음
* 부모 태그 높이 지정안하면 height무쓸모


* asolute로 가운데 정렬하는 방법 : left:50% ; top:50%; margin-left:-(widtn의 반)px margin-top: -(height의 반)px
* circle display flex justify, align==> circle1 => display:flex로 두고 justify 이런식으로 <c><c1><c2><c3></c3></c2></c1><c>

## 추가로 공부할 내용

* 미디어 쿼리


# 내가 배운내용 : margin-left : auto옵션
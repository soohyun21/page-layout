# page-layout
page layout을 공부하기 위한 project 입니다

첫 번째 section 제작 시 media query와 grid system 때문에 생각보다 시간이 오래 걸렸습니다. 
html 작성시에도 처음에 class 명을 일관성있게 만들어 놓아야 한다는 생각에 오래 걸린 것 같습니다.

두 번째 section은 첫 번째 section보다 간단해 보였지만 크기가 768px 이상으로 넘어갔을 때 제목과 설명 두 개를 나란히 배열시키는 것에서 헤맸습니다.
처음에 flex를 사용해서 만들었었는데 아무리 생각해도 이건 아닌 것 같아서 찾아보니 grid를 이용하는 것이었습니다.
grid 활용법에 대해 더 정확히 알게된 것 같아 좋았습니다.

세 번째 section은 재활용할 수 있는 css를 만드느라 오래 걸렸습니다. css를 만드는 도중에 뭔가 너무 복잡해 보여서 강사님의 코드와 비교해보니 밑에 section에서도 재활용 가능한
방식으로 코드를 작성했다는 것을 알 수 있었습니다. 이걸 만드느라 시간이 더 걸려서 후회하긴 했지만 유용한 방법이긴 한 것 같습니다. 앞으로 만들기 전에 전체를 훑어보고 패턴을 찾는 습관을
들여야 할 것 같습니다. 그리고 bootstrap에서 row가 display flex이기 때문에 'row justify-content-center'를 지원한다는 것도 처음 알아서 흥미로웠습니다.

네 번쩨 section은 전반적으로 무난했고 768px 이상일때만 이미지가 나타다도록 하는 과정이 흥미로웠습니다. 몇 주 전에 display:none과 visibility:hidden의 차이점에 대해 공부했는데 768px 이하의
화면에서는 이미지가 보이지 않고 자리도 차지하지 않아야 하기 때문에 display:none을 사용했습니다. 

# ResponsiveWebStudy

display : flex | inline-flex
    flex 박스를 블록 수준의 플렉서블 박스로 작동
    inline-flex 박스를 인라인 수준의 플렉서블 박스로 작동

flex-direction : row | row-reverse | column | column-reverse
    row 박스를 왼쪽에서 오른쪽으로 배치
    row-reverse 박스를 가로로 배치하되 역방향 배치
    column 박스를 위에서 아래로 배치
    column-reverse 박스를 세로로 배치하되 역방향 배치

flex-wrap : nowrap | wrap | wrap-reverse
    nowrap 박스를 한 줄로 배치
    wrap 박스를 여러 줄로 배치
    wrap-reverse 박스를 여러 줄로 배치하되 역방향 배치

flex-flow : [flex-direction] [flex-wrap] | row nowrap

justify-content : flex-start | flex-end | center | space-between | space-around
    flex-start 자식 박스를 부모 박스의 주축의 시작점으로 배치
    flex-end 자식 박스를 부모 박스 주축의 끝점으로 배치
    center 자식 박스를 부모 박스의 중앙으로 배치
    space-between 박스를 동일한 간격으로 정렬 (플렉서블 박스에 빈 공간이 있을 때 사용)
    space-around 양쪽 끝에도 공간을 둔 채 자동 정렬 (플렉서블 박스에 빈 공간이 있을 때 사용)

align-items : stretch | flex-start | flex-end | center | baseline
    stretch 박스를 확장해서 배치
    flex-start 박스를 교차축의 시작점에 배치
    flex-end 박스를 교차축의 끝점에 배치
    center 박스를 교차축의 중앙에 배치
    baseline 자식 박스들을 교차축의 시작점에 배치되는 자식 박스의 글자 베이스라인에 맞춰 배치

align-self : auto | stretch | flex-start | flex-end | center | baseline
    auto 플렉서블 박스의 align-items 속성값을 상속받음

align-content : stretch | flex-start | flex-end | center | space-between | space-around

order : 0 | 정숫값  (배치 순서 바꿈)

flex-grow  플렉서블 박스에 여백이 있을 때 플렉스 아이템의 크기를 늘일 수 있는 속성
flex-shrink 플렉서블 박스 안의 플렉스 아이템의 크기가 넘칠 경우 크기를 줄일 수 있는 속성
flex-basis 플렉스 아이템의 기본 크기를 설정하기 위한 속성

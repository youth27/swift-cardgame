- 미션 요구사항 진행용 README는 [여기](https://github.com/youth27/swift-cardgame/blob/card-step3/README2.md)에 있습니다.
- 미션 진행 단계별 상세한 피드백은 [Wiki](https://github.com/youth27/swift-cardgame/wiki)에 있습니다.
***
## 미션 진행 과정 - Daily
- 2018.01.09 step1 요구사항 구현 : Card, CardDeck(enum타입만 가지고있음), OutputView객체 생성
- 2018.01.10 step1 요구사항 구현 : Card의 속성,메서드 변경, OutputView의 showResult()파라미터 변경
- 2018.01.11 step1 피드백에 따른 수정 : Card 객체 NSObject 상속, Card객체의 init() 호출 시 유추 가능한 파라미터 타입은 케이스 명만 쓰는 것으로 변경
- 2018.01.11 step2 요구사항 구현 : CardDeck에 기본 메뉴 기능구현, InputView추가, main에 흐름제어구문 추가

- 2018.01.12 step2 피드백에 따른 수정 : OutputView의 showResult(), EnumCollection추가, GameMenu enum 추가
- 2018.01.15 step3 요구사항 구현 : CardStack 구조체 추가, main.swift에 함수 추가, 코딩스타일 가이드라인을 작성-[README2](https://github.com/youth27/swift-cardgame/blob/card-step3/README2.md)
- 2018.01.16 step4 요구사항 구현 : GameInputView구조체 추가, Player, Dealer클래스 구현과 상속, main에 흐름제어구문 추가
- 2018.01.17 step4 피드백에 따른 수정 : OutputView의 showResult()인자에 description제거, GameController추가, main에 play(), run()함수 추가
- 2018.01.18 step4 피드백에 따른 수정 : GameController로직 확장, main로직 축소, ResultData구조체 추가, Controller의 init() throws로 수정
- 2018.01.22 ~ 25 step5 요구사항 구현 : 포커게임 표준 족보에 따른 Hands서열대로 점수 계산로직 설계 & 개선. CardTable객체 추가, ScoreChecker객체 추가, Hands구조체 생성, UnitTest코드 추가

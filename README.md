# kotlin-racingcar

## 기능 요구 사항
초간단 자동차 경주 게임을 구현한다.

- 주어진 횟수 동안 n대의 자동차는 전진 또는 멈출 수 있다.
    - [x] 자동차 대수를 입력받는 기능
        - [x] 숫자만 입력할 수 있어야 한다.
    - [x] 자동차를 생성하는 기능
- 사용자는 몇 대의 자동차로 몇 번의 이동을 할 것인지를 입력할 수 있어야 한다.
    - [x] 시도할 횟수를 입력받는 기능
        - [x] 숫자만 입력할 수 있어야 한다.
- 전진하는 조건은 0에서 9 사이에서 무작위 값을 구한 후 무작위 값이 4 이상일 경우이다.
    - [x] 랜덤 숫자를 구하는 기능
    - [x] 자동차를 전진하는 기능
- 자동차의 상태를 화면에 출력한다. 어느 시점에 출력할 것인지에 대한 제약은 없다.
    - [x] 자동차의 상태를 출력하는 기능
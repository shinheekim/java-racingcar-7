# java-racingcar-precourse

### 기능명세서
초간단 자동차 경주 게임을 구현한다.

1. 경주할 자동차 이름을 입력받는다. (쉼표를 기준으로 구분, 5자 이하만 가능)
    `pobi,woni,jun`
2. 시도할 횟수 입력받는다.
    `5`
3. 전진 조건은 0~9 사이 무작위 수를 구한 후 4 이상일 시 전진, 아니면 멈춤
4. 전진하는 자동차를 출력할 때 자동차 이름 출력
   ```
   pobi : --
   woni : ----
   jun : ---
    ```
5. 제일 많이 전진한 자동차가 우승. 여러명일 수 있음. (쉼표 구분)
   `최종 우승자 : pobi, jun`

잘못된 값을 입력할 경우 IllegalArgumentException을 발생
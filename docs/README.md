## ⚾ 숫자 야구 진행 방식

플레이어가 `서로 다른 3가지 숫자`를 입력하여 컴퓨터가 선택한 랜덤 숫자를 맞추는 게임이며,

숫자의 일치 정도를 **스트라이크, 볼, 낫싱**의 문구로 보여준다.

**3스트라이크**가 되면 `1`(재시작) 또는 `2`(종료)를 입력하여 게임을 재시작할지 종료할지 정할 수 있다.

&nbsp;

## ✔ 기능 목록

### `play()`

숫자 야구 게임을 시작을 알리고 게임이 끝나면 **1(재시작) 또는 2(종료)를 입력받아 게임의 진행 여부를 결정**한다.

### `getComputerNumbers()`

1-9 까지의 숫자 중 **서로 다른 3개의 숫자를 랜덤으로 선택하고 반환**한다.

### `getPlayerNumbers()`

3스트라이크가 될 때까지 **플레이어에게 숫자를 입력** 받는다.

### `checkValidation()`

플레이어가 입력한 값이 서로 다른 3자리의 숫자가 아닌 경우 throw 문을 사용하여 **예외를 발생**시킨다.

### `calculateScore()`

컴퓨터가 선택한 숫자와 플레이어가 입력한 숫자를 비교하고 결과에 따라 **볼과 스트라이크의 개수를 반환**한다.

### `printScore()`

야구 게임 결과를 **스트라이크, 볼, 낫싱 중 해당하는 문구로 출력**한다.


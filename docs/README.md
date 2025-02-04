# 우아한 프리코스 1주차 미션 - 숫자 야구 게임

---
우아한 테크코스 6시 백엔드 프리코스 1주차 미션 입니다.<br>
숫자 야구 게임을 구현합니다.

---
## 기능목록

- 게임 생성
    - 야구 게임 객체를 생성하며 컴퓨터의 수(답)을 생성하는 메소드를 호출하여 초기화 합니다.

- 컴퓨터의 수(답) 생성
    - camp.nextstep.edu.missionutils 라이브러리를 사용하여 답을 생성하여 반환합니다.
  - 컴퓨터는 1부터 9까지의 숫자 중 3가지의 숫자를 랜덤으로 생성한다,
- 게임 실행
    - 생성된 게임 객체를 실행하며 사용자의 답을 입력받고 게임을 진행합니다.
    - "숫자 야구 게임을 시작합니다."라는 문구를 출력한다.
    - "숫자를 입력해주세요 :"라는 문구를 출력 후 사용자에게 답을 입력받는다.
- 답 검사
    - 사용자가 입력한 답과 컴퓨터의 답을 비교하여 적절한 문구를 출력합니다.
      - 정답이 없을시 낫싱
      - 같은 수가 같은 자리에 있을 시 스트라이크
      - 같은 수가 다른 자리에 있을 시 볼
    - 올바르지 않는 답을 입력할 시 IllegalArgumentException 에러를 발생시키고 프로그램을 종료시킨다.
    - 정답을 맞출 시 게임을 종료하고 게임 재시작 분기를 처리합니다.
- 재시작
    - 사용자의 입력을 받아 게임의 답을 초기화 한 후 게임을 재시작 합니다.
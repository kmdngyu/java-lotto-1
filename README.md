# java-lotto
로또 미션 진행을 위한 저장소
---
####기능 요구 사항
- 구입 금액 입력
- 로또 수 입력
- 수동으로 구매할 번호 입력
    - 6개 숫자
    - ','로 구분
    -return으로 다음 수동 입력
- 번호 출력
- 지난 주 당첨 번호 입력
- 보너스 볼 입력
- 당첨 통계 출력
- 총 수익률 계산

####to do list
- [x] 로또 번호 객체
    - [x] 1 이상 45이하
- [x] 로또 번호 모음 객체
    - [x] 6개 번호여야함
    - [x] 중복 없어야함
- [x] 로또 객체
    - [x] 하나의 로또 번호 모음
    - [x] 수동 생성
    - [x] 자동 생성(랜덤)
- [x] 자판기 입력
    - [x] 금액 입력
        - [x] 1000 이하면 다시
        - [x] 거스름돈 출력
    - [x] 수동 갯수 입력
        - [x] 구매 숫자보다 적게
    - [x] 수동 번호 입력
        - [x] ,로 구분 
        - [x] 6개 숫자
- [x] 자판기 로직
    - [x] 수동 로또 수 저장
    - [x] 수동 로또 번호 저장
- [x] 게임
    - [x] 당첨 정보 저장
    - [x] 당첨 정보 입력
    - [x] 당첨 정보 출력
    
####refactor
- [x] 메인 메서드 스태틱 제거
    - [x] 로직 간결화
    - [x] 에러 런타임 / 정규표현식 구분
- [x] 스트림 수
- [x] 자동 수동
    - [x] 클래스 따로 생성
    - [x] 구매 정보는 수동 갯수만 가지도록 수정
    - [x] 수동 번호 일급 컬렉션
    - [x] 관련 테스트 생성
- [x] 당첨 로또 상속 분리

Web & ui 
---
- lotto db연결
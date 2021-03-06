# 2장. 비트코인의 작동원리

- 비트코인 시스템 내의 진행되는 거래 과정을 소개 (합의 - 신뢰 - 승인 - 블록체인에 기록)
- 하나의 거래를 추적하여 비트코인 각 부분들과의 상호작용을 알아보기

## 비트코인 거래

- 한마디로 "소유주가 타인에게 전송하는 것을 승인한다"고 네트워크에 이야기 하는 것과 같다.
- 복식부기 장부에 나오는 대변(credit)과 차변(debit)으로 구성되어 있다고 한다.

> 복식부기 장부: 기업의 자산과 부채의 증감 및 변화 과정을 대변과 차변으로 구분하여 기록
> 차변: 하나 이상의 '입력값' 즉 계좌에서 빠져나가는 것
> 대변: 하나 이상의 '출력값' 즉 계좌로 들어오는 것

<br />

하나의 거래에서 나온 출력값은 새로운 거래의 입력값으로 사용될 수 있다. (소유권 사슬)

![image](https://user-images.githubusercontent.com/20738369/114586953-25659400-9cc0-11eb-95e2-8d9d141f2a4f.png)


## 채굴

- 비트코인 시스템은 전체 거래내용을 10분 단위로 모아 장부에 기록
- 거래내용은 암호화 되어있기 때문에 누군가 암호를 풀어 장부에 기록해야 함
- 블록을 유효하게 만드는 솔루션을 채굴자가 찾게 되면 블록에 숨겨져 있는 상금을 얻는다

![image](https://user-images.githubusercontent.com/20738369/115130221-af975a80-a028-11eb-9ca3-543b9e4edb35.png)

- 거래가 거듭 될 수록 거래를 철회하기 힘들어짐 -> 네트워크 상 신뢰도 증가
- height가 높아질수록 각 블록과 체인의 계산 난이도도 증가


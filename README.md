# Algorithm and Coding Study

도서명 : 알고리즘 문제 해결 전략

<br/>

## 프로그래밍 문제 해결 과정

1. #### 문제를 읽고 이해하기
   - 문제 설명을 공격적으로 읽으며 문제가 원하는 바를 완전히 이해하는 과정이 반드시 필요

2. #### 문제를 익숙한 용어로 재정의하기 + 추상화
   - 자신이 다루기 쉬운 개념을 이용하여 문제를 자신의 언어로 풀어 쓰는 단계
   - 본질만 남겨두고 축약하여 다루기 쉽게 표현 -> 추상화
   - 어떤 부분을 추상화할 것인지를 선택하는 작업과 문제를 재정의하는 방법들에 대한 고찰은 좋은 프로그래머가 되기 위해 필수적인 과정
  
3. #### 어떻게 해결할지 계획 세우기
   - 문제를 어떤 방식으로 해결할지 결정하고, 사용할 알고리즘과 자료구조를 선택
   - 문제 해결에서 가장 중요한 단계
  
4. #### 계획 검증하기
   - 설계한 알고리즘이 모든 경우에 요구 조건을 정확히 수행하는지 증명
   - 수행에 걸리는 시간과 사용하는 메모리가 문제의 제한 내에 들어가는지 확인
  
5. #### 계획 수행하기(프로그램으로 구현하기)
   - 프로그램을 작성하는 단계
  
6. #### 어떻게 풀었는지 돌아보고, 개선할 방법이 있는지 찾아보기(회고하기)
   - 당장 직접적인 영향은 없지만 장기적으로 가장 큰 영향을 미치는 단계
   - 1.문제를 풀 때마다 코드와 함께 자신의 경험을 기록으로 남기기(간단한 해법, 접근 방식, 결정적이었던 깨달음 등)
   - 한 번에 맞추지 못한 경우 오답 원인도 기록
   - 2.같은 문제를 해결한 다른 사람의 코드를 보기
   - 다른 사람의 의견이나 답안을 통해 자극을 얻다보면 더 효율적으로 공부할 수 있음(그룹 스터디, 인터넷)

7. #### 문제를 풀지 못했을 경우
   - 한 문제에 너무 매달려 있는 것도 좋지 않음
   - 일정 시간이 지나도록 고민해도 답을 찾지 못할 때는 다름 사람의 소스 코드나 풀이를 참조하는 것도 좋은 자세
   
   - 자신이 왜 이 풀이를 떠올리지 못했는지 돌아보기
<br/>

## 문제 해결 전략

ㅇ 문제 해결 전략
- 직관과 체계적인 접근 : 문제와 답의 구조에 대한 직관의 중요성
- 체계적인 접근을 위한 질문 : 문제를 해결할 때 유용한 질문

1. #### 비슷한 문제를 풀어본 적이 있었는지?
   - 문제의 목적을 보고 적절한 접근 방법을 선택하기 위해서는 어떤 문제가 최적화 문제인지, 경우의 수를 구하는 문제인지, 검색 문제인지 등을 분류하는 방법을 익히고, 각 알고리즘들이 어느 경우에 사용될 수 있는지 체계적으로 공부
  
2. #### 단순한 방법에서 시작할 수 있을지?
   
   - 좀 더 효율적인 자료 구조를 사용하거나 계산 과정에서 같은 정보를 두 번 중복으로 계산하지 않는 등의 최적화
   - ex) 3명의 아이에게 20개 사탕을 배분할 때 사탕 총 량의 순서는 상관 없음
  
3. #### 내가 문제를 푸는 과정을 수식화 할 수 있을지?

4. #### 문제를 단순화할 수 없을지?
   
   - 주어진 문제의 좀더 쉬운 변형판을 먼저 풀어보기
   - ex) 문제의 제약 조건 없애기, 계산해야 하는 변수의 수 줄이기, 다차원의 문제를 1차원으로 줄여 표현해보기 등)
  
5. #### 그림으로 그려볼 수 있을지?
   - 문제에 관련된 그림을 그려 보는 것
  
6. #### 수식으로 표현할 수 있는지?
   - 평문으로 쓰여 있는 문제를 수식으로 표현하는 것도 도움이 되는 경우가 있음
  
7. #### 문제를 분해할 수 있을지?
   - 더 다루기 쉬운 형태로 문제를 변형
  
8. #### 뒤에서부터 생각해서 문제를 풀 수 있을지?
   - 문제에 내재된 순서를 바꿔 보는 것
   - ex) 사다리 게임에서 A에서 B로 가는 방법을 찿기란 어렵지만 B에서 A로 가는 방법을 찾기는 쉬움
  
9. #### 순서를 강제할 수 있을지?
   - 순서가 없는 문제에 순서를 강제해서 문제를 풀어보기
   - ex) 2차원 격자를 이용한 문제, 경우의 수
   
10. #### 특정 형태의 답만을 고려할 수 있을지?
    <br/>

## 추가 정리
<https://data-make.tistory.com/>
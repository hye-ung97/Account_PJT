# Account_PJT

### 1️⃣ Info
Account(계좌) 시스템은 사용자와 계좌의 정보를 저장하고 있으며, 
외부 시스템에서 거래를 요청할 경우 거래 정보를 받아서 계좌에서 잔액을 거래금액만큼 줄이거나(결제), 
거래금액만큼 늘리는(결제 취소) 거래 관리 기능을 제공하는 시스템입니다.

### 2️⃣ 구현 방법
1. Spring boot, JAVA 이용
2. DB : H2 DB(memory DB 모드)
3. DB를 접근하는 방법은 Spring data jpa를 활용
4. Embedded redis를 활용
5. API Request body와 Response body는 json 타입으로 표현

### 3️⃣ API

#### [1] About 계좌
1) 계좌 생성
2) 계좌 해지
3) 계좌 확인

#### [2] About 거래(Transaction)
1) 잔액 사용
2) 잔액 사용 취소
3) 거래 확인

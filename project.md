프로젝트 : BankProject
패키지(총 4개 패키지, 7개 클래스)
- BankDAO(Data Access Object) : BankSQL, DBC 클래스
- BankDTO(Data Transfer Object) : Client, Code, Account 클래스
- Main : BankMain 클래스
- Util : BankUtil 클래스

- Client(회원정보) : 아이디, 비밀번호, 이름, 등등..
- Code(계좌종류) : 계좌코드, 계좌이름
- Account(계좌) : 계좌번호, Client 아이디, Code 계좌코드, 잔액

※ Client의 id를 FK로 받아서 한사람이 3개 이상 계좌를 만들 수 없게 설정
※ Code의 계좌종류 일반, 적금, 청약, 주식 계좌로 설계
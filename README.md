## 소켓통신을 이용한 채팅 프로그램 만들기

### 기능

- 양방향, 다중접속
- 같은 방 유저들끼리 채팅 가능
- 귓속말(쪽지 보내기)
- 방 만들기
- 방 나가기



### 프로토콜 별 기능

- Whisper 귓속말
- Chatting 채팅 "Chatting/방이름/유저이름/내용"
- NewUser
- NewRoom
- CreateRoom 방 생성
- EnterRoom 방 입장 "EnterRoom/방이름/유저이름"
- ExitRoom 방 나가기 "ExitRoom/방이름/유저이름"
- OldUser/OldRoom 기존에 있는 유저들 정보 업데이트

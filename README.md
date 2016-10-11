# instagram-auto-like-with-Python

파이썬을 활용한 인스타그램 자동 좋아요 소스

목적 : 인스타그램을 활용하는데 조금 더 편하게 자동화하고 싶었고 현재 업체에서 팔로워 1000명 모집! 프로그램들을 만들어보고 싶었습니다

사용한 라이브러리 : Selenium

셀레니움의 장점 : 웹 브라우저를 직접 작동할 경우 용이(단, 속도가 느린편이나 인스타그램측에서 많은 좋아요수를 할 경우 제재를 가하기 때문에 셀레니움으로 활용해도 좋다고 판단)



### 구현한 기능

- 인스타그램 메인 화면에서 Follower들의 글을 자동 좋아요

- 특정 해시태그를 검색한 후, n회 자동 좋아요

- 작업이 완료되면 슬랙으로 메세지 전송


### 추후 구현할 기능

- 내 게시글을 좋아요한 유저의 프로필로 가서 좋아요 하고 나오기

- 나를 팔로워한 사람들을 팔로우하기 ( 단순 팔로잉은 너무나 쉬우나 추가 기능 필요 )
- 연계해서, 내가 특정 유저를 팔로잉한 경우, 24시간내로 상대방이 나를 팔로우하지 않으면 팔로잉 상태 끊기 ( DB와 연동해야하나..? )

- 댓글 달기 ( 이건 지금도 가능하나, 무의미한 댓글을 달기 싫어서 추후 텍스트마이닝과 연계해서 딥러닝을.. 사용해보면 어떨까 생각중 )

- 하루의 특정 시간에 자동으로 위의 기능들을 실행하기

### 더 익혀야 할 것들

- 데이터베이스 지식
- 웹프로그래밍 지식 ( Flask나 Django )


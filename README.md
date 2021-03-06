# React-Native-Talk

<br>

React-Native로 제작한 IOS, Android 크로스 플랫폼 실시간 채팅 애플리케이션입니다. 

개발 참고 서적: [처음 배우는 리액트 네이티브](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9791162243879&orderClick=LEa&Kc=)  

google Firebase를 이용하여 로그인, 회원가입 등의 기능을 구현하였습니다.

테스트환경: Expo Android 에뮬레이터 및 실기기

이하의 스크린샷으로 프로그램의 기능을 설명하겠습니다.

<br>

------------
<br>

### 로그인 페이지 

<br>

![KakaoTalk_20210822_114906519](https://user-images.githubusercontent.com/55654216/130340350-823a5c3c-6049-430c-ab99-20eb97eec7a6.jpg)

로그인 화면에서 이메일 형식, 패스워드 등 유효성 검사를 확인합니다. 

유효성 검사에서 올바른 형식을 입력해야 로그인 버튼이 활성화됩니다.

------------
<br>

### 회원가입 페이지 

<br>

![KakaoTalk_20210822_114906726](https://user-images.githubusercontent.com/55654216/130340351-7576aaa5-cc25-428b-afcb-01c619c53543.jpg)

회원가입 화면에서는 사용자의 프로필 이미지, 이름, 이메일, 비밀번호 정보를 입력받아 회원가입을 진행합니다.

카메라 아이콘을 클릭하면 기기 내 다른 이미지로 프로필 이미지를 변경할 수 있습니다.

여기서도 마찬가지로 올바른 형식으로 정보를 입력하면 회원가입 버튼이 활성화됩니다.

------------
<br>

### 채널 선택 페이지 
<br>

![KakaoTalk_20210822_114906388](https://user-images.githubusercontent.com/55654216/130340357-8aad47a0-7808-4c22-a938-3862797689bf.jpg)

로그인 성공 시 채널 화면으로 넘어갑니다.

채널화면에서는 채널을 생성하거나, 채널 화면에서는 만들어진 채널에서 대화를 할 수 있습니다. 

------------
<br>

### 채널 생성 페이지 
<br>

![KakaoTalk_20210822_114906062](https://user-images.githubusercontent.com/55654216/130340354-79cedc34-4c16-487e-b798-87a025d36f6c.jpg)

채널 생성에는 채널 이름과 채널에 대한 설명을 입력합니다.

------------
<br>

### 채널 대화방 페이지 
<br>

![KakaoTalk_20210822_114906230](https://user-images.githubusercontent.com/55654216/130340355-9eb337a4-6deb-4a77-847d-f682a60e3d37.jpg)

채널 대화방에서는 다른 사람의 프로필 이미지가 보이며, 다른 사용자의 글은 왼쪽에 자신의 글은 오른쪽에 보여지게 됩니다.

------------
<br>

### 프로필 페이지 
<br>

![KakaoTalk_20210822_114905887](https://user-images.githubusercontent.com/55654216/130340353-e59f15de-8a97-450c-a95b-8a2662461199.jpg)

채널 화면에서 하단 내비게이션으로 프로필 화면으로 이동할 수 있습니다. 

프로필화면에서는 자신의 프로필 이미지를 변경할 수 있습니다.

또한 자신의 이름과 이메일을 확인할 수 있습니다. 

로그아웃 버튼을 누르면 로그인 페이지로 되돌아갑니다.

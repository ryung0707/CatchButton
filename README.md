# CatchButton

## 개요
- 핵심기능: 마우스를 올리면 버튼이 랜덤한 위치로 이동
- 화면구성: 버튼

## 실행 화면
- 1단계 코드의 실행(기본 도망기능)
  <img width="828" height="485" alt="image" src="https://github.com/user-attachments/assets/d84eda8e-86cb-47a8-829e-36b9e3f87a6f" />
- 2단계 시각적 피드백(버튼을 잡았을때 메시지 박스 출력)
  <img width="186" height="140" alt="image" src="https://github.com/user-attachments/assets/e33435f8-067c-4126-9b30-994fed029147" />
  
  * 메시지 박스 이름 변경(검거 성공.)
  * 단계별 메시지
- 3단계 난이도 조정(잡을 수록 점점 작아짐)
  <img width="796" height="473" alt="image" src="https://github.com/user-attachments/assets/7ef3cba2-ca1f-4cb1-af3e-529e9e921d39" />

  * 210 / 80인 버튼 크기를 -21 / -80 만큼 줄여 난이도 상승
  * 잡고 나면, 단계상승
- 4단계 게임 오버 및 리셋
   ..못해서 사진 없음

## 어려웠던점
- 버튼을 잡는것. 버튼 잡는거 자체가 어려워  *button1.Location = new Point(next_x, next_y);* 를 문서 처리 한 후 테스트를 진행함
- 기능 함수같은 경우, 제미나이에 도움을 받음.
- "실패 변수"를 만드는것. 즉 배경 클릭 시 실패로 간주시키는것이 어려웠다. 인식 자체가 되지 않아 헤매는중



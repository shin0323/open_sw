# 오픈소스 sw 개론 과제 2

## top

## ps
- 현재 실행 중인 프로세스의 목록을 보여주는 명령어이다. top과 달리 실시간으로 갱신되지 않고 명령어를 입력하는 순간의 정적인 상태를 보여준다.
- 주요 옵션
  1. ps -ef : 가장 표준적이고 깔끔한 상태\
     -e : 모든 프로세스를 표시하는 옵션\
     -f : 풀 포맷으로 표시 옵션
  3. ps aux : cpu와 메모리 점유율 볼때 유리
     a : 다른 사용자의 프로세스도 표시\
     u : 사용자 중심의 포맷\
     x : 터미널 제어 없이 실행되는 프로세스(데몬 등)도 표시
     
- 출력 필드 설명
  1. uid : 프로세스를 실행한 사용자 id
  2. pid : 프로세스 고유 번호
  3. ppid : 부모 프로세스의 id
  4. c : cpu 사용률
  5. stime : 프로세스가 시작된 시간
  6. tty : 프로세스가 연결된 터미널
  7. time : 총 cpu 사용 시간
  8. cmd : 실행된 명령어 및 인수
 
 <img width="565" height="108" alt="image" src="https://github.com/user-attachments/assets/3ab8f691-abad-4bc4-ad7a-a15f4e06221b" />

     

## jobs

## kill













# [LDK2024] 2024년 가을학기 대전대학교 리눅스 강좌

## 국정 공휴일 휴강에 따른 강의 일정 변경 (보강 일자 반영) 
* wk1 (9.4): 강의 소개
* wk2 (9.11): 리눅스 개요
* wk3 (9.25): 리눅스 명령어-1
* wk4 (10.2): 리눅스 명령어-2
* wk5 (10.16): vim 에디터
* wk6 (10.23): 중간 고사
* wk7 (11.6): 도커 개요
* wk8 (11.13): 도커 명령어
* wk9 (11.20): 도커 기반 서비스 배포
* wk10 (11.27): 쿠버네티스 개념 및 구조
* wk11 (12.4): 쿠버네티스 환경 구축
* wk12 (12.7(토)): 쿠버네티스 기본 명령어
* wk13 (12.11(수)): 쿠버네티스 네트워크
* wk14 (12.14(토)): 쿠버네티스 네기반 서비스 배포
* wk15 (12.18): 기말 고사


## 멤버 목록

|이름|깃헙 주소|
|------|---|
|고수*	|https://github.com/troll11111/LDK2024 |
|김민*	|https://github.com/keem-minseo/LDK2024 |
|김서*	|https://github.com/sy94543/LDK2024 |
|김* 현 |https://github.com/LDK2024 |
|김* 환 ||
|김준*	|https://github.com/june713/LDK2024 |
|김희*  ||
|박훈*	|https://github.com/znrks02/LDK2024 |
|배은*  ||
|손병*	|https://github.com/bottle-siu/LDK2024 |
|신성*	|https://github.com/mrshin60/LDK2024 |
|안주*	|https://github.com/anjubbro/LDK2024 |
|어하*	|https://github.com/Habin87/habin.git |
|엄태*	|https://github.com/UTJ45/utj.git |
|윤지*	|https://github.com/20230400/lovehun2429.git |
|이원*	|https://github.com/lws0619/LDK2024 |
|이홍*	|https://github.com/junnong15/LDK2024 |
|장우*	|https://github.com/dnwlse/LDK2024 |
|전  *  ||
|진승*	|https://github.com/jin-sghn/LDK2024 |
|최재*	|https://github.com/dmltk/LDK2024 |
|하지*	|https://github.com/20231841/LDK2024 |
|홍우*  |https://github.com/anthony20049096/LDK204 |

## FAQ

<details open>
<summary><b> chatGPT 적극 활용</b></summary>
질문이 생기면 chatGPT에게 물어보고 직접 해결하도록 노력해보세요. 
chatGPT 활용 기술은 실무에 꼭 필요한 기술입니다. 
</details>

<details close>
<summary><b> /usr/lib.systemd/system/ssh.service; disabled; ... Active: inactive (dead)  문제 </b></summary>
강의 자료의 설치 순서 대로 "Install OpenSSH server" 체크 하여 ssh 서버를 설치했다는 가정하에

* 먼저 ssh을 실행시킴: sudo systemctl start ssh
* 부팅시 자동 실행되도록 설정: sudo systemctl enable ssh

</details>

<details close>
<summary><b> VM 서버로부터 파일 다운로드 방법 </b></summary>

* MobaXterm: 좌측 파일 창에서 파일 선택화  상단에 파일 다운로드 아이콘 클릭 \n
* putty: "pcppscp {user_name}@10.0.2.4:/home/{user_name}/file.txt c:\tmp"

  - 참고 사이트: https://xfree302.tistory.com/269

</details>



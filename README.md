# Lottery_Ethereum
Lottery Program

복권 = 계약
상금 n이더
참가자 p1,p2..n명 각 1이더씩 냄
관리자는 상금을 가질 수 없음


변수
이름     목적
manager  당첨자를 뽑는 사람
	       * 주소포함 =>흔히 string배열을 생각할 수 있으나 solidity에는 주소유형이 있음
players  돈을 보내는 사람
          *계약서에 돈을 보낸 모든 사람에 대한 주소 배열

함수
이름         목적
enter       복권에 참가하는 참가입장
pickWinner  참가자 명단에서 랜덤으로 승자 선택기능
   
   
랜덤 생성


1. 
현재 블록 난이도 int
현재 시간
모든 참가자들의 주소

2.
SHA3알고리즘

3.
16진수 큰 수

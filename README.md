# network-security
C, C++ 기반 PCAP API를 활용하여 PACKET의 정보를 출력하는 프로그램 작성  

Ethernet Header: src mac / dst mac  
IP Header: src ip / dst ip  
TCP Header: src port / dst port  
HTTP Message도 출력 (Message: Application 계층의 데이터 단위)  

*TCP protocol 만을 대상으로 진행 (UDP는 무시), sniff_improved.c, myheader.h 코드 참고  
*IP header, tcp header 에 있는 길이 정보를 잘 사용할 것. (ip_header_len)  

- 과제사항 + 본인의 이해를 보고서로 구체적 작성하고, 코드를 포함(github 가능)하여 제출.  
- 제출 형식: [WHS][PCAP Programming] OO반 이름(전화번호 뒷자리).pdf  

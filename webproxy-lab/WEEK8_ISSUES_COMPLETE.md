# Week 8 Issue Checklist

`week8_issues_complete.csv` 내용을 프로젝트 안에서 바로 확인할 수 있도록 옮긴 체크리스트입니다.

## 공통

- [ ] 핵심 역량 목표 수립
- [ ] 핵심 역량 목표 달성률 평가
- [ ] AI 활용 원칙 수립
- [ ] 이번 주 할 일(업무) 검토
- [ ] WIL(What I Learned) 작성
- [ ] 팀 협업 룰/팁 정리 및 합의

## 학습

- [ ] 네트워크 개념과 TCP/IP 계층
- [ ] 소켓과 소켓 인터페이스 (`socket`, `bind`, `listen`, `accept`, `connect`, `close`)
- [ ] 클라이언트-서버 모델 이해
- [ ] 파일 디스크립터
- [ ] Datagram Socket vs Stream Socket
- [ ] 웹서버
- [ ] 웹컨텐츠 이해 (MIME type, 정적, 동적, CGI)
- [ ] HTTP 이해 (요청/응답, 헤더, 메소드, 상태코드, HEAD 메소드)
- [ ] 프록시 서버 이해

## 구현

- [ ] echo서버 - `open_clientfd()`
- [ ] echo서버 - `open_listenfd()`
- [ ] echo서버 - 클라이언트 `main()`
- [ ] echo서버 - 서버 `main()`
- [ ] echo서버 - 서버 `echo()`
- [ ] tiny서버 - `main()`
- [ ] tiny서버 - `doit()`
- [ ] tiny서버 - `read_requesthdrs()`
- [ ] tiny서버 - `parse_uri()`
- [ ] tiny서버 - `serve_static()`
- [ ] tiny서버 - `serve_dynamic()`
- [ ] tiny서버 - `get_filetype()`
- [ ] tiny서버 - `clienterror()`
- [ ] tiny서버 - CGI `adder` 구현
- [ ] proxy서버 - 웹 프록시 (순차적 처리)
- [ ] proxy서버 - 동시병렬 처리
- [ ] proxy서버 - 캐싱 웹오브젝트

## 테스트

- [ ] echo서버 - `telnet` 접속 후 입력 내용을 응답으로 출력
- [ ] tiny서버 - `telnet`으로 tiny의 HTTP 버전 정보 확인
- [ ] tiny서버 - 브라우저에서 `home.html` 요청/응답 확인
- [ ] tiny서버 - 브라우저에서 `cgi-bin/adder?123&456` 요청/응답 확인
- [ ] proxy서버 - PC 네트워크 설정에서 프록시 설정
- [ ] proxy서버 - 로컬 -> 프록시 -> tiny `home.html` 요청 성공
- [ ] proxy서버 - 원격 프록시 서버 중지 후, 로컬 -> 프록시 -> tiny `home.html` 요청 실패
- [ ] proxy서버 - 요청 순차적 처리 (`basic test`)
- [ ] proxy서버 - 요청 동시병렬 처리 (`concurrency test`)
- [ ] proxy서버 - 요청 캐싱 처리 (`cache test`)

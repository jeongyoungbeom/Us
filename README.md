# Us 소셜플랫폼

### Us 사이트

* 기간 : 2021.11.08 ~ 2021.12.30
* 환경 : Chrome 브라우저
* 주제 : 소셜 플랫폼
* 개발 : VScode, mysql
* 사용 언어 : node.js, react, Javascript ES6
* 사용 기술 : axios, socket.io, mail.api

### 시퀄라이즈 적용중...

# 프로젝트 상세내용

**구현 목표**
> 관리자 페이지
> 
- 가입한 회원의 정보 및 회원의 게시물, 채팅방 목록, 상세내용 등을 확인 가능
- 회원들이 생성한 채팅방 및 게시물, 댓글, 상세 내용 확인 가능
- 회원들의 문의 내용 확인 및 답변 등록 및 수정
- 조건 검색을 통한 특정 게시물 및 채팅방, 회원, 문의 검색
- 회원 문의 삭제 기능
- 로그인/로그아웃 기능
- 좌측 사이드 바 하단의 로고 클릭 시 사용자 로그인 페이지로 이동

> 사용자 페이지
> 
- 로그인/회원가입/아이디찾기/비밀번호찾기 가능
- 개인 코드를 통해 친구 등록 및 해지
- 마이페이지를 통해 프로필 수정 및 문의하기 기능
- 게시물 등록/수정/삭제 기능
    - 사진은 최대 6개 최소 1개, 내용 입력 가능(내용 없어도 등록 가능)
    - 삭제 시 해당 게시물 댓글 삭제
- 게시물 댓글(계층형) 기능
    - 본인이 단 댓글 삭제 가능
    - 댓글에 대댓글 작성 가능
    - 댓글 공감/공감 취소 기능

## 나의 역할
### 백엔드
- 관리자페이지 구현
- 실시간 1:1채팅 구현(socket.io)
- 메인페이지, 게시글 페이지 구현
- DB 구현

## ERD
![ERD](/image/erd.png)

# 구동 화면
## 사용자
  ### 회원가입
![회원가입](/image/사용자_회원가입.gif)  
  ### 아이디 & 비밀번호 찾기
![아이디찾기](/image/사용자_찾기.gif)
  ### 로그인 & 친구추가
![로그인](/image/사용자_로그인친구추가.gif)
  ### 게시물 등록
![등록](/image/사용자_게시물등록.gif)
  ### 사용자 채팅
![채팅](/image/사용자_채팅.gif)

## 관리자
  ### 대시보드
![대시보드](/image/관리자_대시보드.gif)
  ### 회원관리
![회원관리](/image/관리자_회원관리.gif)
  ### 게시물관리
![게시물관리](/image/관리자_게시물관리.gif)
  ### 채팅관리
![채팅관리](/image/관리자_채팅관리.gif)
  ### 문의사항
![문의사항](/image/관리자_문의사항.gif)






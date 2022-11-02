# FastAPI 
### 1. What is FastAPI?
- Sebastián Ramírez라는 사람이 만든 파이썬 기반 오픈소스 웹 프레임워크이다.(혼자 만드셨다고 한다.)<br>
- 타입 힌트에 기초한다.
- 장고나 플라스크보다 2배 정도 빠르고 간결하다.
- 비동기처리를 기본적으로 지원하는 프레임워크이다.(비동기처리란 특정코드가 오래 걸리면 일단 뒤로하고 다른 코드 실행가능 한 것)
- api 만드는 툴같은 느낌이다.

### 2. Command
- pip install fastapi
- pip install "uvicorn[standard]"
- uvicorn main:app --reload

### 3. 
- docs - swagger : RESTful api를 json으로 표현하는 방식. get post delete 인터페이스를 제공한다.
- redoc - ReDoc : 오픈소스 툴이며 문서를 제공한다.
- openapi.json : RESTful의 access point

# FastAPI로 블로그 구현
- 주소 : https://cg9tsb.deta.dev/docs
  1. 유저를 생성한다. (아이디, 이메일, 비밀번호 입력)
  2. 우측 상단에 Authorize 버튼을 눌러 인증을 한다. (이메일, 비밀번호 입력)
  3. 블로그를 관리한다. (생성, 업데이트, 삭제, 보기)
- ![image](https://user-images.githubusercontent.com/73030613/199460770-04211653-3032-4ead-a5ef-37e62bd599f5.png)


- 클론 코딩 출처 : https://www.youtube.com/watch?v=7t2alSnE2-I


로그인

마크업 순서
전체 틀은 form 태그로 구성함.
1. 로그인(제목)
fieldset 안의 legend에 입력함.

2. 아이디 레이블과 입력서식
div로 감싼 label과 input으로 입력함.

3. 비밀번호 레이블과 입력서식
div로 감싼 label과 input으로 입력함.

4. 로그인 버튼
button 태그를 이용함.

5. 회원가입 및 아이디/비밀번호 찾기 링크
각각 하이퍼링크 태그를 이용하고 div로 묶었음.

CSS
1. .loginForm
box-sizing: border-box로 크기 고정함.

2. fieldset
border 값을 0으로 줘서 테두리 없앰.

3. legend
margin-left에 음수값을 줘서 로그인(제목)을 왼쪽으로 이동시켜 정렬을 맞춤.

4. .login__group
로그인(제목)을 제외한 나머지를 그룹으로 묶고, padding과 margin을 이용해 크기를 조절함.

5. .idInput
아이디와 비밀번호 입력 칸 사이를 조정함.

6. label
아이디와 비밀번호를 왼쪽 정렬함.
padding으로 왼쪽 여백을 만들어 줌.

7. input
아이디와 패스워드 입력 칸의 크기를 조정함.

8. .text1
아이디 입력칸의 위치를 조정함.

9. .pwInput
구분선을 위치시키기 위해 높이를 조정함.

10. button
로그인 버튼을 흰 박스의 오른쪽 상단으로 이동시키기 위해 position: absolute를 사용함.

11. .a
margin auto로 좌우 가운데 정렬하고 padding-top과 margin-bottom으로 상하 가운데 정렬함.
(margin auto가 마지막에 오면 크기 달라짐)

12. .a1
float을 이용해 왼쪽으로 이동함.

13. .a2
float을 이용해 오른쪽으로 이동함.






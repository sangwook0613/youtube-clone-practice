# Youtube Clone

Cloning Youtube with Vanilla and NodeJS

## Understanding middlewares

" 추후 정리 필요

미들웨어란 ? 라우트(유저)와 실행하는 콜백함수(응답) 사이에서 동작하는 함수.
적용방법은,
전역으로 적용하는 = app.use() ;
각각 적용하는 = 라우팅 과 콜백함수 사이에 쓰는방법;
두가지.

모든 미들웨어함수는 유저- 응답 사이에서 동작하므로 미들웨어가 끝나고 난 뒤, 응답(콜백함수)를 실행하기 위해서 next() 가 필수적임. 혹은 미들웨어에서 중단시킬 수 있음.

주요 미들웨어로는
Morgan - 로그를 남겨줌
helmet - 기초보안담당함
cookieParser - 쿠키를 다룰 수 있음
bodyParser - form데이터를 서버로 받아와서 활용가능함.

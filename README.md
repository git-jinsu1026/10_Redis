# 10_Redis


Redis는 하드에 보통 데이터를 저장하는데
메모리를 저장하는 게 속도가 더 빠르다
데이터베이스처럼 사용가능하다

용도

사용자의 세션서버
웹페이지 캐싱
(데이터들을 미리 적재시켜서 화면에 미리 뿌려주는 것)
(쿼리를 사용하지않게 되면 더 빠르다.)

세션에서도 REDIS 사용가능

서버1 서버2 서버3 ==> 세션서버Redis를 바라보게한다.

윈도우에서 공식지원하지 않음

MAC

$ brew install redis

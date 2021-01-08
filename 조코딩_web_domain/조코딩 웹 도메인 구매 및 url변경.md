### 1.사이트 공개 방법
1) 내 컴퓨터를 서버로
2) 외부 서버를 이용

### 2. 검색을 하는 방법
- 검색 엔진마다 크롤러 가 존재
- 크롤러가 정보를 모아 엔진에 전달
- robot.txt 파일에 크롤러의 허용 유무 있음
- sitemap.xml 에 사이트를 효율적 찾는 경로 있음

**robots.txt 로 크롤러 허용**
- 웹 최상단 파일에 저장

### 사이트맵 생성 및 추가
- 구글 https://www.xml-sitemaps.com/
- 웹 최상단 파일에 넣기
- robots 파일에 사이트맵 주소 추가
- 완료시 다시 deploy 해야함

***검색 엔진 최적화(SEO)***
: 검색시 사이트 상단에 노출되게 함

### 도메인(domain)이란?
:ip는 사람이 이해하고 기억하기 어렵기 때문에 이를 위해서 각 ip에 이름을 부여할 수 있게 했는데, 이것을 도메인이라고 한다.

opentutorials.org -> 115.68.24.88
naver.com -> 220.95.233.172
daum.net -> 114.108.157.19
![도메인과 서버](https://s3.ap-northeast-2.amazonaws.com/opentutorials-user-file/module/121/298.png)


- 무료 도메인 사이트 프리놈 https://www.freenom.com
- 프리놈에서 도메인 구매 후 
- netlify 도메인 설정에서 도메인 추가하고 ip주소 얻음 https://app.netlify.com/
- 프리놈에서 도메인 설정에서 url이름이랑 ip주소 설정 후 기다림
- netlify에서 도메인 확인 가능

# NaverShoppingCrawler

  한 개의 네이버 쇼핑몰 페이지 댓글과 별점을 크롤링 하는 라이브러리 입니다.

## __1. 필요 라이브러리 목록__


      1. selenium
      2. beautifulsoup4
      3. lxml

##  __2. 필요 프로그램__

      1. chromedriver

## __3. 사용 간 유의점__

      1. chromedriver 실행에는 chrome이 필요합니다.
      2. chromedriver버전과 chrome버전을 맞춰주십시오.
      3. chromedriver는 라이브러리와 동일 폴더 내에 있어야만 합니다.

## __4. 사용 방법__

>1. 클래스를 생성합니다

      crowler = NaverShoppingCrawler()
>2. 크롤링 하길 원하는 페이지의 URL을 getCrowlling 함수에 삽입합니다

      crowler.getCrawlling(URL)
>3. 크롤링 결과가 txt 파일로 생성 됩니다 (이름은 nv_mid 값으로 생성됩니다)

## __5. 저장 결과__
|review | "\t" | score |"\n"|
|---|---|---|---|
|댓글1 | "\t" | 0 |"\n"|
|댓글2 | "\t" | 4 |"\n"|
|댓글3 | "\t" | 5 |"\n"|

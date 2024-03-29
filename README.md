# 웹툰화 된 웹소설 특징 분석
- 리디북스에서 판매되는 웹소설의 키워드를 중심으로 웹툰화 된 웹소설의 특징을 분석하고자 함.
- 리디북스 키워드 크롤링 소스코드, 발표자료 수록.

## 👁 분석 과정
### 1. 주제 선정 동기
- 웹툰의 영상화는 '은밀하게 위대하게(2013)' 등 10년 전부터 시작했고, 국내외 온라인 동영상 서비스(OTT)의 대중화로 스토리 사용권(IP)의 중요성은 계속 상승하고 있는 상황. 
- 웹소설 기반 웹툰이 등장하기 시작.
- 웹소설 시장의 규모가 커지고 있는 가운데 웹소설의 웹툰화도 커질것으로 전망해, 웹툰화 후 흥행에 성공할 웹소설의 특징을 분석하고자 함.
### 2. 데이터 수집 및 처리
- 웹툰 플랫폼 상단에 위치한 웹툰 60개를 선정해서 전자책 플랫폼인 리디북스에서 키워드를 추출.
- BeautifulSoup 패키지를 사용해서 python으로 키워드를 크롤링.
- main.py를 실행시키면 urls 파일을 읽어서 키워드를 추출해 keywords 파일을 생성.
- 크롤링한 데이터를 UCINET으로 분석.
### 3. 데이터 분석 및 결과 해석
- eigenvector로 중심성을, Faction으로 하위집단을 분석해 웹툰화 된 원작 소설의 키워드는 대부분 서로 연관성이 높다는 결론 도출.
### 4. 최종 결론
- 웹툰화에 성공한 웹소설은 기존에 흥행에 성공한 웹툰의 소설의 키워드와 비슷했기 때문에, 흥행에 성공했던 웹툰의 원작 소설과 비슷한 키워드를 가진 웹소설은 추후 웹툰화에  성공할 가능성이 높다는 것을 의미.
- 중요한 키워드는 '작품의 평점', '남녀 주인공의 성격', '작품의 배경'.
- 즉, 작품의 평점이 높으면서,
‘남녀 주인공의 성격’과, ‘작품의 배경’과 관련된 키워드가 웹툰화에 성공한 기존에 존재한 웹툰의 원작소설과 비슷한 키워드를 가진 웹소설이 흥행할 가능성이 높다고 예측됨.

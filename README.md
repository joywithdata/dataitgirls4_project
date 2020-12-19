# dataitgirls4-team_4-project
# 신금호텔팀
<b>팀원</b>: 김새민, 김주현, 이다슬, 정희경, 최하나

## 프로젝트 이름  
호텔 리뷰 맛집 여기 있어요!

## 프로젝트 개요
호텔 예약 사이트의 리뷰 중 "좋아요", "굿", "별로에요" 같은 리뷰 말고, 실제로 호텔 예약에 도움되는 리뷰의 특징은 무엇일까? 
도움되는 리뷰 순으로 정렬할 수 있는 새로운 리뷰 정렬 모델을 제안합니다.

## 폴더 설명
1. Web Scrapping
- 호텔 예약 사이트 웹 스크래핑(크롤링) 코드
- [리뷰 크롤링_아고다](Review_Crawling_Agoda.html)
- [리뷰 크롤링 야놀자](Review_Crawling_Yanolja.html)
- [리뷰 크롤링 여기어때](Review_Crawling_Goodchoice.html)

2. Preprocessing
- 데이터 전처리 관련 코드

3. Visualization
- 아래 기준으로 분류 라벨링 작업을 진행하고, 그 데이터로 시각화를 시도한 코드
  (1) 도움되는 리뷰 & 도움되지 않는 리뷰 (2) 긍정 & 부정 & 중립 (3) 시설 & 위치 & 인테리어 & 친절 & 청결 & 방음
- Excel, Tableau, Python(Plotly) 사용

4. Modeling
- 라벨링 작업 후 분류 모델링 및 confusion matrix로 평가한 코드 

Data
- 특수문자, 이모티콘, 개행문자 등을 제거하고 맞춤법을 올바르게 수정해 전처리된, 분석에 사용된 Law data입니다.

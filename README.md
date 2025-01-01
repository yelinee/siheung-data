# 시흥시 상권 분석 프로젝트
시흥시 상권 데이터를 분석한 시흥시 연계 프로젝트입니다.

프로젝트 기간: 2021.05 - 2021.06

## 프로젝트 목표
- 1차 분석: 행정동의 상권 발달과 인구 비례 연관성 확인
- 2차 분석: 특정 동의 상권 비율과 서울시 특정 구의 상권 비율 비교(음식분야)

## 기술 스택
<img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"> <img src="https://img.shields.io/badge/numpy-5276C6?style=for-the-badge&logo=numpy&logoColor=white"> <img src="https://img.shields.io/badge/pandas-10074C?style=for-the-badge&logo=pandas&logoColor=white">

## 분석 결과
### 1차 분석
<img style="width: 400px" src="https://github.com/user-attachments/assets/2ea4db65-1f84-4cee-a8b0-e63fc32352aa">

- ‘상가수’와 ‘인구수’의 상관계수 계산 결과 1에 가까우므로 ‘상가수’와 ‘인’구수’ 간의 연관성은 깊다.
- 연관관계에 대한 시각화 결과 ‘목감동’, ‘은행동’, ‘연성+장곡동’은 인구수에 비해 상권이 덜 발달했다고 볼 수 있다. 따라서 해당 동의 상권 발달에 힘써야 한다.

### 2차 분석
<img style="width: 800px" src="https://github.com/user-attachments/assets/1e3013ad-0d3c-4c3a-91f8-1c1006d6c36a">

- 서울시, 시흥시 모두 ‘한식음식점’, ‘유흥주점’이 가장 큰 비중을 차지하고 있다.
- 서울시와 비교한 결과에 따라 시흥시에서 ‘양식’과 ‘커피점/카페’의 상권 발달에 힘쓰는 것이 좋을 것 같다.

## 아쉬운 점
- 시흥시 상권 데이터에서 행정동을 주소로부터 추출하여 실제 행정동과는 차이가 생김. 이에 따라 분석 결과가 정확하지 않았을 것으로 추정. 
- 배곧동과 서울시 강남구를 비교하고 싶었으나 배곧동을 행정동으로 추출하지 못함.
- 2019, 2020, 2021년 데이터(시계열 데이터)를 가지고 2022년 상권을 예측(회귀 분석)하고 싶었으나 데이터를 구하지 못함.

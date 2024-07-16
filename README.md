# first_project
## 1차 프로젝트 - 데이터분석_경제지표를 통한 환율 예측 모델 생성 
## 프로젝트를 기획하게 된 배경 

<b>환율</b>은 국제 무역 및 금융 거래에서 중요한 역할을 합니다. 그러나 환율은 <u>예측하기 어렵고 불안정한 경향</u>이 있어서 예측이 필요성이 대두됩니다. 예측에는 다양한 방법이 있지만, 머신러닝 알고리즘을 이용한 예측 방법이 최근에 주목받고 있습니다. 이에 따라, <b>이번 프로젝트는 머신러닝을 이용한 환율 예측 모델을 개발하는 것을 목표로 삼고 있습니다.</b>

## 프로젝트 목표 
  - <b>환율 예측 모델 개발</b>: 머신 러닝 알고리즘을 사용하여 환율 예측 모델을 개발하고, 모델의 성능을 평가합니다.
  - <b>예측 변수 파악</b>: 다양한 변수들이 환율 예측에 영향을 미친다는 가정 하에, 어떤 변수들이 환율예측에 가장 영향을 미치는지 파악합니다.
  - <b>모델해석</b>: 개발된 모델을 해석하여, 각 변수가 환율 예측에 어떤 방향으로 영향을 미치는지 분석합니다.

## 프로젝트 분석 절차 

<b>1. 환율의 특성 분석</b>: 환율의 발전에 영향을 미치는 장비들의 변화를 파악하고, 해당 장비의 변화에 대한 변화를 분석한다.
<b>2. 경제지표 분석</b>: 환율과 관련된 경제 지표들(실질 GDP, 인플레이션, 수출입 등)을 분석하여, 환율과 관계 관계를 파악한다.
<b>3. 데이터 수집</b>: 수집된 데이터를 곰팡이로 표현하여 다양한 인사이트를 발견하고 보고 및 발표 자료 작성에 활용한다.
<b>4. 데이터 전처리</b>: 데이터를 수집하고 청소하고, 필요한 데이터만 추출하여 최적의 전처리 작업을 실시한다.
<b>5. 데이터 분석</b>: 수집한 데이터들 사이에 상관성을 분석하여 최종 모델에 넣을 변수를 골라낸다.
<b>6. 모델 생성</b>: 미세한 파라미터 조정으로 골라낸 변수들과 함께 최소의 오차값을 찾아낸다. 

## 주요 분석 기능 
### 데이터 수집 
    - Requests,Selenium, Beautiful Soup을 이용한 환율 정보 크롤링
### 데이터 전처리 
    - Pandas 라이브러리를 이용한  Time Stamp 맞추기
    - scikit-learn 라이브러리를 이용한 기타 데이터 전처리
### 데이터 분석
    - 시계열(ARIMA),  선형회귀 (Linear Regression) 등 모델들을 복합적으로 사용하여 시계열 데이터의 패턴을 파악
    - 하이퍼파라메터와 교차검증을 통한 모델 성능 개선
    - matplotlib, seaborn 등을 통한 모델 예측 결과 시각화

## 프로젝트 역할 분담 
### (조장) 최소현 
  - 데이터 수집 : 환율 변동에 영향을 주는 경제적 요소에 대한 데이터 수집
  - 데이터 전처리
  - 변수 관계 분석
  - LSTM 분석

### (부조장) 이가은
  - 데이터 수집 : 환율 변동에 영향을 주는 국제적 요소에 대한 데이터 수집
  - 변수 관계 분석
  - LSTM 분석 

### 정봉호
  - 데이터 수집 : 환율 변동에 영향을 주는 경제적 요소에 대한 데이터 수집
  - 변수 관계 분석
  - 발표 준비 

### 김주리 
  - 데이터 수집 : 환율 변동에 영향을 주는 정치적 요소에 대한 데이터 수집
  - 변수 관계 분석
  - 발표 준비 

### 박세리 
  - 데이터 수집 : 환율 변동에 영향을 주는 기타적 요소에 대한 데이터 수집
  - 변수 관계 분석
  - 발표 준비

## 데이터 수집 결과 && 변수 정보
[변수정의서](https://drive.google.com/file/d/1Z9AiCpSk4J18TB8ZNDzlfCD1_RycqtTm/view?usp=drive_link)


## 1차 프로젝트 데이터 수집 병합 결과 .Xlsx
[데이터 수집 && 병합 결과](https://docs.google.com/spreadsheets/d/14yVyN6oG2umclZfPiCliIeosqULaqW2F/edit?usp=drive_link&ouid=109969025433946755539&rtpof=true&sd=true) 


## 1차 프로젝트 발표 PPT
[발표PPT](https://drive.google.com/file/d/1U3wUtxpbSYHml1eDXpqzKvp6Hcfzx-Kc/view?usp=drive_link)


## 출처
국제금융센터 https://www.kcif.or.kr/front/board/boardList.do?intSection1=2&intSection2=4&intBoardID=1 <br>
한국은행 경제 통계 시스템 http://ecos.bok.or.kr <br>
IMF  http://www.imf.org/en/data <br>
World Bank https://data.worldbank.org <br>
BIS https://www.bis.org/ <br>
Economic Policy Uncertainty  http://www.policyuncertainty.com/ <br>
Bloomberg, CEIC <br>
산업통상자원부 https://www.motie.go.kr/motie/py/sa/investstatse/investstats.jsp <br>
실시간 환율 데이터,실시간 환율 데이터 Investing.com <br>
금융 데이터 Yahoo Finance <br>
금융, 경제, 정치 등 다양한 분야 Quandl <br>
미국 연방준비은행(Federal Reserve)경제 지표 데이터  FRED <br>
월별 환율 정보 금융투자협회(KOFIA) <br>


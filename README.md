# 데이터 사이언티스트 김서규 포트폴리오 
For English version, please click here: [English Portfolio Intro](https://github.com/sm9801/-Seokyu-Kim-Portfolio-/blob/main/README%20(EN).md)

## 간략 소개
안녕하세요. 현재 화장품 업계에서 데이터 사이언티스트로 재직중인 김서규 입니다.
<br>
University of British Columbia에서 수학을 전공하였으며 확률, 선형 대수학 등의 과정을 거치며 데이터에 접하게 되었습니다.
<br>
이 과정에서 AI, 머신러닝에 관심이 생겼고 통계 분석 및 모델링 능력의 필요성을 느껴 MITx에서 온라인으로 전문 교육을 받았습니다.
<br>
본 교육을 통하여 미국 물가상승율 분석, PCA와 t-SNE 알고리즘 적합성 평가 및 모델 적용한 뇌세포 분류화 연구, 
미국 하와이 Mauna Loa 화산의 이산화탄소 배출양 예측 연구를 진행했습니다.
<br>
현재 화장품 회사에서 KPI 분석 및 의사결정 지원 인공지능 챗봇 개발 업무를 맡고 있습니다.
<br>
앞으로도 지속적으로 성장해서 '견고한 데이터 사이언티스트'가 되고자 합니다.
<br>

## 💼 목차
- [매출 KPI 분석 및 의사결정 지원 AI 챗봇](https://github.com/sm9801/Sales_AI_Agent) (현재 진행중)
  - 화장품 회사의 매출 데이터 기반 KPI 정의하여 대시보드 및 지표 분석 인공지능 챗봇 구축
  - 코호트 분석, 이상 탐지 모델, 진단 분석, 매출 예측(ARIMA/SARIMA), 근본 원인 분석 인공지능 모델, 추천 엔진 설계하여 매출 진단, 예측, 이상 탐지 모델 자동화 및 의사결정 지원
  - 매출, 브랜드, 제품, 시계열, 플랫폼 지표애 대한 구체적인 의사결정 제시
  - 기술 스택: Python, JavaScript, FastAPI, React, OpenAI API, Pandas
  
- [Netflix 콘텐츠 추천 엔진](https://github.com/sm9801/Netflix_Recommendation_Engine)
  - 협업 필터링 기반 넷플릭스 유저 평가 예측
  - 최적 모델: RMSE = 0.46 (K = 3, seed = 1). 기존 baseline 모델 대비 71% 개선
  - 기술 스택: Python, NumPy, Pandas, scikit-learn, Seaborn, Matplotlib, Yellowbrick, Cleanlab

- [사기성 채용 공고 탐지 파이프라인](https://github.com/sm9801/Fraudulent_Job_Postings_Classification)
  - 17,879개의 채용 공고 데이터 feature engineering 및 분류 모델 반복적 개발/​학습
  - Parameter 튜닝 통해 최적 정확도 98.5%, F1 점수 83.2% 달성
  - 중요도 50% 이상인 핵심 피처 4개(회사 프로필, 산업, 요구사항, JD) 발굴하여 채용 공고 사기성 탐지 향상
  - 기술 스택: Python, Snowflake, Dataiku, Random Forest, Gradient Boosting, Decision Tree, XGBoost, SGD

- [뇌세포 주요 유전자 발굴 및 뇌세포 분류](https://github.com/sm9801/Brain_Cell_Identification_via_t-SNE_Feature_Selection)
  - t-SNE, PCA 기반 뇌세포 분류기 구현
  - 45,768개의 유전자로 구성된 뇌세포 2169개 핵심 피처 발굴
  - 주요 뇌세포 3종, 세부 하위 유형 11종 발견하여 모델 정확도 93.1% 달성 (기존 baseline 모델 대비 57% 향상)
  - 기술 스택: Python, NumPy, Jupyter, Seaborn, statsmodels, scikit-learn, Matplotlib, Jupyter, SciPy

- [Mauna Loa 화산 CO<sub>2</sub> 배출량 예측, 미국 물가 상승률 모델링](https://github.com/sm9801/Mauna_Loa_CO2_levels_and_US_Inflation_Rate_Analysis)
  - Mauna Loa 화산 CO<sub>2</sub> 배출량 예측
    - 1958 ~ 2019년 Mauna Loa 화산 CO<sub>2</sub> 데이터 잔차(residual) 분석을 통해 계절별 트렌드와 변동성 분석
    - 결정적 추세 모델 파라미터 예측: Quadratic regression $F_n(t_i)$ ~ $\beta_0 + \beta_1t + \beta_2t^2$
    - 계절 추세 모델 정의: Monthly Average Residuals $P_i = C_i-F_n(t)$
    - 잔차 모델: Remaining Residuals $R_i$
    - 최적 모델: RMSE = 1.143, MAPE = 0.21%의 CO<sub>2</sub>배출량 예측 성능 달성
  - 미국 물가상승률 모델링
    - 2008 ~ 2019 소비자물가지수 (CPI), 손익분기점 (BER), 물가상승률 (IR) 데이터 전처리 및 추가 지수 정의
    - 자기공분산 함수 기반 AR(p) + RBF 구조 학습 및 파라미터 튜닝, 내생적 로그 변환 CPI + 외인성 변환 BER 데이터 활용한 SARIMAX 모델 훈련
    - 최적 모델: RMSE = 0.0527
  - 기술 스택: Python, NumPy, Jupyter, Seaborn, statsmodels, scikit-learn, Matplotlib, Jupyter, SciPy

## 읽어주셔서 감사합니다 :) 
데이터 사이언티스트 김서규
<br>
Email: seokyukim98@gmail.com
<br>
GitHub: [sm9801](https://github.com/sm9801)
<br>

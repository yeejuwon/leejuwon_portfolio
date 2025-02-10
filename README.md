# 이주원_데이터 분석 프로젝트 포트폴리오

데이터를 입체적으로 해석하고, 소통으로 답을 찾는 데이터 분석가를 꿈꾸는 이주원의 데이터 분석 프로젝트 포트폴리오입니다.

## #1 군집 분석을 활용한 최적의 투수 교체 알고리즘 개발
* 기간: 2024년 9월 ~ 2024년 11월
* 프로젝트 진행 인원: 5인
* 프로젝트 소개:
  * 2024학년도 2학기 YSAL 1차 프로젝트
  * MLB 투수의 투구 트래킹 데이터를 군집분석하여 구종별 특성을 도출
  * 특정 구종에 약한 타자를 매칭해 최적의 투수 교체를 제안
* 역할:
  * 팀장으로서 R의 kohonen 라이브러리를 활용해 데이터 클러스터링을 진행
  * Python에서 Ball-Tree 알고리즘을 구현해 최적의 투수 매칭 알고리즘 제작
* 성과: 제작한 알고리즘의 산업 적용 가능성을 인정받아 기업과의 협력 관계 구축
* [웹페이지](https://ysal-bullpen-recommend.vercel.app/)

## #2 서울시 최적의 노인복지주택 입지 선정 프로젝트
* 기간: 2024년 12월 ~ 2025년 1월
* 프로젝트 진행 인원: 4인
* 프로젝트 소개:
    * 2024학년도 2학기 YSAL 내부 Tableau 스터디에서 진행한 파이널 프로젝트
    * 독거노인 가구 증가에 따라 노인들을 위한 공유 주거 형태인 노인복지주택의 입지를 분석하고, Tableau 대시보드를 젲가
    * 서울 열린데이터광장, KOSIS에서 수집하고 제공한 데이터를 바탕으로 분석을 진행
* 역할:
  * Python을 활용해 주거 환경 변수를 통제한 모델을 대상으로 A/B테스트 진행 -> 주요 주거 환경 변수 도출
  * 분석 결과를 바탕으로 노원구 중계동이 최적의 입지라는 인사이트를 도출
  * 독거노인 인구의 지역별 데이터, 인구 증가 추이를 Tableau를 활용해 시각화
* 성과: A/B테스트 설계를 통해 변수 선택의 중요성을 경험하고, 데이터 시각화를 활용한 정책적 의사결정 지원 방법을 익힘
* [결과물(Tableau Public)](https://public.tableau.com/app/profile/.51236637/vizzes)

## #3 인터넷 전문은행은 올바르게 성장하고 있는가?
* 기간: 2024년 4월 ~ 2024년 5월
* 프로젝트 진행 인원: 2인
* 프로젝트 소개:
  * KOSSDA 대학생 공모전 2024 출품작
  * 인터넷 전문은행과 기존 은행의 시장 데이터를 분석해 인터넷 전문은행이 기존 은행을 대체할 수 있을지 분석
* 역할:
  * SQL의 서브쿼리를 활용해 KOSIS애서 제공한 2차 데이터를 전처리
  * Python의 matplotlib 패키지를 활용해 은행 유형별 연체율, 청년층 사용자 비율 등 시각화
* 성과: 시장 데이터를 기반으로 금융 산업의 변화 패턴을 분석하고, 데이터를 기반으로 인사이트를 도출하는 역량 강화

## #4 Monte-Carlo 시뮬레이션을 활용한 타순 시뮬레이션 모델 개발
* 기간: 2024년 11월 ~ 2025년 1월
* 프로젝트 진행 인원: 3인
* 프로젝트 소개:
  * CSAS 2025 Data Challenge 공모전 출품작
  * 타자의 스윙 유형을 분류하고, 이를 기반으로 확률 기반 시뮬레이션 모델을 개발
* 역할:
  * 팀장으로서 Python에서 K-Means 클러스터링을 통해 타자의 스윙 유형 분류
  * Python에서 Monte-Carlo 모델링을 담당
  * R의 Shiny를 활용해 반응형 웹 애플리케이션 구축
* 성과:
* [Github 리포지토리](https://github.com/yeejuwon/mlb_batting_simulator), [Shinyapp](https://yeejuwon.shinyapps.io/mlb_batting_simulator/)

## #5 Logistic Regression Model을 활용한 선수 계약 규모 예측 프로젝트
* 기간: 2024년 9월 ~ 2024년 11월
* 프로젝트 진행 인원: 4인
* 프로젝트 소개:
  * 2024학년도 1학기 YSAL 1차 프로젝트
  * Logistic Regression Model과 FE 추정을 기반으로 선수에게 제시할 적절한 계약 규모를 예측
* 역할:
  * 팀장으로서 Logistic Regression Model을 활용해 은퇴 확률 및 다음해 타격 성적을 예측하는 모델 구축
  * 회귀 계수를 바탕으로 선수의 경력과 성적에 미치는 중요한 요인들을 산출
* 성과: 제작한 모델의 R-Squared 값이 0.58로 유의미한 결과를 나타냄

## #6 EM 알고리즘과 Latent Class를 활용한 선발투수의 이상적 교체 타이밍 분석
* 기간: 2024년 9월 ~ 2024년 11월
* 프로젝트 진행 인원: 6인
* 프로젝트 소개:
  * 2024학년도 1학기 YSAL 2차 프로젝트
  * EM 알고리즘을 활용해 잠재 클래스를 분류하고, 각 클래스 별로 전이행렬을 생성해 이닝별 기대득점을 구함
  * 이를 바탕으로 선발 투수의 교체 타이밍을 제안한 프로젝트
* 역할:
  * 클래스 분류 결과를 바탕으로 각 클래스가 의미하는 바를 해석해 인사이트를 팀에 제공
  * 기대득점 Transition Matrix를 생성
* 성과: RMSE값이 1.3으로 선행 연구에서 기록한 1.7보다 더 정확한 모델을 구축

## #7 Kaggle Competition : Contradictory, My Dear Watson
* 기간: 2024년 9월 ~ 2024년 11월
* 프로젝트 진행 인원: 개인 프로젝트
* 프로젝트 소개: 두 문장의 의미적 관계를 추론하는 언어 모델을 개발하는 Kaggle 대회에 참여
* 역할:
  * 대회에서 주어진 문장의 언어 구성 비율 등을 Python의 matplotlib을 통해 확인
  * 영문과 기타 언어에 별개의 언어모델을 적용하는 앙상블 기법을 차용
* 성과: 리더보드 전체 참가자 34명 중 2위 달성

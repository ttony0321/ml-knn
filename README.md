# ml-knn

> 정규화 전후 KNN 성능 비교
> 제4회 2023 연구개발특구 AI SPARK 챌린지 - 공기압축기 이상 판단



## 프로젝트 개요

- 주제: 정규화 전후 KNN 성능 비교
- 형태: Jupyter Notebook 기반 실험
- 저장소: https://github.com/ttony0321/ml-knn
- 기본 브랜치: main
- 공개 범위: Public

## 주요 기능

- 데이터 EDA
- KNN 분류
- 정규화 전후 결과 비교

## 기술 스택

- Python
- Jupyter Notebook

## 프로젝트 구조

- `KNN_nor.ipynb`
- `README.md`
- `air_EDA.ipynb`
- `knn.ipynb`

## 실행 방법

- Jupyter 실행 환경 구성
- 데이터 경로 설정
- 실행 순서: KNN_nor.ipynb → air_EDA.ipynb → knn.ipynb

## 핵심 구현

- 분석 과정과 모델 실험을 Notebook 단위로 분리
- 데이터 탐색부터 결과 확인까지의 흐름 구성
- AutoML Pycaret 사용하여 학습 이후에 따로 knn_nor pyod의 knn 라이브러리 사용 normalize후 파라미터 설정으로 성능 향상0.93->0.95

## 개선 과제

- 의존성 버전 고정
- 환경변수 기반 경로·설정 관리
- 대표 평가 지표와 결과 그래프 문서화


# House_Prices_EDA

데이터 세트 설명

파일 설명

train.csv - 훈련 세트

test.csv - 테스트 세트

data_description.txt - 원래 Dean De Cock이 준비했지만 여기에 사용된 열 이름과 일치하도록 약간 편집한 각 열의 전체 설명

sample_submission.csv - 판매 연도 및 월, 부지 면적 및 침실 수에 대한 선형 회귀의 벤치마크 제출

데이터 필드

다음은 데이터 설명 파일에서 찾을 수 있는 내용의 간략한 버전입니다.

SalePrice - 부동산의 판매 가격(달러)입니다. 이것은 예측하려는 대상 변수입니다.

MSSubClass : 건물 클래스

MSZoning : 일반적인 구역 분류

LotFrontage : 건물에 연결된 거리의 선형 피트

LotArea : 부지 크기(제곱피트)

Street : 도로 접근 유형

Alley : 골목 진입 방식

LotShape : 속성의 일반적인 모양

LandContour : 속성의 평탄도

유틸리티 : 사용 가능한 유틸리티 유형

LotConfig : 로트 구성

LandSlope : 속성의 기울기

인근 지역 : Ames 시 경계 내의 물리적 위치

조건 1 : 간선도로 또는 철도와 인접

조건 2 : 주요 도로 또는 철도와의 근접성(두 번째가 있는 경우)

BldgType : 주거형태

HouseStyle : 주거 형태

OverallQual : 전반적인 재료 및 마감 품질

OverallCond : 전반적인 상태 등급

YearBuilt : 원래 건설 날짜

YearRemodAdd : 리모델링 날짜

RoofStyle : 지붕의 종류

RoofMatl : 지붕재

Exterior1st : 주택 외부 피복재

Exterior2nd : 주택 외부 피복재(재료가 둘 이상인 경우)

MasVnrType : 석조 베니어 유형

MasVnrArea : 벽돌 베니어 영역(제곱피트)

ExterQual : 외장재 품질

ExterCond : 외부 자재의 현재 상태

기초 : 기초의 종류

BsmtQual : 지하실의 높이

BsmtCond : 지하실의 일반적인 상태

BsmtExposure : 파업 또는 정원 수준 지하실 벽

BsmtFinType1 : 지하 마감면의 품질

BsmtFinSF1 : 유형 1 마감 평방 피트

BsmtFinType2 : 두 번째 완성된 영역의 품질(있는 경우)

BsmtFinSF2 : 유형 2 마감 평방 피트

BsmtUnfSF : 지하 공간의 미완성 평방피트

TotalBsmtSF : 지하 면적의 총 평방 피트

난방 : 난방의 종류

HeatingQC : 난방 품질 및 상태

CentralAir : 중앙 에어컨

전기 : 전기시스템

1stFlrSF : 1층 평방 피트

2ndFlrSF : 2층 평방 피트

LowQualFinSF : 저품질 마감 평방 피트(모든 층)

GrLivArea : 지상(지상) 거실 면적 평방피트

BsmtFullBath : 지하 전체 욕실

BsmtHalfBath : 지하 반 욕실

FullBath : 지상 위의 전체 욕실

HalfBath : 지상 반욕

침실 : 지하층 위의 침실 수

주방 : 주방 개수

KitchenQual : 주방 품질

TotRmsAbvGrd : 지상 위의 총 객실 수(욕실 제외)

기능 : 홈 기능 등급

벽난로 : 벽난로 수

FireplaceQu : 벽난로 품질

GarageType : 차고 위치

GarageYrBlt : 차고가 건설된 연도

GarageFinish : 차고 내부 마감

GarageCars : 차량 수용 가능 차고의 크기

GarageArea : 평방 피트 단위의 차고 크기

GarageQual : 차고 품질

GarageCond : 차고 조건

PavedDrive : 포장된 진입로

WoodDeckSF : 목재 데크 면적(제곱피트)

OpenPorchSF : 평방 피트 단위의 열린 베란다 영역

EnclosedPorch : 평방피트 단위의 닫힌 현관 면적

3SsnPorch : 제곱피트의 3계절 베란다 면적

ScreenPorch : 스크린 베란다 면적(제곱피트)

PoolArea : 풀 면적(평방피트)

PoolQC : 수영장 품질

울타리 : 울타리 품질

MiscFeature : 다른 범주에서 다루지 않는 기타 기능

MiscVal : 기타 기능의 $Value

YrSold : 판매 연도

SaleType : 판매 유형

SaleCondition : 판매 조건

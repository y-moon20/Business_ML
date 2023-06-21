# Business_ML
### 2023-1 SMWU Graduate School BA

- 2023.03.08 ~ 2023.06.07
- Final project : 2023.6.21

## 기업 리뷰 데이터를 이용한 BERTopic (-기업 추천 의사에 영향을 미치는 요인-)
( google Colab/ python 3.10ver/ BERTopin 0.15ver)
- 802개의 기업 70263건의 리뷰 데이터를 활용.

### 1. LDA, CTM
- LDA Topic Modeling과 Combined Topic Modeling을 이용하여 기업에 대한 장점과 단점 텍스트에 대해 토픽모델링 시도
> 토픽모델링은 되나, 이를 통한 머신러닝 분류모델 학습이 원활하지 않아서 사용하지 않음.

### 2. BERTopic
- 구글 BERT기반 임베딩과 클래스 기반의 TF-IDF를 활용한 토픽모델링
- 기존에 많이 사용되는 LDA의 단점인 문맥을 파악하지 못하는 점을 보완해줄 수 있음.

### 3. BERTopic을 이용한 머신러닝 분류모델 및 회귀분석
- DT, GBM, LGBM GB등 다양한 머신러닝의 분류모델을 사용하여 추천여부를 분류해보고, 추천여부를 분류하는 데에 영향을 미치는 feature importance를 확인하고자 하였으나 저조한 학습 정확도로 인해 보류.
- 최종적으로 장점과 단점리뷰의 토픽을 활용하여 추천여부를 종속변수로 하는 로짓 회귀분석을 시행함.
  


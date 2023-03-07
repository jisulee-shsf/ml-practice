####
## Machine learning / NumPy & pandas
####
#### ► [01_ml_numpy1_230307]
- Fashion MNIST dataset을 이용해, 10개의 의류 class에 속할 확률을 예측하는 모델 생성
- train / test x의 픽셀값 범위를 0-1 사이 값으로 scaling하여 예측 성능 변화 확인
- label의 one-hot encoding 여부에 따라, categorical crossentropy loss function 적용 실습
- label 값이 10개의 class 중에 속할 확률을 나타냄에 따라, 총합이 1인 softmax activation function 적용 실습
- 한 장의 2차원 배열 이미지의 경우, expand_dims()를 통해 3차원 배열로 변환 후 fit / predict() 진행 필요 확인
####

# dacon_HAI

대회에서 요구한 tapr 맞추기가 넘 어려워서 포기한 대회입니다

deepant, 1d cnn, lstm+vae+gan (학습 실패), lstm(3-layered), xgboost, lightgbm 등으로 t까지의 time window 를 기반으로 t+1일떄 각 process 별 예측값을 구하도록 하였습니다

추가적으로 각 process regression 모델이 뱉어주는 error 를 sum하여 계산하거나, Decision tree와 같은 모델로 특정 process의 오류를 feature로 추가 모델을 구성해보고 싶었으나 잘 되지 않았습니다. 

target loss, target accuracy 같은 걸 별도 세팅해서 학습할 수 있었으면 더 좋은 성적이 나오지 않았나 싶습니다.


dacon 에 수상작이 공개되면 분석하여 업로드 할 예정입니다.

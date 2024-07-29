# 🚀Spaceship-Titanic
## 대회 소개
PassengerId, HomePlanet, Cabin 등 승객들의 다양한 정보를 활용하여 승객이 다른 차원으로 이동하였는지 예측하는 Kaggle의 데이터 분석 경진대회입니다.
(링크 : [Spaceship Titanic | Kaggle](https://www.kaggle.com/competitions/spaceship-titanic/))

## 결과 및 순위
![](https://velog.velcdn.com/images/pompom_33/post/170a9ce2-b11a-4a32-a468-a492aef0243a/image.png)
제가 제출한 모델은 **0.80173**의 예측 정확도를 가졌습니다.

## 모델에 대한 간단한 설명
<img width="409" alt="image" src="https://github.com/user-attachments/assets/9a86bb41-1d5c-403e-bd4f-47bd2f10171c"> </br>
Decision Tree Classifier, Random Forest, Boosting Tree(lightGBM)을 활용하여 모델을 형성하였고,
Stratified K Fold 교차검정을 진행하였습니다.
최종 채택한 모델은 **Grid Search로 찾은 Random Forest 모델**입니다.

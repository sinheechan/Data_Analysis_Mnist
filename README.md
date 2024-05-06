# Data_Analysis_Mnist

Kaggle 데이터 분석 과정을 담은 내용입니다.

모델에 대한 학습 과정은 Mnist_test.ipynb 파일에 작성하였으며

실제 데이터 분석 및 모델 구축 과정은 Mnist_model.ipynb 파일을 참고 부탁드립니다 (_ _)

<br/>

## WorkFlow Summary

[ Mnist_test.ipynb ]

- cross_val_score : SGDClassifier 교차검증을 통한 모델 성능 평가
- F1 Score, 정밀도, 재현율에 대한 학습 및 최적 모델에 대한 기준 정의
- roc_curve를 통한 임곗값의 변화에 따른 TPR, FPR 을 계산
- SGD와 RandomForest 모델 성능 비교
- 다중 클래스 분류 모델 교차 검증 이론 적용 및 표준화 스케일링을 통한 정확도 개선
- 오차행렬 시각화를 통한 Error 행렬 분석 및 개별 오류 검출 후 모델 선정

[ Mnist_model.ipynb ]

- k-NN 모델을 활용한 데이터 모델링 : 정확도 96%
- GridSearchCV 기법을 활용한 최적 하이퍼파라미터 도출 및 성능 향상
- 테스트 셋에 대한 정확도 : 정확도 97% 

# kwix_Illegal-Parking-Detection-Model

예측 모델 학습에 사용된 데이터셋은 AI-Hub(한국지능정보사회진흥원이 운영하는 AI 통합 플랫폼)의 ‘차로 위반 영상 데이터’의 일부입니다.
학습 과정에서는 황색 차선, 백색 차선, 청색 차선과 갓길 차선 중 주정차 위반 여부를 학습하기 위해 갓길 차선 데이터만 활용하였으며, 학습 환경에 맞게 전체 165,726장의 이미지 중 5,324장의 이미지를 학습에 활용하였습니다. 아래는 데이터셋의 구분과 해당 분류에 따른 차량 사진 수, 위반 여부 수, 그리고 총 객체 수를 보여준 표 입니다.
![image](https://github.com/user-attachments/assets/c858b2e9-bdaa-452b-a36e-88baa56fa351)

![image](https://github.com/user-attachments/assets/8d211fa0-9ff3-40fe-94c5-e0473e0a5336)


![image](https://github.com/user-attachments/assets/8a46059b-0819-45e9-9d00-ea1f56aa7004)

학습 환경에 맞추다 보니 학습 데이터의 비율이 적어 높은 성능을 보이지는 못했습니다.
차선은 각도에 따라 형태가 다양하게 변하고 이미지 내에서 차량에 가려진 모습이 많아 학습에 어려움을 겪었습니다.

# 주제 : YOLOv5를 활용한 해양 쓰레기 분류 및 분석

# 주제 선정 이유

해양 쓰레기는 전 세계적으로 심각한 환경 문제로 대두되고 있습니다. 매년 수백만 톤의 쓰레기가 바다로 유입되어 해양 생태계를 위협하고, 바다 생물의 생존에 치명적인 영향을 미칩니다. 이 문제를 해결하기 위해 YOLOv5를 활용하여 해양 쓰레기의 종류와 분포를 분석하여 환경 문제 해결의 도움을 주고 싶습니다.
![다운로드](https://github.com/user-attachments/assets/4b1273d7-1e9e-40dd-bf00-eca8d0720773)
![article_1662545819](https://github.com/user-attachments/assets/3db79084-b4f9-4b6d-991e-20135bca1de0)


# 영상 활용 방법

인공지능 영상 학습을 위해 영상을 다운받았습니다.
https://www.youtube.com/watch?v=H2ZHC2a-Q0A&t=46s (뉴스)

YOLOv5에서 영상을 학습하기 위해 Clipchamp를 사용하여 수정하였습니다.
![image](https://github.com/user-attachments/assets/c12824a1-2c2d-45cd-8149-5e6c7c4ea8f0)

# 학습 데이터 추출

DarkLabel을 활용하여 학습 시키려는 해양 쓰레기 종류를 각각에 맞게 드래그합니다. 
![image](https://github.com/user-attachments/assets/2db9c282-6bdd-4f73-b1d5-72085f06ca4b)

# 학습 코드

Google Colaboratory를 활용하여 Python으로 학습을 합니다.

1. 구글 드라이브 연동
![image](https://github.com/user-attachments/assets/88eca8b2-8016-415c-91fa-d013b89aa8e2)

2. YOLOv5 설치
![image](https://github.com/user-attachments/assets/39fd2868-221a-457d-bcf4-6ecef16de248)

3. 이미지 파일 관리
![image](https://github.com/user-attachments/assets/631a065a-9ba5-4b2a-aae7-984c1d287104)

4. 검증 데이터 생성
![image](https://github.com/user-attachments/assets/d8357e05-8c4c-41c3-bfd5-3720bc6d72b5)
![image](https://github.com/user-attachments/assets/66b293df-d0d4-4966-8a79-41dffb6a07e8)

5. YOLOv5 학습 시작
![image](https://github.com/user-attachments/assets/7eb20e07-19b0-4dc4-b849-acf10af8aed1)
![image](https://github.com/user-attachments/assets/0d0d3243-a4cb-4193-a8b0-535cb6de6769)
![image](https://github.com/user-attachments/assets/78fa80d8-1b71-498c-b3fd-e9933982aad5)
![image](https://github.com/user-attachments/assets/6e05b75d-ade4-4755-a274-b12cac29da17)
![image](https://github.com/user-attachments/assets/079da06d-191b-43f8-9f45-8d4c6151396a)

# YOLOv5 모델 학습 결과 검증

confusion_matrix
![image](https://github.com/user-attachments/assets/9acf15d7-6acd-4a1c-85bc-beb84dbc3c51)

F1_curve
![image](https://github.com/user-attachments/assets/e4e8fc1e-e37b-426a-8ef1-c8417caf4375)

P_curve
![image](https://github.com/user-attachments/assets/f4f61341-c9f2-4f20-b47c-eb7d9afdaa10)

R_curve
![image](https://github.com/user-attachments/assets/c8bf4752-bd01-474c-898e-861f591ad58a)

result
![image](https://github.com/user-attachments/assets/8e574eb3-9f54-4598-94c9-ded8c5537f6b)


train_batch
![image](https://github.com/user-attachments/assets/98e61455-6922-472c-a86c-e66f25e081f3)

val_batch
![image](https://github.com/user-attachments/assets/b3a248d9-8a4e-45bf-bf31-791ef37a0081)

# 잭슨 나노 비디오

https://github.com/user-attachments/assets/4e5d17fc-bc18-445c-8489-d90912b811cb

https://github.com/user-attachments/assets/9b717ee4-b49b-4b94-aa4c-c9d03306fe66

https://github.com/user-attachments/assets/1b283414-ca1e-4bd3-80d6-949117f3dc97

https://github.com/user-attachments/assets/049e891a-4c41-4e7a-93e5-a9291670e3ab

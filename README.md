# Apple_image_classification
• 사과 이미지를 통해 사과 품종을 찾는 Image Classification
  - 평가지표: F1 Score
  - input: 512*512 pixel image data(.jpg)
  - target: 4개의 사과 종(HJ, HR, SG, AR)
  
 <데이터 구조>
 
   DATA/ 

   |__ train/  # 학습 데이터

   |     |─xxx.jpg

   |     |─yyy.jpg

   |   └─zzz.jpg

   |__ test/  # 추론 데이터

   |     |─xxx.jpg

   |     |─yyy.jpg

   |   └─zzz.jpg

   |─ train.csv

   |__ test.csv 



- train.csv : 총 10,000개의 사과 이미지 파일명과 라벨

- test.csv  : 총 5,000개의 사과 이미지 파일명

- sample_submission.csv : 제출 양식 csv 파일

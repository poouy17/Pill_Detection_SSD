# Pill_Detection

Using SSD Model to detect pill in picture and crop that to use Text Detection Model's Input
-Inha University Project

### SSD Model 학습

  - 2000장 가량의 알약 사진 Labeling
  - SSD Model의 Train.py를 이용해 학습
  - 가장 성능이 좋은 Model의 .pb File 저장

### SSD Model을 이용하여 사진에서 Pill Detection 후, Crop
  - Using_finetuned_model_to_detect_pill_text.ipynb

### Crop된 Image 전처리
  - Crop_images_preprocessing.ipynb
  - Text recognition Model의 Input으로 들어갈 Crop Image를 전처리하여 성능 향상
  - Text_recognition Model은 CRNN 또는 CRNN + Craft 사용할 예정



## Todos

 - Flask Server에 Model 올리기
 - Flask Server와 Android App 연동
 - Android App와 Firebase 연동


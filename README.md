# 2021 데이터 청년 캠퍼스 - 서울여자대학교

> 프로젝트 기한 : 07/26/21 - 08/31/21

> 프로젝트 기업 : [에이아이닷엠](http://aimlabs.ai/)

> 프로젝트 NOTION link : [2021데이터청년캠퍼스](https://www.notion.so/pyzoo/5583e1ae7f59444580b0536584d9fc0c?v=fec0a5b9124644a4a5053645e1509b58)
- - -

## model folder
>**oneclick_code.ipynb**
  + <generate face - face shifter - GPEN> 과정을 모두 담은 코드
  - 한 번 클릭하면 모두 실행
  
>**generateface_with_styleGAN.ipynb**
  - styleGAN2를 이용하여 가상 인물을 생성

>**face_swapping.ipynb**
  - face swapping을 이용하여 생성 얼굴을 상품 이미지 속 얼굴로 대체

>**face_shifter.ipynb**
  - face shifter를 이용하여 생성 얼굴을 상품 이미지 속 얼굴로 대체

>**GPEN.ipynb**
  - GPEN을 이용하여 대체한 이미지를 고화질로 변경

>**facedetection_with_v2.ipynb**
  - mobilenet_v2를 이용하여 사측으로부터 제공받은 데이터를 얼굴 유무로 분류
  
>**styleCLIP.ipynb**
  - styleCLIP을 이용하여 얼굴 변형

>**beautyGAN.ipynb**
  - beautyGAN을 이용하여 얼굴 변형

  
## data folder
>>**img_data.csv**
  - 사측으로부터 제공받은 raw data
>>**img_data_url.csv**
  - facedetection_with_v2.ipynb에서 사용한 데이터

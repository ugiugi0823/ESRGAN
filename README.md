# ESRGAN

![ESRGAN](https://user-images.githubusercontent.com/106899647/219962040-806672f5-d6cd-4e51-ab51-7ea5dc50fcdc.png)


## 설명
ESRGAN(Enhanced Super-Resolution Generative Adversarial Networks)은 딥 러닝을 사용하여 저해상도 입력에서 고해상도 이미지를 생성하는 이미지 초해상도 알고리즘입니다. 2018년 Xintao Wang, Ke Yu, Shixiang Wu, Jinjin Gu, Yihao Liu, Chao Dong, Chen Change Loy, Xiaoou Tang이 "ESRGAN: Enhanced Super-Resolution Generative Adversarial Networks" 논문에서 처음 소개했습니다.

ESRGAN은 GAN(Generative Adversarial Network)이라는 신경망 유형을 기반으로 하며 생성기와 판별기의 두 가지 신경망으로 구성됩니다. 생성기는 저해상도 입력에서 고해상도 이미지를 생성하는 방법을 학습하는 반면 판별자는 실제 고해상도 이미지와 생성기가 생성한 이미지를 구별하는 방법을 학습합니다. 두 네트워크는 생성자가 판별자를 속이는 이미지를 생성하는 방법을 배우는 적대적 훈련이라는 프로세스에서 함께 훈련됩니다.

ESRGAN은 쌍입방 보간법과 같은 이전의 초고해상도 방법보다 개선된 것입니다. 더 자세하고 더 적은 아티팩트로 이미지를 생성할 수 있기 때문입니다. 알고리즘은 텍스처 및 색상과 같은 높은 수준의 지각 기능 측면에서 생성된 이미지와 대상 이미지 간의 차이를 측정하는 지각 손실 함수를 통합하여 이를 달성합니다. 또한 ESRGAN은 새로운 RIR(Residual-in-Residual) 네트워크 아키텍처를 사용하여 가장자리가 더 선명하고 세부적인 이미지를 생성할 수 있습니다.





## 결과







![esrgan](https://user-images.githubusercontent.com/106899647/219944423-06d1e7dc-932a-4ba5-b0b9-f15720380fa6.jpg)


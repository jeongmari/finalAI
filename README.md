# 인공지능 기말 과제_2조
성별 및 감정 분류 AI

# 프로젝트 소개
1.[설명](#p1)

2.[설치](#p2)

3.[사용법](#p3)

4.[데이터셋](#p4)

![happy](https://user-images.githubusercontent.com/96713929/173236620-2ed47079-dbc6-4c58-b9a8-a8da58473cf9.png)
![surprised](https://user-images.githubusercontent.com/96713929/173236654-bfdcd666-5484-4c91-8cd2-4ea0be080dcf.png)

<a id="p1"></a> 
# 설명:
 해당 프로젝트는 “사람의 얼굴에서 성별과 감정을 분류해낼 수 있는 AI”로 노트북에 내장된 카메라나 웹캠을 통해 실시간으로 얼굴을 인식해 성별과 감정을 분류할 수 있다.
 우리 인간의 얼굴은 복합적인 감정을 가지고 있으므로 정확한 감정 분류를 위해서는 우리가 가지고 있는 이러한 감정의 확률을 보여주어야 한다.

 ## 감정 인식이 의미하는 것은 무엇일까?

 감정 인식은 프로그램이 고급 이미지 처리를 사용하여 사람 얼굴의 감정을 "읽을" 수 있도록 하는 소프트웨어에서 사용되는 기술이다. 많은 기업들이 사람의 얼굴을 촬영한 이미지나 동영상을 바탕으로 그 사람이 느끼는 감정과 그 사람이 보여주는 감정에 대해 더 많이 이해하기 위해 지난 10년 동안 등장한 이미지 처리 기술과 정교한 알고리즘을 결합하는 실험을 진행하고 있다. 그만큼 인간의 표정은 생각보다 훨씬 중요한  역할을 하고 있다.
 인간과 원활하게 상호작용하는 로봇을 만들기 위해서는 기본적으로 사람의 성별이나 나이를 파악하고 표정을 보고 감정을 파악할 수 있어야 한다. 

<a id="p2"></a> 
# 설치:
required libraries.txt를 사용하여 종속성을 설치한다.

pip install -r (모듈 이름).txt

<a id="p3"></a> 
# 사용법:
주피터 open-cv 개발환경에서 실행: finalSuccess.ipynb

<a id="p4"></a> 
# 데이터 세트:
얼굴 감지 모델 haarcascade_frontalface_default.xml,
감정 모델 _mini_XCEPTION.102-0.66.hdf5

> 참고 코드
Adrian Rosebrock의 resource
[this](https://www.kaggle.com/c/3364/download-all)

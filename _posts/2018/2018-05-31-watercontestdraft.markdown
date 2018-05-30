---
layout: "post"
title: "watercontestdraft"
date: "2018-05-31 07:12"
---

[모집요강](https://www.kwater.or.kr/news/sub02/bigdata/guidPage.do?s_mid=1792)

## 들어가기 전에...
- 수요예측모델링은 **파생변수**의 싸움이라고 합니다.
- 누가 더 창의적인 파생변수를 만드느냐 가 관건이라고 합니다.
- 좋은 파생 변수를 만들기 위해 노력해봅시다.


## 과제목표
추진배경, 필요성, 목적 등  [논문전문링크](https://www.dropbox.com/s/usksz5ry5bflfoz/%EB%AC%BC%EC%88%98%EC%9A%94%20%EC%98%88%EC%B8%A1%ED%95%98%EB%8A%94%20%EB%B0%A9%EB%B2%95%EC%97%90%20%EB%8C%80%ED%95%B4%20%EC%84%A4%EB%AA%85%ED%95%9C%20%EC%A2%8B%EC%9D%80%20%EA%B8%80.pdf?dl=0)

우리의 목표는 물수요를 예측하여 물을 효율적으로 공급하는 것이다. 특히 물 사용량을 산정하여, 제반 상수도 계획과 설계 등에 활용하면 좋을 것 같습니다.

- 아래는 모집 요강에 적힌 설명입니다. 이 내용도 참고하시면 좋겠습니다.
![Imgur](https://i.imgur.com/VrdnMUN.png)

- 아래 내용도 참고해서 과제목표 작성해주세요.
![Imgur](https://i.imgur.com/zfLkzHl.png)

## 주요내용
과제내용 요약설명

## 분석기법
**[포함해야할 사항]**

1. **구체적 명시 (분석기법 기초설명 포함)**
2. **활용 예정인 데이터,**
    +  [데이터 변수에 대한 자료](https://www.kwater.or.kr/gov3/sub03/annoView.do?seq=2308&s_mid=1664)
    +  ![데이터 예시](https://i.imgur.com/tHioazZ.png)
    + 이 중 적절해보이는 변수 10여개 정도 사용하면 될 것 같다.
    + **스마트 미터링 자료**도 필요하면 좋겠다. 실시간 물 사용량 파악을 위해 필요하다고 봄.
3. **분석도구**
    + Open Source R
4. **분석기법** **등**
    + randomforset, 인공신경망모형, 요인분석(파생변수 생성을 위한) 선형회귀분석, 시계열모형 등을 사용할 수 있다.
    + 전력수요예측 모델 분석법에서 사용한 방법들을 차용하여 물수요예측에 반영해보겠다.





- 보통 물수요예측에 포함하는 변수는 아래와 같다 :
    - **수운영 시스템에서 수요변동**
    - **기상여건**
    - **계절별 요인**



## 기대효과

기대효과는 아래 내용을 참고하여 적으면 될 것 같습니다.  [논문전문링크](https://www.dropbox.com/s/usksz5ry5bflfoz/%EB%AC%BC%EC%88%98%EC%9A%94%20%EC%98%88%EC%B8%A1%ED%95%98%EB%8A%94%20%EB%B0%A9%EB%B2%95%EC%97%90%20%EB%8C%80%ED%95%B4%20%EC%84%A4%EB%AA%85%ED%95%9C%20%EC%A2%8B%EC%9D%80%20%EA%B8%80.pdf?dl=0)
![Imgur](https://i.imgur.com/bAdY1kN.png)


## 참고할만한 논문 및 링크..
- 신경망 모형을 통해 예측했다고 함. 무슨 내용인지는 모르겠으나 나중을 위해 일단 모아둠. [링크](https://patents.google.com/patent/KR100540009B1/ko)
- 물수요 예측에 대한 아이디어 얻기 좋음. 연구의 필요성, 기대효과에 대한 설명이 있음. 계획서 쓸 때 여기 참고할것. [링크](https://patents.google.com/patent/KR101139161B1/ko)

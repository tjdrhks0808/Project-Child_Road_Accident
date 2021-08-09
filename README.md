# Project-Child_Road_Accident
오산시 어린이 교통사고 위험 지역 도출 분석 과제 - hosted by LH

링크: https://compas.lh.or.kr/subj/past/info?subjNo=SBJ_2012_001


## 1. 과제 개요
  * 분석 목적

  오산시는 어린이 교통사고 예방을 위해 다양한 데이터를 융합하고 활용하여 교통사고 예방을 위한 주정차 단속 강화, 교통 안전시설물 및 AI기반 스마트시티 솔루션 설치 등 어린이 보호를 위한 다양한 정책을 수립하여 추진 할 계획입니다.


  * 해결 과제

    1. 어린이 보호구역 외 어린이 교통사고 위험지역 20개소 제시
    2. 기존 어린이 보호구역 중 교통안전시설물* 우선 설치 지역 20개소 제시
        - 교통안전시설물 : 과속단속카메라, 교통안전표지판, 미끄럼방지시설(적색포장), 과속방지턱, 가드휀스 등
    3. 분석 조건
      - 위험지역 범위설정은 중심점으로부터 반경 50m를 기준으로 함.(분석결과에 따라 제시 가능)
      - 사용자가 자유롭게 필요 데이터를 발굴하여 사용 가능하나 최종 결과파일 제출 시 데이터 출처와 사용한 데이터도 함께 제출
      - 외부 데이터는 법적인 제약이 없는 경우에만 허용되며 크롤링을 통해 데이터를 생산 한 경우 크롤링 코드도 함께 제출



## 2. 개요

  ![image](https://user-images.githubusercontent.com/80023275/128469163-36b340a7-d838-4ec1-8933-3ddc56c3ff22.png)
  

  ![image](https://user-images.githubusercontent.com/80023275/128469201-f7f05c98-24a1-4b99-854b-60e75b1880f9.png)
  ![image](https://user-images.githubusercontent.com/80023275/128469258-bc3f14de-9772-47cb-b8c1-1b27697a8c6a.png)
  
  
  
  도로교통공단의 교통사고분석시스템(TASS) 집계 결과, 최근 3년(2017-2019년) 전국에서 발생한 어린이 교통사고는 3만 2023건이다.
  
  현재 어린이 교통사고에 대한 경각심이 계속해서 높아지고 있지만, 교통사고는 증가하는 추세를 보이고 스쿨존 내 어린이 교통사고는 매년 400건 이상을 유지하고 있다.
  
  
  ![image](https://user-images.githubusercontent.com/80023275/128469596-1715d160-7c60-47f2-98f5-4e584882a7a6.png)


  분석의 대상이 되는 오산시에서는 교통약자부문 교통안전지수가 전국 평균에 비해 낮은 것을 알 수 있다.
  
  **따라서 우리는 오산시의 공간적 특성을 가진 데이터와 교통관련 데이터를 활용하여 어린이 교통사고 위험지역을 도출하고, 기존 어린이 보호구역에 대해 교통사고 감소를 극대화할 수 있는 시설물을 재정비할 필요가 있다.**


## 3. 데이터 분석

※분석보고서 참고

# Phantom
**파노라마팬텀을 이용한 파노라마방사선장비평가소프트웨어**
=======  


해당 소프트웨어는 서울대학교 공대-치대 학제간 융합 연구를 통해 이루어 졌습니다.  


>>- 공과대학 컴퓨터공학부 분산시스템 연구실   **염헌영 교수님**
>>- 치의학대학원 영상치의학교실              **이삼선 교수님**  



**볼 팬텀**은 파노라마방사선장비의 상층 형태와 크기를 평가하기 위해 제작되었습니다.  
Phantom소프트웨어는 볼 팬텀으로 획득한 영상을 정확하고 편리하게 평가하기 위한 프로그램입니다. 

Phantom소프트웨어에서 구현된 기능과 그 사용법에 관련된 설명은 다음과 같습니다.  

- [분석영상선택하기](#첫화면home)  
- [분석결과](#결과Result)
  - [매칭정보확인](#매칭정보)

-------
1. ## 첫화면(home)
-------

![home.jpg](./image/home.jpg)  

**파노라마방사선장비평가 소프트웨어의 첫화면입니다.**  
```
    소프트웨어가 제공하는 기능에 관한 간단한 설명과 함께, 분석하려는 영상을 선택할 수 있습니다.  
```

**1-1. 단일 분석 영상의 선택**  
![single_select.jpg](/image/single_select.JPG)  
영상이 선택된 후 **분석할 영역을 선택**하여야 합니다.  
```
    영상분석 후 악골도면과의 매칭작업을 위해 분석영역 지정이 필요합니다.  
    영역지정이 제대로 되지 않은 경우에, **분석 결과에 오차**가 발생할 수 있습니다.  
```

![single_select1.jpg](./image/single_select1.jpg)
![single_select2.jpg](./image/single_select2.jpg)  


분석영역을 선택한 후에 **[선택 영역 분석 시작]**버튼을 누르면 분석을 시작합니다.  
```
    분석 영역을 잘못 지정한 경우에 [영역 재선택] 버튼을 통해, 영역 재지정을 할 수 있습니다.  
    분석 영역 지정이 필요하지 않은 사진의 경우, 영역지정 없이 분석을 시작할 수 있습니다.  
```


-------
2. ## 결과(Result)  
-------
  - ## 매칭정보  
  ![matching_confirm1.jpg](./image/matching_confirm1.jpg)  
  분석이 완료되면, 전체적인 분석결과를 종합해서 보여줍니다. 하지만 그 전에 분석영상과 도면 간의 잘못된 매칭영역이 있는 지를 우선 표현합니다. **원본영상 보기 모드**의 선택을 통해 다양한 방식의 매칭정보를 확인할 수 있습니다.  
  

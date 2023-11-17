## 🔥 우리 동네산불지키미 🔥
팀원 : 박은주, 여채윤, 이의진

### ❓ 연구 개발 배경 및 목적 ❓
최근 들어 산불 발생이 심각한 사회 문제로 떠오르고 있으나, 산불에 대한 정보는 여러 플랫폼에 분산되어있고 산불에 대비하기 위한 중요한 정보가 부족한 현황이다. 
본 작품은 강원도 지역의 기상, 날짜 등 여러가지 요인을 고려해 산불발생시 산불 피해 면적을 예측한다. 이뿐만 아니라 산불위험지수와 실시간 기상정보와 같의 산의 전반적인 정보들과 인근 소방서 위치, 과거 산불 통계 등 산불에 대한 정보를 제공한다.
현재 세계적으로 규모가 큰 산불이 빈번하게 발생하고 있는 상황 속에서 산불에 대한 예측과 대비가 중요한 이슈로 떠오르고 있다. 하지만 현재 산불위험지수는 제공하고 있으나 산불이 발생할 시 예상되는 산림의 피해면적을 제공하는 시스템은 존재하지 않다. 
따라서 신속한 산불대응을 위해 산림피해면적을 예측하여 제공하고, 이뿐만 아니라 산림에 대한 정확한 정보를 전달하는 플랫폼을 개발했다. 


### 🖥️ 웹 화면 🖥️

1. 메인화면
    - 웹페이지의 첫 화면으로 산 검색 창 구현
    - 상단 메뉴바를 통해 원하는 서비스를 클릭하면 바로 이동할 수 있도록 구현
    
    ![Untitled (6)](https://github.com/pej0918/2022_Hanium_Project/assets/79118751/075455e3-0ce8-43a8-b658-62fbe8cdf338)

    
2.  산 정보 전달 화면
    - 산 위치를 보여주는 대시보드 구현
        - 데이터 : 카카오 지도  API
    - 날씨 정보와 특정 산에 대한 산불위험지수 보여주는 대시보드 구현
        - 데이터: 산불위험지수 API ( 크롤링하여 DB에 저장)
        - 산악기상관측시스템 ( 크롤링하여 DB에 저장)
    
    ![Untitled (7)](https://github.com/pej0918/2022_Hanium_Project/assets/79118751/ffb7fa18-2972-4dbf-ab33-2cee40d4b1cc)
    

1. 산불 발생 피해 정보 제공 화면
    - 예상 피해 면적을 나타내는 대시보드 구현
        - 데이터 : 과거 산불 데이터(DB에 저장)
        - 알고리즘 : Ridge regression
    - 산불 피해 예방방법에 대한 안내 대시보드 구현
    
    ![Untitled (8)](https://github.com/pej0918/2022_Hanium_Project/assets/79118751/07d56a20-4a46-4f5e-a0c6-e6331cdf598f)



    ![Untitled (9)](https://github.com/pej0918/2022_Hanium_Project/assets/79118751/2789e703-370a-4bc6-ada9-587703922752)

    
3.  산불 위험 지역 정보 제공 화면
    - 강원도의 모든 지역에 대한 산불 위험지수를 보여주는 대시보드 구현
        - 데이터 : 산불위험지수 API (크롤링하여 DB에 저장)
    - 산불위험지수 개념 설명 대시보드를 구현
    - 원하는 지역의 산불위험지수를 볼 수 있도록 검색창 구현
    
    ![Untitled (10)](https://github.com/pej0918/2022_Hanium_Project/assets/79118751/60a4b042-22c0-4318-8cc5-e406857d2c1a)

    
4.  주변 소방서 정보 제공 화면
    - 인근 소방서의 위치와 세부 정보를 보여주는 대시보드 구현
        - 데이터 : 소방서 데이터 (DB에 저장)
        
        ![Untitled (11)](https://github.com/pej0918/2022_Hanium_Project/assets/79118751/1f00a5a4-fac5-4119-8926-b6ea0c7bdd29)

        
5.  과거 산불 통계 시각화 제공 화면
    - 과거 산불 데이터를 기반으로 웹 사용자가 한눈에 알아보기 쉽게끔 시각화하여 보여주는 대시보드 구현
        - 데이터 : 과거 산불 데이터(DB에 저장)
    
    ![Untitled (12)](https://github.com/pej0918/2022_Hanium_Project/assets/79118751/7bb7949b-d5dc-4ab1-92b4-90c0d896f2ab)


### 🏆 결과물 및 결과 🏆

- 입선

![Untitled (13)](https://github.com/pej0918/2022_Hanium_Project/assets/79118751/2e471ed3-ddfa-490a-b049-4553d204b9b3)

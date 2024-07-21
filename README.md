# LH-Compas-DataAnalysis

## 👩‍🦼 밀도기반 군집분석을 활용한 전동휠체어 충전소 위치 최적화

- LH Compas 공모대회 | 한국멀티미디어학회 논문지

  <summary>🏆 <b>대상(LH 사장상)</b></summary> 
  
    <img src="https://github.com/sshnyy/LH-Compas-DataAnalysis/assets/99328827/71e2812b-816b-4753-af8a-f9c4fd1520c3" height="500">

  <br>
  
  <summary>📃 논문지(KCI등재)</summary> 
  
    - KCI보기 : [KCI-링크](https://www.kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART003048426)
    - 원문보기: [DBPIA-링크](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE11699983)

  
<br>

## 📚 Project

- 기술 스택: `Python`, `QGIS`

```
    Team: 2명
    
    My Roles:
      - 프로젝트 리딩
      - 데이터 추출 및 분석
      - AI(머신러닝: 밀도기반 군집분석)을 활용한 위치 최적화
```

<strong> Part 1</strong>: 
```
     Date : 2023.06 ~ 2023.08 (2개월)
     Summary: LH Compas
``` 
<strong> Part 2</strong>: 내용 추가 및 보완
```
     Date : 2023.09 ~ 2024.01 (3개월)
     Summary: 논문지(KCI등재)
```
<br>

## 👀 Summary

- 입지 결정을 위해 요인평정법(FRM, Factor Rating Method)을 활용하여 수요지수 점수를 제안하였습니다.
- 밀도기반 군집분석을 활용하여 실외 공중전화 부스를 대상으로 충전시설에 적합한 위치 최적화 방법을 제안하였습니다.


<br>

<img width="796" alt="image" src="https://github.com/sshnyy/LH-Compas-DataAnalysis/assets/99328827/22caac71-0bc7-4c46-b826-6db1d68efe3f">



## 1️⃣ 프로젝트 소개

- **문제 정의**
    - **전동휠체어 충전소는 2023년 기준 4천여 장소에 설치되어 사용자의 수요 대비 공급이 부족한 상황**이며, 설치기준이 마련되지 않아 지자체마다 운영시간과 대수가 상이하다는 문제가 있습니다.
    - 또한 지자체마다 설치 용이성에 따른 입지 선정은 운영 시간의 제한을 고려하면 전동휠체어 충전소의 공급은 더욱 부족한 상황이므로, **실외를 대상으로 24시간 365일 수용 가능한 입지**선정이 필요합니다.
- **문제 해결**
    - 전동휠체어 충전소의 공급이 부족한 상황을 해결하고자 **입지 장소를 실외 공중전화 부스**로 하였으며, **밀도기반 군집분석**을 활용하여 입지 분석을 진행하였습니다.

<br>

## 2️⃣ 프로젝트 진행과정

1. 전동휠체어와 관련된 데이터를 전처리 및 종합한 뒤, 입지 결정을 위해 요인평정법(FRM, Factor Rating Method)을 활용하여 수요지수 점수를 구성
2. 밀도기반 군집분석에 활용하여 후보군 선별 및 군집의 입지별 특성을 분석한 뒤, 수요지수 점수가 가장 높은 후보군을 기반으로 최적 후보군의 행정동을 선정
3. 선정된 행정동을 대상으로 실외 공중전화 부스 후보군 격자를 추출한 후, 이를 입지 후보군 격자에 할당하여 두 후보군의 매핑을 진행
4. 전동휠체어 충전소 설치 기준을 고려하여 적합한 최적 위치를 선정

<br>

## 3️⃣ 데이터 수집 및 가공


<img width="797" alt="image" src="https://github.com/sshnyy/LH-Compas-DataAnalysis/assets/99328827/8e61eed0-2af1-447e-9fe5-163ac0ef0501">
<img width="794" alt="image" src="https://github.com/sshnyy/LH-Compas-DataAnalysis/assets/99328827/a33e56bc-7379-4b8c-9e85-6972f7ebe61c">

## 4️⃣ AI(머신러닝: 밀도기반 군집분석)을 활용한 위치 최적화
<img width="796" alt="image" src="https://github.com/sshnyy/LH-Compas-DataAnalysis/assets/99328827/1c4e73db-c032-4fd4-b918-0e455f445a94">
<img width="796" alt="image" src="https://github.com/sshnyy/LH-Compas-DataAnalysis/assets/99328827/e0a8099a-394c-4e6f-9bba-50afe22cc8a6">
<img width="795" alt="image" src="https://github.com/sshnyy/LH-Compas-DataAnalysis/assets/99328827/839547e9-765b-44b5-a184-52f5dae4ef3c">



## 5️⃣ 프로젝트 결과

- 최적 행정동에 최적입지로 선정된 충전소의 공급이 증가함에 따라, 이용자의 수요지수 점수가 반 이상 낮아져 기존보다 공급이 충족해질 것을 확인

![image](https://github.com/sshnyy/LH-Compas-DataAnalysis/assets/99328827/1bcd7307-2dfe-4e7e-861c-409ad2e871b9)

- 기존 전동휠체어 충전소의 반경 500m×500m 이내에 포함되는 후보군을 제거하였기에, 설치 거리에도 적합함을 확인
![image](https://github.com/sshnyy/LH-Compas-DataAnalysis/assets/99328827/133b0983-5dc9-4db1-a927-30cc45c272d3)
   
<br>

## 6️⃣ 기대효과 & 한계점

<img width="799" alt="image" src="https://github.com/sshnyy/LH-Compas-DataAnalysis/assets/99328827/9f39c821-7a9a-4fe3-94b3-5669965c1a58">




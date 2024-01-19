##### 2022_Shinhan_data_analysis
# 2022년 신한금융그룹 빅데이터 해커톤


### 신한카드 ESG로 미래세대와 소통하다


> 2022.09.15. (목) - 2022.10.07. (금)
> 
> 신한금융그룹 빅데이터 해커톤 데이터 분석 트랙 우수상 수상
>
> 팀 숙데콘(숙명데이터유니콘) : 강수연, 김세은, 임다미
>
<br>

![Untitled (1)](https://github.com/senikim/2022_Shinhan_data_analysis_R/assets/113660954/c26cee34-a1fb-4d96-afa6-f7dbd3346dc3)

### 💡데이터 분석 기반의 신사업 아이디어 기획

| 서비스 | 세부내용 |
| --- | --- |
| 1. 고객 신용 리스크 관리 서비스 | 의사결정나무 기반의 내부 통제 강화 모델 제시 |
| 2. 플랫폼 통합을 통한 고객 맞춤형 서비스 | 장바구니 분석을 통한 고객 소비 패턴 도출 및 활용 |

<hr>
<br>
    
### **📂 분석 배경과 목표**

- **미래세대 정의**
    
    “MZ 세대 뿐 아니라 다가올 미래에 적응하고 새로운 삶을 실현해 나갈 모든 세대”
    
- **미래세대를 위한 사업 방향성과 신한카드의 실용적 문제 해결을 위한 솔루션 고안**
    - 다가올 미래에 적응하는 미래세대에 발맞춰 미래 세대와 공생관계에 있는 기업 또한 미래를 대비하는 경영, 지속가능한 경영을 지향해야한다고 판단함. 따라서 ESG 지수를 높일 수 있는 사업을 고안함.
    <br> ⇒ 내부통제를 위한 고객 신용 리스크 예측 서비스
    - 신한 Play를 직접 이용하며 느꼈던 아쉬운 점을 보완하기 위한 실용적인 솔루션을 고안함.
    <br> ⇒ 플랫폼 통합을 통한 고객 맞춤형 서비스


### 📂 **사업 요약**

1. **비용 절감 측면의 고객 신용 리스크 관리 서비스 제안**
    
    - 데이터 기반의 내부통제 사업 기획
        
2. **새로운 가치 창출을 위한 신한 Play 확장 서비스 제안**
    
    - 데이터 기반의 플랫폼 통합 사업 기획
        
      | 고객의 소비 유형에 따라 개별 고객의 소비 패턴을 발견한다. |
      | --- |
      | 각 소비 패턴에서 고객의 니즈를 파악하고 그를 충족시킬 수 있는 맞춤형 서비스를 제안한다. <br> * 맞춤형 서비스 : 개인화한 고객의 소비 패턴에 맞는 제휴 쇼핑몰 추천, 펀드 추천, 신한 플랫폼 추천 서비스 |
      
      | 신한 금융 지주사의 모든 플랫폼 통합 |
      | --- |
      | - 궁극적으로 신한 PLAY를 중심으로 신한 올댓 쇼핑, My Car, 신한 알파, 신한라이프 등의 신한 금융 지주사의 모든 플랫폼을 통합 <br> - 신한카드에서 모든 신한 금융 계열사로 서비스를 확장한다.  |
            

### **📂 분석 요약**

  | 머신러닝 모델 | 분석 목적 |
  | --- | --- |
  | 카이제곱 독립성 검정 | 연령대 변수가 신용 위험수준 변수에 영향을 미친다는 가설 검정 |
  | 이항 로지스틱 회귀분석 | 고객의 신용 위험도 관련된 산업 변수 추출 |
  | 의사결정 분류나무 | 신용카드 리볼빙* 대금의 채무불이행 고객의 특성 예측 모델링 <br> *) 카드대금 일부 이월결제약정 |
  | K-means 군집분석 | 신용카드 이용건수 및 결제금액에 따른 소비성향이 유사한 고객 군집 8가지 형성 (VIP 여부에 따른 사전 분류) |
  | Apriori 연관규칙분석 | 8가지 고객 군집별 26개의 결제지출이 있는 산업 중 연관규칙이 있는 산업 집합 추출 |

<br>

## 피드백


📂 **업무 분배**

| 팀원 | 업무 |
| --- | --- |
| 강수연 | 데이터 전처리, 의사결정나무, 의사결정나무 성능평가, 연관규칙분석, 시스템 구현(신사업 기획) |
| 김세은 | 데이터 전처리, 군집분석, 이항로지스틱 회귀분석, 연관규칙분석, 시스템 구현(신사업 기획) |


📂 **프로젝트 소감**

• 데이터 분석 과정에서 얻은 역량 및 개선점 <br>
   </t> 1. 실제 고객 데이터를 가지고 데이터 분석부터 신사업 기획까지 모든 과정에 주도적으로 참여하면서 데이터 기반의 의사결정 역량을 키움. <br>
    2. 새롭게 배운 점과 앞으로 공부해야 할 점을 알게 됨. <br>
        - Apriori 알고리즘의 시간분석도(BigO)에 대한 개선의 필요성 <br>
        - 분석 모델링 성능평가의 중요성 <br>
        - 머신러닝과 알고리즘 공부가 필요함 <br>
    
• 데이터 분석 협업 과정에서 얻은 의사소통 역량 <br>
    1. 내가 해석한 분석 결과를 팀원들에게 설명하는 과정에서 어떻게 하면 더 쉽게 의미를 전달할지 고민함으로써 전달력과 표현법을 배움. <br>
    2. 최종 사업 아이디어를 실무진에게 피칭할 때 본 프로젝트의 목표 달성 과정을 효과적으로 전달하기 위해서 사업의 배경, 방향성, 분석 과정, 도출한 인사이트, 인사이트를 활용한 사업 설명 순으로 구조화하여 전달하는 스토리텔링 능력을 키움.|

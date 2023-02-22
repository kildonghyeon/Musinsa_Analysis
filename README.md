# 무신사 랭킹 데이터 분석
<img src="/images/musinsaLogo.jpeg" width="80%"/>

## 개요
평소 관심이 많던 대한민국 최대 규모의 온라인 편집숍인 무신사 사이트의 상품 랭킹페이지를  
크롤링, 데이터 분석을 함으로써 구매 시 어떤 브랜드가 가장 합리적인지를 판단하는 데 도움이  
될 수 있을 지 그래프 및 표로 볼 수 있다면 좋겠다 생각하고 시작하게 된 데이터 분석 프로젝트입니다.  

## 제작과정
<img src="/images/production.png" width="100%"/>

## 워드클라우드 제작
랭킹 페이지에 가장 많이 오른 브랜드 기준으로 워드클라우드를 제작해보았습니다.  
총 브랜드 수: 915개 (23.01.10 랭킹 페이지 기준)
<img src="/output/musinsaWordCloud.png" width="110%"/>
육안으로만 봐도 무신사 스탠다드가 압도적으로 랭킹 페이지에 이름을 올린 것을 확인할 수 있습니다.  
그 외로는 아디다스, 폴로 랄프 로렌, 디스커버리 익스페디션 정도가 눈에 띄는데  
좀 더 구체적인 확인을 위해 시각화 작업을 진행하였습니다.

***

# 시각화

## 랭킹페이지에 가장 많이 오른 브랜드 Top20 상품수 비교
ggplot을 이용한 막대그래프  
<img src="/output/brandTop20.png" width="80%"/>  
matplotlib을 이용한 파이차트  
<img src="/output/brandTop20(pie).png" width="70%"/>  
두 그래프, 파이차트를 보면 무신사 스탠다드 상품수가 전체 비중에 굉장히 많은걸 확인 할 수 있습니다.  
또, 상위권 브랜드도 전체에서 적지않는 비중을 가지고 있다는 것도 알 수 있습니다.

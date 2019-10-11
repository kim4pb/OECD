# OECD

## 인구 노령화가 과연 개인에게도 부정적 영향을 미칠까?

국가가 출산률이 낮아지고 있다며 국민을 협박하고 있는데, 과연 이게 엄청나게 위험한 것일까?  
국가가 출산지도(가임기 여성지도)를 만들고, 이상적인 여성의 신체를 정의하고, 또한 미디어에 여성의 눈높이를 낮추어 결혼을 권장과 출산을 권장을 하도록 조장을 하고 있다는 사실도 밝혀졌다.

출산률이 낮은 것이 그렇게나 안좋은 일일까?  
환경에도 좋지 않을까?  
현대 여성들은 개인의 성취와 미래를 대비하기 위해 비혼, 비출산에 대한 담론들이 많이 늘어났다. ??  
과연 출생률이 국가를 망치고 개인의 삶도 망칠까? 그렇게 어마무시하게 무서운 일일까?

https://news.joins.com/article/23564231

### 왜 출생률이 낮아질까?
(출산률과 출생률의 다르다)   
출산률 = 1년간 가임여성 1000명당 낳은 출생아 수 / 출생률 = 1년간 인구 1000명당 태어난 출생아 수  
합계출산율 = 가임 여성(15~49세) 1명이 평생동안 낳을 것으로 예상되는 평균 출생아 수

(합계)출산율은 가임기 여성 인구를 토대로 나온 수치이고, 출생률은 남녀노소를 모두 포함한 전체 인구 대비 출생아 수  
보다 정확한 인구변동추이를 보려면 합계출산율과 출생률 여기에 사망률까지 함께 봐야합니다.  
출산율 하락 하나만으로 인구감소를 예측할 수 없습니다.  
통계청 관계자는 "인구감소를 파악하려면 합계출산율, 출생·사망률, 국제인구이동 등 다양한 요소들을 고려해 파악해야 한다"고 강조합니다.  
**출산율이 낮아지는 게 인구감소의 직접적인 영향이라고 볼 순 없다**

![표](http://cdn.bizwatch.co.kr/news/photo/2018/03/08/f12637ff8505a01a5a0be654a06a2e6d110102.jpg)

가임여성 기준?  
1. 여성의 인구가 줄어서? -> 출산률에 영향 x 출생률에 영향
2. 


### 인구 노령화란?
14세 미만 인구 / 65세 이상 인구 * 100

### 개인에게 부정적 영향이란?
1. 임금격차 (영향이 있을까?) 
2. 세금 증가(개인)
2. 행복지수()
3. 복지(건강보험, 연금 )
4. 범죄율
5. 취업률



### 검증 방법
1. 국가별 비교 (실제 노령화가 많이 된 국가와 아닌 국가 비교)
2.  

### 필요한 데이터
1. OECD 연령대별 인구수
2. OECD 취업률
3. 연금, 세금
4. family - 출산률, 취업률, 성별 격차, 육아 육아휴직 -남녀별
5. 평균 출산연령, 결혼연령
6. 행복도

# 중간발표
1. 선택한 데이터
- OECD 데이터

2. 필요한 데이터를 얻기까지 트러블슈팅 과정 (API가 구리다 -> 그래서 다양한 API들을 비교해봤다, 데이터가 비어있는 부분이 많다 -> 비어있는 데이터들을 처리하는 방법들을 찾아봤는데, 통상적으로 이렇게 해결하더라 등)
- 데이터들마다 연도, 국가가 달라 데이터 통합이 어려울 것 같다.

3. 분석 주제
- (위에서 처음에 설명)

4. 데이터 EDA 결과 중 눈여겨 볼 만한 것들 (EDA 하다보니 이 부분이 더 재밌어서 분석 주제를 바꿔봤다)
- 한국이 생각보다 세금이 낮다
- 은퇴 전 소득 대비 실질 연금 수준도 여성이 남성보다 비율이 낮다...

5. 우리 데이터는 이런게 좀 특이하고 재밌다 사랑스럽다
- 

6. 동기들 또는 강사에게 이런 부분은 도움을 얻고 싶다
- 노령화 지수랑 위의 데이터들이랑 어떤 식으로 분석을 해보면 좋을까?
- 생각하기에 시간에 따른 데이터들이다보니까 상관관계는 높게 나올 것 같은데 그게 진짜 상관이 있어서 높게 나오는 게 아닐 것이라는 생각이 든다.

7. 인원이 부족하다! 추가 팀원을 구한다

8. 우리는 이렇게 협업했다 / 팀 구성원의 역할 분배는 이랬다
- 각자 데이터를 나눠서 EDA 해보고 결과를 공유했다.
- 중간 중간 각자 판다스 파일을 공유해서 분석하는데 서로 도움을 받았다.

9. 주제 선정부터 지금까지 이런걸 얻었다 (판다스 복습이 되었다 / API를 만져볼 수 있게 되었다 / 통계 시간에 배운 뭘 써먹어 봤다 / 파이썬 또는 판다스 등에서 새로운 기능을 찾았는데 유용해서 공유하고 싶다)
- 판다스, 시각화 복습

10. 이 프로젝트를 포폴화 하기 위해서 또는 외부에 발표를 할 만큼 매력적으로 만들기 위해서 이런 노력들을 기울이려고 한다.
- 깃헙 만들어서 자료 아카이빙하고, EDA 과정 정리

11. 앞으로 이런 분석들을 해보려고 한다. or 이번에는 좀 부족하지만 차후에 이런 데이터가 더 있다면 ~~ 이런걸 더 해 볼 수 있겠다.
- 행복지수와 출생률, 여성 취업률과 출생률 상관분석
- 출생률 예측

12. 기타
- 전처리의 중요성
- 주어진 데이터를 쓰다보니 내용을 이해해야하고, 원하는 데이터가 없다....

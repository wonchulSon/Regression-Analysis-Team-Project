# Regression-Analysis-Team-Project
```Kaggle Data : Zillow’s Home Value Prediction를 사용한 회귀분석 프로젝트```
</br>

<img src="readme_img/title.png" width="700" align="center">
<img src="readme_img/description.png" width="700" align="center">
</br>

## [ 팀프로젝트 활동 로그 ]
### EDA
- *2018/06/19 (화)*
	- 이전까지 각자 진행했던 EDA를 공유
	- 80 ≤ missing ratio를 갖는 피처을 처리하기 하기 위해 각자의 분석 할당량 분할

- *2018/06/20 (수)*
	- 각자 맡은 피처를 분석한 내용을 브리핑하고, 해당 피처 제거 여부와 NaN 값 처리에 대해 토론<br/>
    	➜ missing ratio가 80% 이상되면 종속변수를 알아내는데 영향이 미미할 것으로 보고 모두 제거하기로 하였음
    
    - 30 ≤ missing ratio < 80 사이의 값을 갖는 피처을 어떻게 처리할지 토론<br/>
    	➜ 각 피처들을 분석해보았을때, 대부분 missing ratio가 높고 중요도가 높지 않다고 생각되어, 대부분 제거하기로 하였지만,<br/>몇몇 피처들은 좀 더 확인해 볼 필요가 있다고 판단되어 기록해두었다가 추후 재검토하기로 하였음
	
    - missing value < 30에 해당하는 25개의 피처 분석에 대해 토론<br/>
        ➜ 25개 중 단 2개의 피처만이 약 9%의 missing ratio를 갖고 나머지 피처들은 모두 4% 미만의 피처이므로,<br/>회귀분석에 있어서 주요 피처가 될 가능성이 높다고 판단되어 모든 피처를 다 함께 면밀히 EDA를 진행하고 토론하기로 하였음 
        
- *2018/06/23 (토)*
	- missing value < 30에 해당하는 피처를 각자 분석한 결과를 브리핑<br/>
    	➜ 3일이라는 시간이 있었지만 피처수가 많기도 하고 매일 수업도 있어서 결국 8개 정도 씩 분석을 했지만 큰 진전은 없었기 때문에 피처들을 비슷한 성격을 갖는 것 끼리 묶고 나눠서 다시 분석하여 2일 후에 브리핑하기로 하였음
    
	
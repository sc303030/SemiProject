# 세미프로젝트_영화추천(Movie_recommendations)

> 최종적으로 완성한 영화추천 시각화 



## POWER BI

> 시각화 툴인 power bi를 이용하여 만들었다.

<iframe style="position: relative; width:1280; height:720;" width="600" height="373.5" src="https://app.powerbi.com/view?r=eyJrIjoiMDFmNjk5YTgtYmYzMy00YWM3LTgzNjctNDRhNjBjNWY0ZDdhIiwidCI6IjcxNzYzNWIxLTFjNzUtNDViOC05NmEzLWQzYzM0MTk5MWUwNyJ9&pageName=ReportSection" frameborder="0" allowFullScreen="true"></iframe>



### 설명

#### 1페이지 

- 해당 유저에게 10개의 영화를 추천한다.
- 유저가 도넛 차트에 있는 영화를 선택하면 오른쪽 포스터 모음에서 해당 영화의 포스터가 나타난다.

#### 2페이지

- 1번 유저에게 기본적인 영화를 추천한다.
- 후에 1번 유저가 영화를 더 관람하였다면 그에 맞춰서 다시 추천해준다.

#### 3페이지

- 가중치를 주지 않은 `SVD()`알고리즘만 사용한 개인화 추천이다.

#### 4페이지

- 4개의 변수 가중치를 준 영화 추천을 비교한다.
- 도넛 차트에서 영화 하나를 클릭해보면 그 영화가 다른 변수 가중치에서 몇 번째로 추천해주었는지 알 수 있다.
- 그와 동시에 가운데 포스터 모음집에서 해당 영화 포스터가 나온다.
- 변수 추천마다 영화를 클릭해보며 어떤 영화들을 추천해주었는지 비교해본다.

#### 5페이지

- 4개의 알고리즘 영화 추천을 비교한다.
- 3페이지와 마찬가지로 도넛 차트에서 한 개의 영화를 클릭해보면 그 영화가 다른 알고리즘에서 몇 번째로 추천해주었는지 알 수 있다.

- 그와 동시에 가운데 포스터 모음집에서 해당 영화 포스터가 나온다.
- 알고리즘 추천마다 영화를 클릭해보며 어떤 영화들을 추천해주었는지 비교해본다.

#### 6페이지

- 4개의 알고리즘을 돌려서 얻은 `RMSE` 와 `MAE`, `FIT TIME`과 `TEST TIME`을 그래프로 나타내었다.
-  어떤 알고리즘이 가장 효율적이었는지 비교해본다.
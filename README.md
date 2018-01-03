# 파이썬으로 데이터 주무르기

* **파이썬으로 데이터 주무르기**라는 책을 집필하고서 책 내용의 데이터와 소스코드를 관리할 목적으로 유지하는 공간입니다.
* IT의 빠른 흐름 떄문에 책 집필 후에 아래의 상황을 자주 만나게 됩니다.
	* 분석하려는 인터넷 사이트가 변경
	* 최신 버젼의 모듈이 문법이 변경
* 그래서 이 공간은 책이 다룬 데이터와 소스코드를 단순히 공개하는 것이 아니라 보다 적극적으로 독자를 위해 항상 소스코드가 공개되도록 유지하겠습니다.
	* 단, 분석하려는 해당 사이트가 아예 없어지거나
	* 해당 모듈이 더이상 버전업등의 지원이 없는 경우는 예외로 합니다.
* 본 공간의 내용 중 기초 내용은 모두 **[PinkWink](http://pinkwink.kr) 블로그**에서도 만나보실 수 있습니다. 
* 그러나 블로그에서 이야기하는 것은 책의 구성과는 꽤 다릅니다.
* 더불어 본 책의 내용에서 더 발전되고 자세한 내용은 **패스트캠퍼스**에서 강의로 진행되고 있습니다.
	* 패스트캠퍼스 강의 : **[파이썬을 활용한 데이터 분석 입문 CAMP](http://www.fastcampus.co.kr/data_camp_pda/)**

## 목차별 소스코드 학습시 주의 사항
* 집필 후 모듈의 업데이터 및 데이터의 취득 방법이나 그 내용이 변경된 경우에 대해서만 정리합니다.

### 1장 서울시 구별 CCTV 현황 분석
* 현재 발견된 수정사항 없음

### 2장 서울시 범죄 현황 분석
* 교재에서 접근하는 방식으로 데이터를 얻으로 가면 교재 집필하던 때와 데이터의 형식이 변경되어 있다.
* 지금은 데이터를 얻는 것이 실제 데이터라는 것에 대한 증명일 뿐이므로, 해당 데이터를 Github에서 배포하는 데이터를 다운받는 것으로 한다.
* Matplotlib의 heatmap 등을 그릴때 cmap의 디폴트 설정이 변경되어 heatmap 등에서 cmap을 적용할 때 옵션을 잡아주어야 교재와 동일한 효과가 나타난다. (소스코드에 모두 반영됨)
* Folium이 0.4.0으로 판올림 되면서 choropleth 명령에서 geo_str 옵션명이 geo_data 옵션명으로 변경됨. (소스코드에 모두 반영)
* Folium이 0.4.0으로 판올림 되면서 circle marker 적용할때, fill=True 옵션을 반듯이 사용해야 함. (소스코드에 모두 반영)

### 3장 시카고 샌드위치 맛집 분석

### 4장 셀프 주유소는 정말 저렴할까

### 5장 우리나라 인구 소멸 위기 지역 분석

### 6장 19대 대선 결과 분석

### 7장 시계열 데이터를 다뤄보자

### 8장 자연어 처리 시작하기
# 줄리아 딥러닝 & 강화학습

본 저장소에는 책 ```줄리아 딥러닝 & 강화학습```의 3부(머신러닝), 4부(딥러닝), 5부(강화학습)에 해당하는 소스 코드 및 예제 실행 결과를 담은 주피터 노트북 파일이 있다.

노트북 파일은 해당하는 파트(부) 폴더 안에 각 장 또는 장/절 별로 명명되어 있다. 예를 들어 3부의 14장 1절에 해당하는 파일명은 ```3부``` 폴더 안에 ```14장1절.ipynb```이다. 노트북은 해당 장의 내용의 흐름에 맞게 순서대로 정리되어 있다. 

각 폴더는 ```Project.toml``` 파일과 ```Manifest.toml``` 파일을 포함하고 있어, 프로젝트 환경을 재현할 수 있게 해놓았다. 프로젝트 환경 재현 방법은 이 책 7.2절에서 다룬다.   

각 노트북 파일들의 예제 실행 결과는 최대한 책의 결과와 동일하게 나오도록 난수 시드 등을 관리했지만, GPU에서 실행되는 플럭스 드롭아웃 층을 포함한 모델과 같이 난수 시드 관리가 어려운 경우는 동일한 결과가 나오지 않을 수 있다.  

줄리아 1.9 버전을 기반으로 하고 있고, 2023년 5월 기준 최신 패키지들을 사용하고 있다.

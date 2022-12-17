# Git-Action

![image](https://user-images.githubusercontent.com/79193811/208234402-6197a65f-f665-460c-9c6e-b841ddbc532c.png)

### 1. git action python package workflow config

* git action python package 선택

* workflow config 생성 

### 2. git workflow 및 파이프라인 작성, 환경변수 설정

* 가상터미널에 선택한 파일을 실행하기위한 환경설정 

* 예)python -m pip install --upgrade pip
        # pip install -r requirements.txt
        pip install selenium
        pip install bs4
        pip install requests
        pip install lxml
        pip install datetime
        pip install pytz

* commit ,pull ,run 등등 파이프라인 작성
![image](https://user-images.githubusercontent.com/79193811/208234539-e428a9eb-9ebd-4ad5-b759-6ba3664b8af6.png)

3.cron 설정으로 주기적으로 자동으로 크롤링한 파일 업데이트


* on:
  schedule:
    - cron:  '* 7 * * *' # 주기적으로 실행하기 위한 스케줄링 - cron 설정


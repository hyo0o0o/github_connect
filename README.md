# github_connect

## 🍬 [git setup](https://git-scm.com/download/win) 🍄
      
      git을 통해서 github과 연결 가능.
      git에 올려야 할 폴더에 shift+우클릭 > PowerShell 선택
      > "git init" 입력
      => .git 폴더가 생성됨.

----------------
## 🍬🍬 open 'Git Dash' after setup the git 🍄🍄
![image](https://user-images.githubusercontent.com/129706828/235417876-203da90e-226f-4334-be0c-b39ee631f6f4.png)

* 유저 이름 설정하기

            git config --global user.name"hyo0o0o"
                  
                  
* 유저 이메일 설정하기(반드시 github에 가입한 이메일 주소와 동일한 주소 기입)
                  
            git config --global user.email "hy84770@gmail.com"
            
* 내 정보 확인하기

      git config --list

## 위 연결은 한 디바이스에서 한 번만 실행하면 됨.
-----------------------

## 🍬🍬🍬 uplode th codr on github  🍄🍄🍄

* 초기화
      
      git init
      
* 추가할 파일(폴더 안 내용을 모두 올림)
      
      git add .(한 칸 띄우고 점 찍기 .은 모든 파일 의미)
      
* 히스토리 만들기(-m=메세지 ""= 안에 쓴 내용은 히스토리 이름 적음)
      
      git commit -m"first commit"

* github에 repository를 만들고 그 주소와 연결하기(리드미 생성금지)

      git remote add origin https://github.com/hyo0o0o/css_flex.git
      
* 연결 확인(사용 안 해도 되는데 혹시나 싶자너~)

      git remote -v
      
* github에 올리기

      git push origin master
      
      
-----------------------------------------------------------
      
## 수정하여 다시 업로드 할 때
      
1.  기존의 코드를 다운받는 행위를 해야한다
      
            git pull origin master
      
2. 다시 push 해야한다

            pit push origin master
            
            
------------------------------------------------------------

# Github 협업하는 방법

1. 소스코드 다운로드

      git clone 주소
      
      git clone 주소쓰기
      
      2. 브랜치(branch) 만들기

      git checkout -b "kim"
      

      ![image](https://github.com/hyo0o0o/github_connect/assets/129016961/ae54d907-0f73-41e9-9214-d91782cdd0ea)

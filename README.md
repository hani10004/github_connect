# github_connect


## 🍩1.  [git설치] (
      
      -git에 올려야할 폴더에가서 shift+우클릭하여 Powershell창열기 
                  git init 입력
                  
      - .git 폴더가 생성됨
 -----------------------      
      

### 🍩2. git 설치 후 git dash 열기

![Untitled-2](https://user-images.githubusercontent.com/129706997/235418164-47cb9d57-709d-480d-8fc3-584a4654d036.png)

      * 유저 이름 설정하기 
                  $ git config --global user.name "hani100"

      * 유저 이메일 설정하기
                  $ git config --global user.email "zz113111@naver.com"

       * 내 정보 확인 하기
                  $ git config --list
                  
## 위의 연결은 해당 컴퓨터에서 한번에 실행하면 됨
----------------------

# github에 코드 업로드하기
      * 초기화
            git init
      * 추가할 파일 (폴더안에 내용을 모두 올림, '.':(콤마)는 모든 파일을 의미, 띄어쓰기 해야함  
            git add . 
      * 히스토리 만들기 (-m: 메세지를 의미함, ""안에는 히스토리 이름을 적음)
            git commit -m "first commit"
      * github에 repository를 만들고 그 주소와 연결하기 (이때, readme체크 하지 마!!!)
            git remote add origin https://github.com/hani10004/css_flex.git
      * 연결이 잘 되었는지 확인하기(선택사항)
            git remote -v
     *  github에 올리기
            git push origin master
----------------------
## 수정하여 다시 업로드할때
      1. 기존의 코드를 다운받는 행위를 해야한다.
            git origin master 
      2. 다시 push해야한다.
            git push origin master
----------------------
# 깃허브 협업하는방법
      1.소스코드 다운로드
      git clone+주소
      
      2.브랜치(branch) 만들기
      git checkout -b ban

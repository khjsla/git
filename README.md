# git
## START git
1. Github 에서 create repository 를 한다. (레포지토리 이름은 프로젝트명)
2. 내 컴퓨터에 있는 프로젝트 폴더 아이콘 위에서 우클릭을 한다.
3. Git Bash Here 를 클릭한다.
```
4. git init 
5. git branch -M main
6. git add . 
7. git commit -m "code desc" 
8. git remote add origin https://github.com/내닉네임/레포지토리 이름.git
9. git push origin main 
```
- . 의 의미는 all 과 동일하다
- origin = 내 GitHub 저장소 별명
- main = 내 컴퓨터 폴더 별명

- 🦔

## ERROR
```
error: failed to push some refs to 'https://github.com/내닉네임/레포지토리이름...
```
에러가뜨면 -> 우선 폴더가 비어있으면 텍스트 파일이든 뭐든 만들어서 추가한 다음!
```
git pull
git add .
git commit -m "first commit"
git push origin main
```

- 🦔

## -ING git
1. 프로젝트 폴더내 파일의 내용을 수정(코드추가/코드삭제)
```
2. git add .
3. commit -m "수정된 내용 설명"
4. git push origin main
```
- 위 과정을 프로그램 폴더내 파일 내용의 수정이 있는 날마다 실행
<br/>-> git 을 사용 함으로써 프로젝트 관리 효율을 높일 수 있게 된다.


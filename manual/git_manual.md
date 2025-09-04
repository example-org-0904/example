# 1. 처음 생성시 적용법


**1-1. 폴더 생성할 아무곳이나 마우스 우클릭 + Git bash here 클릭**

**1-2. 사용자 전역 등록**

```
git config --global user.name (user name)

git config --global user.email (user email)
```

**1-3. 원격 레포지토리 로컬 저장소로 가져오기**

```
git clone http://github.com/(user name)/(repository name)
```
**(Organization 사용시 user name 대신 Organization이름으로 적으면 됨)**

```
git clone http://github.com/(organization name)/(organization's repository name)
```

**1-4. 코드 순차 입력(생성된 폴더에서 bash를 연 다음 - 해당 폴더에 .git이라는 폴더가 존재하는 폴더**

```

git remote // origin이 뜨면 합격

git add . // 여지껏 한 작업들 전부 한방에 이행
git status // 추가한 작업물 확인용

git commit -m "커밋메세지"
ex) git commit -m "add new files"

git push origin main 
```

**1-5 이후 팀프로젝트 진행시 작업 시작 전, clone한 폴더에서 bash를 연 다음 fetch + merge 시키기**

```
git pull origin main // pull 자체가 fetch 시키고 병합(merge)시킴
```
**원래는 fetch 따로 merge 따로 해야함(이해를 위해 예시 남김)**
```
git fetch origin
git merge origin/main
```

***보통 이정도만 숙달해놓으면 괜찮은데 혹시나 오류생기면 알려주세요***




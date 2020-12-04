# 오늘 시험에서 사용했던 git 명령어 정리



## 1. git init

repository를 생성하면 제일 처음으로 git을 사용할 수 있도록 초기화 해줘야 합니다.

git init 을 하고 나면 해당 프로젝트 안에서 git을 사용할 수 있습니다.



## 2. git add

add는 git에 해당 파일을 더하겠다는 뜻입니다. git에 파일을 더해주지 않으면 commit을 할 수 없습니다.

모든 파일을 다 add 하고 싶다면 git add . 라고 온점을 써주면 됩니다.



## 3. git commit -m "설명"

commit을 해야만 git에 파일이 저장됩니다. add만 하면 저장된 상태는 아닌 것이죠!!



## 4. git status

내가 commit을 했는지, add는 했는지 헷갈린다면 git status를 입력해 현재 상태가 어떤지 알 수 있습니다. add가 안돼있는 파일들은 빨간 글씨로 표시되고, add가 된 파일들은 초록 글씨로 표시됩니다.

commit을 하면 어떤 파일이 바뀌었고, 어떤 파일이 추가되었습니다 라는 설명이 뜬 후 초록 글씨도 파란 글씨도 나오지 않습니다. 그러면 git에 저장이 잘 된 것입니다.



## 5. git remote add origin 경로명

repository를 만든 맨 처음에는 github의 원격저장소와 로컬저장소를 연동시켜줘야 합니다.

해석하자면 origin이라는 이름의 remote 저장소를 경로명에 등록하겠다는 뜻입니다.

경로명은 github홈페이지에 내가 만든 repository에서 확인할 수 있습니다.



## 6. git push

push는 원격저장소에 내 commit을 **보내는(push)** 것입니다.

보내고 싶은 branch의 위치를 뒤에 함께 입력해주면 됩니다.

git push origin master, git push origin feature/login 이런 식으로요.

참고로 origin은 위에서 만들어준 원격저장소의 이름입니다.


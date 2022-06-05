# git

## user config 설정하기
깃 쓰기 전에 꼭 설정 해줘야하는것임.

### 현재 설정된 유저컨피그 확인하기
git config --list

### set user name
git config --list user.name (MY_GITHUB_NAME)

### set user email
git config --list user.email (MY_EMAIL_ADDRESS)

### 이름 이메일 동시에 변경
git config --list user.name (MY_GITHUB_NAME) && git config --list user.email (MY_EMAIL_ADDRESS)

"&&" 기호로 터미널 명령어 이어서 쓸수있음.



## 깃 혼자서만 잘써도 나중에 협업하는거는 아주 쉬움
1. git init  (ok)
2. git remote add / git remote remove (git 저장소 리모트)
	* git remote -v   (현재 깃 리모트 확인)
	* git remote add origin https://yoonzz123@github.com/yoonzz123/learn_hosting.git
		* push 할때마다 토큰 입력해서 사용자 인증 받는 리모트 폼.
	* git remote add origin https://yoonzz123:(github_token)@github.com/yoonzz123/learn_hosting.git
		* 저장소를 나만 써서 푸쉬할때마다 귀찮게 토큰 입력 안해도 되게 할려면 이 폼으로.
3. git add
	* git add . (마지막 깃 버전 이후 수정된 파일 모두 깃 밥그릇에 올리기)
	* git add (filename)  (특정파일만 애드)
4. git commit -m "my_message"
5. git branch (이거 설명이긴데 그냥 혼자 사용할때 branch master를 main으로 바꾸는 용도로만 쓰자구)
	* git branch -M main  (-M 옵션으로 master에서 main으로 바꿀수이씀.)
	(git branch -M 을 마스터로 두는게 흑인노예. 그 마스터같다고 해서 세계적인 운동임ㅋㅋ)
	(혼자 쓰는 개인프로젝트에서는 브랜치 따로 안나눠두 대)
6. git push (첫 푸쉬일 경우 git push origin main --set-upstream)
	                            (리모트이름) (main branch)

지머였더라 좀 찾아봐야할거 같은디ㅁ잠금 요 디렉토리  learn_hosting 이거 어떻게 명령함?ㅋㅋ  이거 깃허브 저장소에 올려보셈.

지금은 빔에디터에 들어와있어서.
1. 여기서 나가서 터미널환경에서 명령어 쓰던지.  아니면
2. 터미널 새탭 열어서 쓰면됨.








updated2

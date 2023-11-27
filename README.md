# learn-git

learn git!

# git init
git 초기화 
git으로 프로젝트를 감시하게 해준다.

# 현재 상태를 기록해두려면?

# git add
git add .
git add [file]

# git commit -m "memo"

# staging
local - [git add](기록을 남길 파일을 고르는 행위) -> staging area - [git commit] -> repository(저장소)

# git diff
전 커밋이랑 현재 코드 분석하기
사실 이거보다 git difftool 을 사용한다.
git difftool [commit id]

# Webstorm 기반
cmd + 9 로 깃 메뉴 열 수 있다.
쪽에 로컬 브랜치와 원격 브랜치를 볼 수 있다.

.git 폴더가 로컬 저장소의 정체!

## git init
.git 초기화 즉 git 초기화

## 왼쪽 commit 메뉴에서
VCS로 추적 관리할 수 있다.
삭제는 파일을 정말 지우는 것.

## git 메뉴
로컬 브랜치 오른쪽 마우스 클릭하고 푸시 가능

### Head
특수한 포인터 
브랜치 또는 커밋을 가리킨다.
[Head]를 통해 브랜치를 마음대로 넘나든다. -> 일종의 타임머신 역할
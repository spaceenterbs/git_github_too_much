git config --global user.name "spaceenterbs"
git config --global user.email "anotherhell48@gmail.com"

git config --global user.name
git config --global user.email

git config --global init.defaultBranch main 또는 trunk와 같은 용어
=================================================================
git init

git status

외워서 써먹는 깃 명령어
1. 깃 최초 설정하기
- 깃 버전 확인하기 # git --version
- 줄바꿈 오류 방지(윈도우) # git config --global core.autocrif true
- 줄바꿈 오류 방지(맥) # git config --global core.autocrif input
- 사용자 이름 등록하기 # git config --global user.name "(본인 이름)"
- 사용자 이메일 등록하기 # git config --global user.email "(본인 이메일)"
- 사용자 이름 확인하기 # git config --global user.name
- 사용자 이메일 확인하기 # git config --global user.email
- 기본 브랜치 이름을 main으로 변경하기 # git config --global init.defaultBranch main

2. 깃 관리 시작하기
- 깃 관리 시작하기 # git init 
- 깃 상태 확인하기 # git status
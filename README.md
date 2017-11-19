# -git 저장소에 과제 #7의 코드 업로드하기-
github.com 에 계정을 만듭니다.
과제 #7의 소스코드를 github 저장소에 push 합니다.
저장소 주소를 wiki에 올립니다.

# 느낀 점
gitbash의 커맨드 사용에 익숙하지 않기도 했지만git add, git commit 이후 git push 단계에서 계속 에러가 나서 해결책을 찾는데 상당히 오래 걸렸습니다.

Administrator@ACE-20160120XNF MINGW64 ~/gittest (master)
$ git push -u origin masterTo https://github.com/idblue1047/new.git
! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/idblue1047/new.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.


찾아보니 http://erm00.blog.me/220426457597의 오류가 저랑 같은 현상이었는데 git push origin +HEAD을 하니 문제가 해결되었습니다.


아직까지 git 명령어를 몰라 사용이 익숙치 않지만 사용하다보면 조금씩 익숙해질 거라 기대하고 있습니다.

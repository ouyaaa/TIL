1. git init<br>
    git 으로 관리 시작<br>
    -> 디렉토리당 한번만
    <br>
    * 주의! 홈폴더나 바탕화면 x

2. git status (중요)<br>
    파일 상태 확인<br>

3. git add 파일명<br>
    무대위로 올리기

4. git commit -m "커밋 사유"<br>
   git commit --amend -m "커밋 사유"  <br>
   -> 커밋 해쉬자체가 삭제되고 새로운 커밋으로 대체된다<br>

    변경사항을 기록<br>
    즉, 사진 찍기<br>
    (vim 빠져 나오는 것 esc -> :wq )<br>

5. config 설정 <br>
    -> 한번만<br>
    ->git에게 내가 누군지 알려주기 <br>
    git config --global user.email "you@example.com"<br>
    git config --global user.name "Your Name"<br>
    git config --global --list<br>

6. git log<br>
    커밋 내역 확인<br>
    git log --oneline<br>

7. 커밋 비교<br>
    git diff 비교커밋태그1 비교커밋태그2<br>

8. 외부 원격 저장소 연결<br>
    git remote remove origin (연결 저장소 제거)<br>
    git remote add origin URL주소 (외부 원격 저장소 입력)<br>
    git remote -v (입력 저장소 연결)<br>

9. github에 local commits 올리기<br>
    git push origin master<br>
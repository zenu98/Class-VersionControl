# Class-VersionControl
과제문제
- 교수님의 repository에 이슈를 생성 (제목에 "과제" 라고 꼭 명시!!)
- 교수님의 repository를 fork
- 로컬저장소에 clone
- 교수님의 repository 를 연결(git remote add professor https://github.com/sylee-skhu/Class-VersionControl)
- 교수님의 repository 최신정보 업데이트(git fetch professor)
- 로컬저장소에 브랜치 middle_homework_A 생성 후 체크아웃 (git branch middle_homework_A 한 다음 git checkout middle_homework_A)
- middle_homework_A 브랜치가 교수님의 main 브랜치와 동일한 상태가 되도록 맞춤(git reset --hard 교수님원격저장소별명/main)
- README.md 파일은 # Class-VersionControl 라고 씌여진 파일이다. 그 아랫줄에 본인의 생년월일 6자리을 기입
- middle_homework_A 브랜치의 변경사항을 반영 (git add README.md 와 git commit -m '메시지' 활용)
- 브랜치 middle_homework_B 생성 후 체크아웃
- middle_homework_B 브랜치가 교수님의 2021_2_middle_homework 브랜치와 동일한 상태가 되도록 맞춤(git reset --hard 교수님원격저장소별명/2021_2_middle_homework)
- 아까 생년월일을 추가했던 middle_exam_A 브랜치의 변경사항을 middle_exam_B 브랜치로 병합(middle_exam_B 브랜치에 체크하웃 한 상태에서 git pull middle_exam_A)
- 충돌 발생시 밑에 ****** 를 생년월일로 바꿔서 해결하고 add, commit, push 해서 middle_homework_B 브랜치의 변경사항을 본인의 원격저장소에 반영
- 원격저장소에는 middle_homework_B 브랜치가 없으므로 새로 만들면서 push해야 해서 git push --set-upstream origin middle_homework_B 를 해야 할 수도 있음
- 원격저장소의 middle_homework_B 브랜치를 교수님의 2021_2_middle_homework 브랜치로 반영해달라는 풀리퀘스트 생성
- 풀리퀘스트 내용에 Resolve [본인이 처음에 생성한 이슈 주소] 라고 작성
- 끝

생년월일 : ******

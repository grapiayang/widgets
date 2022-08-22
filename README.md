# git
homepee's widgets 
## 1. git init
사용폴더에서 git 탐색기로 호출하여 이 폴더를 사용하겠다고 초기화 해줍니다
## 2. touch sample.txt
현재 폴더의 샘플 테스트 생성 
## 3. git status
현재 상태 파악하기 
## 4. git add sample.txt / 4번과 5번과 12번을 차례로 실행
git 에다가 샘플 텍스트를 올린다 
## 5. git commit -m " 템플 퀘스트 설명을 올린다 'm'은 메세지" / 4번과 5번과 12번을 차례로 실행
commit 설명을 올린다 -m : 메시지
## 6. git config --global user.email "enterpia@naver.com"
config setup
## 7. git config --global user.name "grapiayang"
config setup
## 8. git remote add origin 주소
git remote add origin https://github.com/grapiayang/bzer5001.git
## 9. remote -v
현재 레퍼토리 상황 주소
## 10. git remote remove origin
리모트 오리진 이 주소가 잘못 되었을 때 변경을 위해 오리진을 지운다 
## 11. git remote add origin https://github.com/grapiayang/bzer5001.git
기존 오리진이 지워졌으면 다시 설정할 오리진 을 설정한다
## 12. git push origin master [업로드]
기존 파일들을 마스터로 올린다
## 12. git pull origin master [다운로드] - 다운로드 먼저 해서 변경된 파일을 받은 후 코드를 추가하여 업로드하는 것을 원칙으로 한다
기존 파일들을 마스터로 부터 다운로드 한다 
## 13. 파일 생성, 추가, 커밋, 업로드 -> 다운로드[수정후], 추가, commit, 업로드
※ commit(message, snapshot)


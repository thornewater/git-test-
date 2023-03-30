# Wecode Git Test

해당 레포지토리는 `git test`를 위한 레포지토리입니다.

시험 시간은 총 1시간이며, `git`에 익숙해질 때까지 연습을 하셔도 좋습니다.

교육생분들은 아래 안내에 따라 단계별 과제를 진행해주시기 바랍니다.

<br>
<br>

## 📍 초기 세팅

1. 터미널을 켜서 desktop 디렉토리로 이동합니다.
   ```shell
        $ cd desktop
    ```

2. `wecode-git-test` 레포지토리를 클론해주세요.
   
    ```shell
        $ git clone https://github.com/wecode-bootcamp-korea/wecode-git-test.git
    ```
3. 터미널에서 클론 받은 레포지토리의 디렉토리 경로로 이동 후 remote 연결을 해제해주세요.
   
    ```shell
        $ git remote remove origin
    ```
4. 본인 github 페이지로 이동하여 repository를 생성해주세요. repository 이름은 `git-test`로 만들어주세요.


5. 이후 아래 이미지처럼 개인 Github에 생성한 레포지토리의 주소를 복사합니다.
   - 예시 이미지
   ![스크린샷 2023-03-21 오전 11 13 55](https://user-images.githubusercontent.com/78401083/226503628-aaf7a9fc-139c-470f-ba4a-3250a9b144e3.png)

6. 다시 clone 받은 프로젝트로 돌아와서 방금 생성한 개인 repo와 연결해줍니다.
   
    ```shell
        $ git remote add origin https://github.com/[본인의 github username]/git-test.git
    ```
7. 이후 노션 안내에 따라 Test를 진행해주세요.


- `git init`  프로젝트 관리를 시작하기위한 명령어
- `git remote add origin <remote repository url>`  프로젝트 폴더를 올릴 repository 에 주소 추가
- `git add <file name>` 변경된 파일 추가
- `git commit` 변경 사항 기록
- `git push origin <branch name>` 변경파일 및 사항 repository에 추가하기
- `git pull origin <branch name>` 원격 변경 사항 가져오기, 내가올린 브런치가 merge 되었을경우 사용
- `git merge <branch name>`  다른 브랜치 변경 사항 병합




# newspaper-alyout




1. 위지위그 : 깃허브 홈피

2. 터미널 모드( 수동 )
-로컬 저장소 (현재 내 pc)
-원격저장소 (깃허브 repository)

 입력순서
    -echo "# mewpaper-layout" >> README.md 생성
    -git init 로컬저장소 초기화
    -git branch - M main  저장소ㅗ > 브랜치 기본경로 생성
    -git remote add origin  깃허브 소스주소 -> 원격저장소 설정
    
    

    -git add . 업데잍 할 파일등록
    -git status 업데이트 대기 등록된 파일 확인 (new 초록색으로 보임)

    -git config --global user.email ww2084@naver.com -깃허브 계정이메일 주소 -> 인증
    (처음만 인증하면됨)
    -git commit -m "업데이트내용설명" -> 변경사항을 반영

    -git push -u origin main 깃허브에 업로드


## 다음 업데이트부터는 
 -glt add .
 git commit -m "업데이트설명글"
 git push -u origin main
# Git 기초
Git 기초 커맨드

## 기본 커맨드
- `git init` : Git으로 프로젝트 관리 시작(`.git` 폴더 생성)
- `git status` : 상태 확인
- `git add [파일명]` : staging
- `git commit -m [메시지]` : commit
- `git log` : commit 히스토리

## 추가 커맨드
- `git checkout [커밋해시]` : 특정 commit을 확인하기
- `git restore [파일명]` : 추가 내용을 버릴 때, 최종 commit version으로 복원

## 원격저장소 관리 :house:

- `git remote` : 원격저장소의 정보(이름)
- `git remote -v` : 원격저장소 정보(이름, 주소)
- `git remote add [이름] [주소]` : 원격저장소 추가
- `git push [저장소 이름] [브랜치 이름]` : 원격저장소로 코드 업데이트
- `git clone [주소] [프로젝트이름]` : 원격저장소 코드 복제
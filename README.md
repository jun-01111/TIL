# TIL
Today I Learned..

## Git 기본 개념

- Git이란? 분산형 버전 관리 시스템(Distributed Version Control System)입니다. 리누스 토르발스가 리눅스 커널 관리를 위해 개발했습니다.

- Git의 특징: 단순한 구조, 빠른 속도, 분산형 저장소 지원 , 그리고 비선형적 개발(브랜치)이 가능합니다.

##Git의 핵심 작업 흐름

- Working Directory (작업 공간): 실제 파일들을 수정하는 내 컴퓨터의 폴더입니다.

- Staging Area (스테이징): 커밋할 변경 사항을 임시로 모아두는 곳입니다.

- Local Repository (로컬 저장소): 커밋 이력(버전)이 저장되는 내 컴퓨터 안의 저장소입니다.

- Remote Repository (원격 저장소): GitHub 등 원격 서버에 있는, 팀과 공유하는 저장소입니다.

  이 영역들을 이동하는 기본 명령어

- git add: 변경 사항을 Working Directory에서 Staging Area로 올립니다.

- git commit: Staging Area의 변경 사항을 Local Repository에 버전으로 기록(스냅샷)합니다.

- git push: Local Repository의 커밋을 Remote Repository로 업로드합니다.

- git pull: Remote Repository의 최신 버전을 Local Repository로 가져옵니다.


## 좋은 커밋을 위한 도구

- feat:: 새로운 기능 추가 

- fix:: 버그 수정 

- docs:: 문서 수정 

- refactor:: 코드 리팩토링 

- .gitignore: Git이 특정 파일이나 디렉토리를 추적하지 않도록(무시하도록) 설정하는 파일입니다.

- pre-commit: git commit을 실행하기 전에 코드를 자동으로 검사하거나 포맷팅해주는 도구입니다.

## 브랜치(Branch) 기초

- git branch [이름]: 새로운 브랜치를 생성합니다.

- git switch [이름]: 해당 브랜치로 작업 환경을 이동(전환)합니다.

- git merge [이름]: 다른 브랜치에서 작업한 내용을 현재 브랜치로 병합(합치기)합니다.

- git branch -D [이름]: 브랜치를 삭제합니다.

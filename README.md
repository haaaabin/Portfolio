# :pushpin: Projects
</br>
개인/팀 프로젝트에 대한 상세 설명, 주요 기능, 담당 역할 등을 기재하였습니다. </br>
자세한 사항은 각 프로젝트의 제목을 클릭하시면 볼 수 있습니다.

</br>

### 1. [KITTY VALLEY](https://github.com/haaaabin/Valley)
> Unity 2D RPG 농장 생활 시뮬레이션 게임 (개인 프로젝트)
> 
> 개발 기간 : 2024.10 ~ 2024.11
> 
> 사용 언어 및 개발 환경 : Unity, C#, Git
>
> #### 주요 기능
>  - ScritableObject를 활용하여 아이템 데이터를 효율적으로 관리하여 확장성 강화
>  - 드래그 앤 드롭, 툴바 UI를 통한 직관적인 <b>UX</b> 설계
>  - <b>JSON</b>을 활용하여 저장/로드 시스템 구현
>  - <b>농작물, 인벤토리, 저장/로드 시스템</b>을 통합적으로 설계하고 구현하면서 시스템 간 연계의 중요성 인지

---
### 2. [Sleighers (슬레이어즈)](https://github.com/haaaabin/Sleighers_Client)
> [크래프톤 정글] 설산 배경의 멀티 플레이 썰매 레이싱 게임 (팀 프로젝트)
> 
> 개발 기간 : 2024.4.18 ~ 2024.5.24 (5주)  
>
> 참여 인원 : 5인(클라이언트 3, 서버 2)
> 
> 사용 언어 및 개발 환경 : Unity, C#, GitHub Action, Git
>    
> #### 담당 역할
>  - 사용자 경험을 고려하여 전반적인 <b>인게임/아웃게임 UI</b> 개발
>  - 플레이어의 체크포인트 및 거리 데이터를 기반으로 [실시간 랭킹 시스템 구현](https://github.com/haaaabin/Sleighers_Client/blob/e87a9df5fef953412336d99781b7e7ba34dd04cd/Assets/Scripts/InGame/Ranking/RankManager.cs#L6-L183) 
>  - [보간/외삽을 사용한 유저 간 상태 동기화](https://github.com/haaaabin/Sleighers_Client/blob/e87a9df5fef953412336d99781b7e7ba34dd04cd/Assets/Scripts/InGame/Sled/Player.cs#L271-L298) 로 네트워크 지연을 최소화하고 원활한 플레이 경험 제공
>  - <b>프로파일러를 사용한 CPU 사용률 분석</b>을 통해 카메라 렌더링, GUI, 프로세스 프로세싱, 파티클 시스템, 퍼포먼스 스파크 최적화로 클라이언트 프레임 레이트 <b>20FPS -> 40FPS</b> 향상
>  - 클라이언트와 서버 간의 구조를 이해하기 위해 서버 코드에 대한 학습을 진행하여, <b>카운트 다운과 매치 메이킹 프로토콜</b>을 구현하여 서버와의 통신 부분 기여

---
### 3. [PintOS](https://github.com/haaaabin/PintOs)
> [크래프톤 정글] 카이스트 교육용 운영체제 학습을 위한 프로젝트 (팀 프로젝트)
> 
> 개발 기간: 2024.03 ~ 2024.04  
>
> 참여 인원 : 3인
>
> 사용 언어 및 개발 환경 : C, Ubuntu, Git
>
> #### 주요 기능
>  - <b>Threads</b> 프로젝트에서 <b>스레드의 우선 순위</b>에 따라 CPU를 선점할 수 있도록 donation 기능 구현하여 모든 과제 통과
>  - <b>User Programs</b> 프로젝트에서 open, write, fork 등 <b>시스템 콜</b>을 구현하여 3개를 제외하고 모든 과제 통과
>  - <b>Virtual Memory</b> 프로젝트에서 보조 페이지 테이블을 활용한 <b>가상 메모리</b>를 구현하여 3개를 제외하고 모든 과제 통과

---
### 4. [Welcome To Jungle](https://github.com/haaaabin/Welcome_To_Jungle)
> [크래프톤 정글] ﻿3D 멀티 플레이 및 게시판 기능 (팀 프로젝트)
> 
> 개발 기간: 2024.04 ~ 2024.04  
>
> 참여 인원 : 2인 (클라이언트 1, 서버 1)
>
> 사용 언어 및 개발 환경 : ﻿Unity, C#, 뒤끝 서버, Git
>
> #### 담당 역할
> - 글쓰기 관련 CRD(Create/Read/Delete) 기능 구현
> - 플레이어 이동과 카메라 조작 구현
> - 아웃게임 UI
>
> #### 주요 기능
>  - 로그인 및 회원가입 기능- 글쓰기 관련 CRD(Create/Read/Delete) 기능
>  - 모바일 환경을 고려하여 조이스틱을 활용한 플레이어 이동 및 터치패드를 활용한 카메라 조작
>  - 뒤끝 매치 메이킹을 활용한 멀티 플레이 기능

</br>



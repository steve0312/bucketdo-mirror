# 버킷 두(Bucket Do)

작심삼일러를 위한 "작은 실천으로 큰 목표 이루는" 기록 서비스 ✅

![메인 이미지](assets/main.png)

<br />

[🔗 BucketDo 바로가기](https://43.201.20.130.sslip.io/)

<br />

## 📖 프로젝트 소개

> 프로젝트 기간 : 2025.02.19 ~ 2025.03.06

장황한 계획을 이루지 못하는 작심삼일러를 위해, 세분화된 투두 리스트 실천으로 버킷 리스트를 이루는데 도움을 주는 기록 서비스입니다.

사용자가 이루고 싶은 큰 목표를 작은 목표들로 나누어 달성률을 높일 수 있도록 하였습니다. 계획을 세워놓기만 하고 실천하지 않는 이유는 무엇일까요 ? 너무 큰 계획을 세우지는 않았나요 ? 큰 목표만 생각하면 달성하기 어려워 질 수 있습니다. 버킷두를 통해 작은 계획으로 세분화하되, 이를 하나씩 이루어가는 것은 어떨까요 ?

“천천히, 하나씩, 당신은 할 수 있어요 !”

<br />

## ⚒️ 기술 스택

- **Frontend** : React 19, Redux 9.2, Axios 1.7
- **Backend** : Spring Boot 3.4.3, Java 21, MySQL 8
- **Infra** : Docker, AWS EC2, AWS S3, GitHub Action
- **Tool** : Figma, Notion, Jira, GitHub

<br />


## ✨ 주요 기능

| 회원가입 및 로그인                                                                                                | 버킷 리스트 생성                                                                                                  |
|-----------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| 아이디, 이메일, 비밀번호 입력으로 사용자 정보가 등록됩니다. <br /> 사용자 인증 정보를 통해 로그인합니다.         | 버킷 리스트를 생성합니다.                                                                                             |
| <img src = "https://github.com/user-attachments/assets/b87b774e-c6d2-4299-ad90-ce82d04db03b" width="300"> | <img src = "https://github.com/user-attachments/assets/6aebb13d-a950-46b3-832e-a82812b96a5e" width="300" > |

| 버킷 리스트 수정                   | 버킷 리스트 필터                   |
|-----------------------------|-----------------------------|
| 버킷 리스트의 제목과 이미지를 수정합니다.     | 버킷 리스트의 진행도에 따라 목록을 조회합니다.  |
| <img src = "https://github.com/user-attachments/assets/a4287ed8-7b0d-4eb5-a7c1-b44cb0379bfa" width="300" > | <img src = "https://github.com/user-attachments/assets/1dc97ad3-f750-41c6-9079-d11f83087f83" width="300" > |

| 버킷 리스트 삭제                                | 투두 리스트 생성                                |
|------------------------------------------|------------------------------------------|
| 생성한 버킷 리스트를 삭제합니다. | 버킷 리스트의 하위 투두 리스트를 생성합니다. |
| <img src = "https://github.com/user-attachments/assets/e8237ce2-00c3-4eef-a906-70026fb13a0e" width="300"> | <img src = "https://github.com/user-attachments/assets/5aaef3d9-c557-4b8b-ac72-4e408582c89a" width="300" > |


| 투두 리스트 수정                                   | 투두 리스트 삭제                                                                                                               |
|------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|
| 투두 리스트의 내용을 수정하고, 체크박스를 표시합니다. <br /> 모든 투두 리스트를 체크할 경우, 버킷 리스트는 완료 처리가 됩니다. |   투두 리스트를 삭제합니다.                                  |
| <img src = "https://github.com/user-attachments/assets/f1093f82-d20c-4bf6-98dc-792406f23ed2" width="300" > | <img src = "https://github.com/user-attachments/assets/34e2d8aa-f976-4ab9-b541-e8d762b9042f" width="300" > |

<br />

## 🏗️ 아키텍처

### 서비스 아키텍처

![서비스 아키텍처](assets/service.png)

### CI / CD

![CI / CD](assets/ci_cd.png)

### ERD 설계도

![ERD 설계도](assets/erd.png)

### 와이어프레임

![와이어프레임](assets/wireframe.png)

<br />

## 👥 팀 소개

| Frontend | Frontend | Backend | Backend | Backend |
| --- | --- | --- | --- | --- |
| <img src="assets/member_sungjoon92.png" alt="원성준" width="150" /> | <img src="assets/member_imdla.png" alt="임수빈" width="150" /> | <img src="assets/member_ssdeok.png" alt="서승덕" width="150" /> | <img src="assets/member_steve0312.jpeg" alt="이상호" width="150" /> | <img src="assets/member_wag192625.jpg" alt="정명훈" width="150" /> |
| [원성준](https://github.com/sungjoon92) | [임수빈](https://github.com/imdla) | [서승덕](https://github.com/ssdeok) | [이상호](https://github.com/steve0312) | [정명훈](https://github.com/wag192625) |



<br />

## 📝 문서

| 📃 리소스 | 🔗 링크 | 설명 |
| --- | --- | --- |
| 팀 노션 | [Notion 링크](https://www.notion.so/BucketDo-19d8cf3b3b228052a204e7b2f8f40099?pvs=21) | 프로젝트 계획 및 일정 관리 |
| 피그마 디자인 | [Figma 링크](https://www.figma.com/design/QM8vJ0pEPeqOPIAi6CDCde/%EB%94%94%EC%9E%90%EC%9D%B8-%EC%84%A4%EA%B3%84?node-id=0-1&t=Pm5B6xXHu8BQp6X8-1) | UI / UX 디자인 |
| Jira 백로그 | [jira 링크](https://bucket-do.atlassian.net/jira/software/projects/BD/boards/1/backlog?epics=visible&atlOrigin=eyJpIjoiOTliMThlZDg1YTUzNDNkMzhhNDk5NWE2MTBhMjg2NzIiLCJwIjoiaiJ9) | 프로젝트 개발 프로세스 관리 |

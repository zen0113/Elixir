<!-- ===================== -->
<!--  GitHub Project README -->
<!-- ===================== -->

<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=24,20,14,6,2&height=180&section=header&text=Elixir&fontSize=64&animation=twinkling)


</div>

<br>

## 📌 Overview

**AI 챗봇 기반 저속노화 식단 관리 앱**입니다.

GPT-4o mini를 활용한 맞춤형 식단 추천과
게이미피케이션 요소를 결합하여
지속적인 건강 관리 동기를 제공합니다.

<br><br>

### Project Information

<div align="center">

| 항목    | 내용                          |
| :---- | :-------------------------- |
| 개발 기간 | 2025.03.28 ~ 2025.09.05 (6개월) |
| 플랫폼   | Android                     |
| 개발 언어 | Kotlin                      |
| 개발 형태 | 팀 프로젝트 (4인)                 |
| 역할    | 앱 디자인 / 안드로이드 프로그래밍        |

</div>

<br><br><br>

## 🎮 Demo

<div align="center">

|                                                 화면                                                 | 설명                                     |
| :----------------------------------------------------------------------------------------------------: | :------------------------------------- |
| <img src="YOUR_GIF_1.gif?raw=true" width="250"/> | 식단 캘린더 및 점수 기반 색상 표시 시스템 |
| <img src="YOUR_GIF_2.gif?raw=true" width="250"/> | GPT-4o mini 기반 AI 챗봇 맞춤 피드백 |
| <img src="YOUR_GIF_3.gif?raw=true" width="250"/> | 월간 챌린지 시스템 및 단계별 진행도 |

</div>

<br><br><br>

## 💻 Core Features

<br>

### 식단 캘린더

사용자의 식단 기록을 직관적으로 관리하고
시각화하는 시스템입니다.

<br>

**주요 기능**

* 메인 화면에 캘린더 + 리스트 형태로 식단 기록 제공
* 하루 동안 아침, 점심, 저녁은 1번씩, 간식은 여러 번 기록 가능
* 사용자가 입력한 식단 점수에 따라 캘린더 및 리스트에 색상 표시

<br>

**기술 구현**

* Room Database를 활용한 로컬 데이터 영속화
* RecyclerView 최적화를 통한 부드러운 스크롤 경험
* 날짜별 데이터 필터링 및 집계

<br><br>

### AI 챗봇

GPT-4o mini를 활용한 저속노화 식단 관리 특화 챗봇입니다.

<br>

**핵심 특징**

* 프롬프트 엔지니어링으로 간결하고 실용적인 조언 제공
* 4가지 기능을 통해 사용자가 등록한 식단 및 레시피를 불러와 맞춤 피드백 제공
* 대화 히스토리 기반 컨텍스트 유지

<br>

**구현 방식**

* MVVM 패턴 기반 아키텍처
* Kotlin Coroutines를 활용한 비동기 API 통신
* Room Database로 대화 내역 로컬 저장 및 관리
* Repository 패턴으로 데이터 레이어 추상화

<br><br>

### 챌린지 시스템

게이미피케이션을 통한 지속적인 동기 부여 시스템입니다.

<br>

**설계**

* 단계별 건강 미션으로 구성된 월간 챌린지
* 보건소 자료 기반으로 챌린지 구성 (식재료 매달 갱신)
* 각 단계는 2개의 미션으로 구성되며, 완료 시 다음 단계로 자동 진입

<br>

**서버 연동**

* 서버 API(Retrofit)로 진행도 동기화
* 실시간 진행 상태 업데이트
* 달성 시 뱃지 및 보상 시스템

<br><br><br>

## 🏗 Architecture & Tech Stack

<br>

### Architecture Pattern

**MVVM (Model-View-ViewModel)**

* UI와 비즈니스 로직의 명확한 분리
* ViewModel을 통한 생명주기 안전한 데이터 관리
* LiveData/StateFlow를 활용한 반응형 UI 구현

<br>

### Key Technologies

**Android Development**

* Kotlin Coroutines + lifecycleScope 비동기 처리
* Repository 패턴으로 데이터 접근 계층 추상화
* Room Database를 활용한 로컬 캐싱
* Retrofit을 통한 RESTful API 통신

<br>

**오프라인 우선 전략**

* 서버 API(Retrofit) 데이터를 로컬 DB(Room)에 캐싱
* 네트워크 연결 상태와 무관하게 앱 사용 가능
* 연결 복구 시 자동 동기화

<br><br>

### Tech Stack


**Frontend**

![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)

**Backend**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

**Infrastructure**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</div>

<br>

**Development Environment**

* Android Studio
* Android SDK 23+
* Java 17

**Backend & Database**

* Spring Boot
* Redis
* Amazon RDS
* MySQL
* Swagger

**Infrastructure & DevOps**

* Amazon ECS
* AWS Fargate
* Docker
* GitHub Actions
* Amazon S3
* AWS ALB

<br><br><br>


## 🏆 Achievement

<br>

* **KCI 등재 학술지 논문 게재** (2025)
* 6개월 장기 프로젝트 성공적 완수

<br><br><br>

## 📚 Lessons Learned

이번 프로젝트를 통해
다음과 같은 점을 학습했습니다.

<br>

* MVVM 아키텍처 패턴의 실전 적용 및 장점 체감
* Kotlin Coroutines를 활용한 효율적인 비동기 처리
* Repository 패턴을 통한 데이터 레이어 추상화의 중요성
* 오프라인 우선 전략을 통한 사용자 경험 향상
* GPT API 연동 및 프롬프트 엔지니어링 경험
* 장기 프로젝트에서의 팀 협업 및 역할 분담
* 디자인과 개발을 병행하는 풀스택 경험

<br><br><br>

<div align="center">

![footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=24,20,14,6,2&height=120&section=footer)

</div>
```

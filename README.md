# 최승문 | Seungmoon Choi

널뎁스의 창업자이자 소프트웨어 개발자입니다.  
Unity 게임과 데스크톱 앱, 웹 인터랙티브 콘텐츠, AI가 실제 업무를 수행하는 제품을 만듭니다.

아이디어를 구체적인 이용 흐름으로 정리하고, 클라이언트와 서버 구현부터 테스트, 배포와 운영까지 이어갑니다.

[포트폴리오](https://seungmoon-choi.opendesk.page) / [널뎁스](https://nerdevs.co.kr) / [OpenDesk](https://opendesk.ai.kr) / [블로그](https://cgmoon.tistory.com) / [이메일](mailto:moonchoi@nerdevs.co.kr)

## 현재

**널뎁스 창업자, 소프트웨어 개발자 | 2025.06~현재**

AI 데스크톱 제품 OpenDesk를 기획하고 개발합니다. Unity 게임과 개발 도구를 만들고, 웹 서비스와 인터랙티브 콘텐츠를 제작합니다. 브랜드와 팝업의 현장 경험에 연결되는 디지털 체험도 기획하고 개발합니다.

## 대표 작업

### OpenDesk

AI 모델과 외부 도구를 연결해 사용자가 작업을 맡기고 실행 과정과 결과를 확인하는 데스크톱 앱입니다. 클라이언트와 AI 실행 계층, 백엔드의 구조 설계와 핵심 개발, 사용자 승인과 실패 및 취소 처리, 대화 복구와 공개 베타 배포를 맡았습니다.

`Unity` `C#` `Python` `FastAPI` `PostgreSQL` `MCP`  
[웹사이트](https://opendesk.ai.kr) / [공개 배포 저장소](https://github.com/TeamH-GameStudio/OpenDesk-releases)

### 무림 히어로즈

5인 팀(개발 2/기획 1/디자인 2)으로 시작해, OpenDesk 개발로 팀 개발이 멈춘 뒤 사이드 프로젝트로 이어 가고 있는 무협 RPG입니다. 스킬을 애니메이션, 타격 대기, 데미지, 이펙트 같은 Action의 조합으로 정의하는 전투 구조, VContainer 의존성 주입 전환, 성능 측정과 개선, 게임 데이터 에디터를 맡았습니다.

`Unity` `C#` `VContainer` `UniTask` / 2024.03~현재 / 미출시

### 웹 인터랙티브 콘텐츠

이어그림 LIVE의 교실 실시간 상호작용, 반반의 무대 제어와 관객 가사 화면을 개발했습니다. 이용 흐름과 화면, 서버 상태를 연결하고 모바일 이용과 재접속 상황을 검증했습니다.

`React` `TypeScript` `WebSocket` `Cloudflare`  
[널뎁스](https://nerdevs.co.kr) / [반반](https://banban.opendesk.page)

### Unity Wireless Debug Manager

Android 기기의 무선 디버깅을 Unity Editor 안에서 관리하는 도구입니다. 무선 페어링과 연결 관리, 여러 기기의 상태 표시, ADB 경로 탐지, 한국어와 영어 전환을 구현했습니다.

`C#` `ADB` `UPM`  
[저장소](https://github.com/ovthemoon/unity-wireless-debug-manager)

<details>
<summary><strong>전체 프로젝트와 담당 범위</strong></summary>

### OpenDesk

2026.02~현재 / 1인 개발 / 자체 제품, 2026.08 공개 베타

- Unity/C# 클라이언트, Python AI 실행 계층, FastAPI/PostgreSQL 백엔드의 구조 설계와 핵심 개발
- 여러 AI 모델, 외부 도구와 MCP 연동
- 도구 실행 전 사용자 승인, 실행 상태, 실패와 취소, 사용량 처리
- 대화 저장과 복구, 승인 대기와 업무 재개, 앱 배포와 베타 지원

### 무림 히어로즈

2024.03~현재 / 5인 팀으로 시작, OpenDesk 개발로 팀 개발 중단 뒤 사이드로 계속 / 미출시

- 캐릭터 상태머신과 Action 조합형 스킬 실행 구조, Action 40여 종으로 캐릭터 15명의 스킬 정의
- 스킬 정의를 JSON 텍스트로 옮기고 에셋을 다시 만드는 컴파일러(원본과 차이 0)
- VContainer 의존성 주입 전환(LifetimeScope 11개), 우편함 가상 스크롤 20 → 59 FPS
- 게임 데이터 에디터로 캐릭터 1명 검증 기간 7일 → 3일

### PopPop Word

2025.02~2025.09 / 2인 팀 / 2025.09 Google Play 출시(유지보수 종료로 현재 내림) / Unity, C#, Addressables

- 청크와 그리드 기반 시설 배치, 이동과 회전, 점유와 충돌 검사
- 작물과 나무의 성장, 물주기와 수확, 동물 호감도와 보상
- 공통 UI, 화면 전환, 데이터 저장, 광고와 인앱 결제의 클라이언트 흐름

### Unity Wireless Debug Manager

Unity Editor 개발 도구 / C#, ADB, UPM

- Android 무선 페어링과 연결 관리, 여러 기기의 상태 표시
- ADB 경로 탐지, 한국어와 영어 전환

[저장소](https://github.com/ovthemoon/unity-wireless-debug-manager)

### Anything Arena

2026.09 개발 및 검증 / 브라우저 파티 배틀 프로토타입 / React, TypeScript, WebSocket, Cloudflare Durable Objects

- 방별 상태를 관리하는 실시간 멀티플레이
- AI 판정 입력 검증과 서버 규칙에 따른 피해량, 승패 확정
- 응답 시간 제한, 지연 응답 폐기, 여러 브라우저의 경기 흐름 검증

### 이어그림 LIVE

2026.09~10 개발 및 검증 / 내부 교육 시제품 / WebSocket, Cloudflare

- 선생님, 학생, 중계 화면을 연결하는 단어 릴레이 콘텐츠
- 역할별 상태 동기화, 서버 저장, 재접속과 서버 재시작 후 복원

### 반반

2026.09~10 개발 및 검증 / 공연 운영 웹사이트 / JavaScript, WebSocket, Cloudflare

- 밴드 소개, 공연 관리, 무대 제어와 관객 가사 화면 연결
- 서버 시각 기준의 진행, 정지와 재개, 중간 접속과 탭 복귀 시 상태 복구

[웹사이트](https://banban.opendesk.page)

### 널뎁스 홈페이지와 관리자

자체 서비스 웹사이트 / Next.js, React

- 서비스 소개, 체험 콘텐츠, 문의 접수와 운영자 관리
- 로그인과 권한 확인, 콘텐츠와 문의 상태 관리
- 문의 실패 시 입력 보존과 재시도 흐름

[웹사이트](https://nerdevs.co.kr)

### 이전 작업

- [MirrorDimension](https://github.com/ovthemoon/MirrorDimension) — 한림대학교 캡스톤 게임 프로젝트
- [3D Flag Museum](https://github.com/ovthemoon/3dflagmuseum) — 웹 3D 국기 박물관
- [3D Model Viewer](https://github.com/ovthemoon/3d-model-viewer) — React, TypeScript, Three.js 기반 모델 뷰어
- [AutoMeetingNote](https://github.com/ovthemoon/AutoMeetingNote) — Notion, Discord, ChatGPT를 연결한 회의록 자동화

</details>

<details>
<summary><strong>기술과 개발 방식</strong></summary>

| 분야 | 기술 |
|---|---|
| 게임과 클라이언트 | Unity, C#, UniTask, Addressables, 상태머신, UI, 데이터 저장 |
| 웹과 인터랙티브 | React, TypeScript, Next.js, JavaScript, Three.js, WebGL |
| 서버와 실시간 통신 | Python, FastAPI, PostgreSQL, WebSocket, Cloudflare Workers, Durable Objects |
| AI 연동 | LLM API, 도구 호출, MCP, 실행 상태와 사용자 승인 처리 |
| 개발 환경 | Git, Claude Code, Codex |

Claude Code와 Codex를 개발 과정에 활용하며, 코드 구조와 오류 처리, 실제 실행 결과를 검토하고 반영합니다.

</details>

<details>
<summary><strong>학력</strong></summary>

**한림대학교 | 2019.03~2025.07**  
콘텐츠IT 학사, 빅데이터 복수전공, 졸업

</details>

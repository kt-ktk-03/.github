# ArchiTalk | 자동 다이어그램 에이전트

## 🏀 Repos
* GitOps : https://github.com/kt-ktk-03/final-gitops
* Frontend : https://github.com/kt-ktk-03/final-front
* Backend : https://github.com/kt-ktk-03/finalmainserver
* Flask : https://github.com/kt-ktk-03/final-agent-flask-server

### 🧠 목적
사용자의 자연어 입력을 기반으로 다이어그램을 생성해주는 인공지능 기반 에이전트를 개발합니다.
### 💡 주요 기능
- 자연어 및 코드 분석
- 다이어그램 생성 및 시각화
- 생성된 다이어그램의 수정 및 재생성 지원 

### 🧰 사용 기술
- 언어 모델 (GPT-4o 등)
- 다이어그램 렌더링 도구 (Mermaid.js, Draw.io)
- 프론트엔드 (Next.js)
- 백엔드 (Python FastAPI or Flask)
- 저장 및 공유 기능 (Notion 연동 가능 -> Confluence 로 활용 가능)
### 🖼️ 예시 시나리오
> 사용자가 입력 → 프로젝트의 설계서, 리소스 정의서 등을 서비스에 등록 <br>
> → 에이전트는 제공된 자료를 읽고, 인프라 설계도 다이어그램(Draw.io)으로 시각화

> 사용자가 입력 → 프로젝트의 소스코드 Git 레포 <br>
> → 프로젝트를 구성하는 여러개의 Git 링크를 통해 서비스간 플로우차트를 그려냄
> → Mermaid.js 로 시각화

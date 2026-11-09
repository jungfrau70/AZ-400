# AZ-400 (Designing and Implementing Microsoft DevOps Solutions) 학습 자료

> 대상 자격증: **Microsoft Certified: DevOps Engineer Expert**
> 선수 조건: AZ-104(Administrator) 또는 AZ-204(Developer) 중 하나 취득
> 시험 형식: 약 40~60문항, 100분 내외, 합격 점수 700/1000, 케이스 스터디·드래그 앤 드롭·다중 선택·Yes/No 시리즈 포함, 시험 중 Microsoft Learn 열람 가능(Open book)

⚠️ Microsoft는 시험 범위를 수시로 업데이트합니다. 시험 전 반드시 공식 **Study guide for Exam AZ-400** 페이지의 "Skills measured"를 확인하세요.

## 구성

| 파일 | 내용 |
|---|---|
| [01-이론.md](01-이론.md) | 5개 출제 영역별 핵심 개념, 비교표, 시험 포인트 |
| [02-실기.md](02-실기.md) | `temp/springboothelloworld` 앱을 활용한 단계별 실습 10개 (Azure DevOps + GitHub Actions) |
| [03-문제집.md](03-문제집.md) | 영역별 연습문제 70문항 + 케이스 스터디 + 해설 |

## 출제 영역과 비중

| # | 영역 | 비중 |
|---|---|---|
| 1 | 프로세스 및 커뮤니케이션 구성 (Configure processes and communications) | 10–15% |
| 2 | 소스 제어 전략 설계·구현 (Design and implement a source control strategy) | 10–15% |
| 3 | 빌드 및 릴리스 파이프라인 설계·구현 (Design and implement build and release pipelines) | **50–55%** |
| 4 | 보안 및 규정 준수 계획 개발 (Develop a security and compliance plan) | 10–15% |
| 5 | 계측 전략 구현 (Implement an instrumentation strategy) | 5–10% |

→ **파이프라인 영역이 절반 이상**입니다. 학습 시간도 그 비율로 배분하세요.

## 4주 학습 계획 (하루 1.5~2시간 기준)

| 주차 | 이론 | 실기 | 문제 |
|---|---|---|---|
| 1주 | 영역 1, 2 | Lab 1–3 (Boards, Repos, 브랜치 정책) | 1~25번 |
| 2주 | 영역 3 전반부 (에이전트, YAML, 템플릿, 아티팩트) | Lab 4–6 (CI, 패키지, 멀티 스테이지 CD) | 26~45번 |
| 3주 | 영역 3 후반부 (배포 전략, IaC) + 영역 4 | Lab 7–9 (GitHub Actions OIDC, Bicep, 보안 스캔) | 46~62번 |
| 4주 | 영역 5 + 전체 복습 | Lab 10 (App Insights, KQL) | 63~70번 + 케이스 스터디, 오답 재풀이 |

## 실습 환경 준비물

- Azure 구독 (무료 체험 또는 종량제) — 실습 후 리소스 그룹 삭제로 비용 관리
- Azure DevOps 조직 (https://dev.azure.com) — 무료 Basic 5명, Microsoft 호스팅 병렬 작업 1개 (신규 조직은 무료 병렬 작업 신청 필요할 수 있음)
- GitHub 계정
- 로컬: Git, Azure CLI (`az`), JDK 25, VS Code
"# AZ-400" 

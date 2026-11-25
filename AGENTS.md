# Repository evaluation instructions

## Independent judging / 평가 격리
- For every new version's independent evaluation, read only the explicitly designated version's proposal, its current supporting design materials, the official contest guide/sample, and the fixed rubric below.
- **Do not open, search, summarize, or use `evaluations/` (including earlier scores, recommendations and comparison reports), previous-version proposals, prior review discussions, or prior feedback during absolute scoring.** Do not recursively ingest the entire repository. Listing paths to locate the requested version is permissible; exclude archived evaluation contents from retrieval.
- Only after the new version's absolute score and evidence have been finalized may the evaluator read earlier reports, and only if the user explicitly asks for a version comparison. Never revise absolute scores merely to match the earlier scores.
- A request to archive an evaluation is not a request to perform a new evaluation. Keep archival reports separate from proposal documents. Do not use archive contents as proposal evidence.
- Score the proposal as written. Do not infer missing designs, add points for implementation, or penalize lack of implementation/experiments. External research is allowed for feasibility and existing alternatives, not to fill missing design. Distinguish evidence from inference, and disclose non-blind evaluation limitations.
- These rules do not apply to an explicit request to read, archive or compare evaluation records.

## Fixed rubric: Independent Agentic AI Judge v1.0

| Category | Subcriteria (points) | Total |
|---|---|---:|
| Agent 도입 필요성 | 기존 방식 한계 5; Agent 판단 필요성 5; 일반 코드와 Agent 역할 구분 5 | 15 |
| 계획·정보·도구 선택 | 목표·계획 4; 정보·상태 4; 도구 역할·선택 조건 4; 실행 결과 활용 3 | 15 |
| 상황 대응 | 정상 시나리오 4; 조건 변경·재계획 6; 정보 부족·충돌·모호성 5; 실패·복구 5 | 20 |
| 결과 점검 | 완료 조건 4; 정확성·일관성 검증 4; 검증 실패 후속 행동 2 | 10 |
| 문제의 필요성 | 이용 대상·상황 5; 중요성 5; 유용성 5 | 15 |
| 실현 가능성 | 핵심 기술 5; 범위 5; 한계·미검증 사항 인식 5 | 15 |
| 이용 편의·명확성 | 상호작용 5; 전달력 5 | 10 |

Score each of 22 subcriteria independently: grade 0 = absent/not viable; 1 = abstract claim only; 2 = partial, core mechanism unclear; 3 = adequate, some conditions missing; 4 = concrete and consistent. Points = grade × maximum / 4. Sum without retroactive adjustment. Official Agentic total 60; other totals 15/15/10. Tie-break: Agentic total, then situation response.

Required checks: submission audit, Agent Necessity Test, Workflow Walkthrough, Scenario Stress Test, Outcome Verification, Feasibility Audit, Adversarial Review. Report score, source evidence, limitations, critical questions, and separate recommendations (P0/P1/P2). Avoid duplicate penalties without independent justification. Do not estimate award probability without data.

Follow this project's Meta Loop Protocol.

## Iteration Start (mandatory)

1. Read `.meta-loop/WHY.md`
2. Read `.meta-loop/PROGRESS.md`
3. Read `.meta-loop/DECISIONS.md`
4. Compare `.meta-loop/BASELINE.md` against current state
5. Record this iteration's objective in PROGRESS.md → begin work

## Work Principles

- 청크 I/O 준수 (Read/Write 800줄 이내)
- Edit 단위로 변경, 한 번에 한 슬라이드/한 섹션
- Decisions → DECISIONS.md
- 사실 왜곡 금지
- 막히면 subagent 스폰
- 자율 진행 (사용자 부재)

## Specific Work Order

### Iteration 1 — Baseline + Diagnosis
- index.html 청크별 통독 (200줄 단위)
- 슬라이드 51개 텍스트 추출 → 톤·내러티브 이슈 매핑
- BASELINE.md 작성
- Chrome 로컬 서버 띄우고 슬라이드 전수 시각 검수

### Iteration 2 — 콘텐츠 보정 (사실/내러티브)
- N7: S28 "AI 인프라의 심장" → "AI 인프라에서 어디가 병목인가"
- N8: S29-32 메모리 슬라이드 추론 시장 강조
- N9: "파산" 슬라이드 5대/680B 구체 숫자 → 개념 + 치킨게임 + 과소투자 공포

### Iteration 3 — 슬라이드 단위 수정
- N2: S19 Samsung 비유 → 비유로 이해하는 구조
- N3: S20 "코딩 성능"/"업무 성과" → "성능"
- N4: S21 멀티에이전트 Team 구조 재디자인
- N5: S22 line 529 "이 자료가 그 증거" 제거
- N6: S27 발표자료 자기자랑 슬라이드 톤다운

### Iteration 4 — 내러티브 ACT 재정렬 (필요 시)
- 산만한 부분 식별 → ACT 경계/순서 조정

### Iteration 5 — 톤 전수 정리
- N12: "대단/짜잔/만능/온몸으로/세계상위/저는지금" 등 grep
- 발견 항목 일괄 담백화

### Iteration 6 — 가시성
- N10a: html font-size 117% (체감 125%)
- N10b: 낮은 opacity 회색 일괄 상향
- N10c: 포인트 색 은은하게 (기존 팔레트 활용)

### Iteration 7 — Chrome QA + commit/push
- 전 슬라이드 시각 검수
- git commit + push

### Iteration 8 — Demo 링크 검증 (N11)
- "Demo — Claude Code 웹사이트 제작" 영상 URL 유효성
- 깨지면 공식 Anthropic 영상 대체

## Autonomous Constraints

- 질문 금지, 멈춤 금지
- 청크 I/O 절대 준수
- 디자인 시스템 보존 (흑/회 톤 + Figtree 폰트)
- 각 이터레이션 종료 시 git commit (push는 최종)

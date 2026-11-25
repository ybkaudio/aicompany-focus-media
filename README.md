# aicompany-focus-media — AI기업집중탐구(@aicompany.focus) 업로드 저장소

AI 쪽 Claude만 고침. 기업집중탐구(@company.focus) 파일은 ybkaudio/company-focus-media에 따로 있음. 규칙 원본: 프로젝트 파일 `ai-pack/rules/3-업로드.md`.

- 게시 방식(11/25부터): 정해진 시각 없음. 사용자가 맥북 Aside에 고정 프롬프트를 아무 때나 붙여 넣으면, `schedule.json`에서 posted=false인 편 중 queued가 가장 이른 한 편을 instagram.com에 올림.
- `posts/NN-slug/01.jpg…` + `caption.txt`: 렌더·점검을 통과한 편. Aside가 `https://raw.githubusercontent.com/ybkaudio/aicompany-focus-media/main/{folder}/…`로 내려받음.
- `schedule.json`: 편 목록. 칸 = queued(+09:00, 순서), folder(예: posts/01-openai), episode, count, first_line, music, posted(true/false). 칸 이름을 바꾸면 Aside 프롬프트도 같이 고침.
- 둘 다 `ai-pack/tools/publish_ai.py`가 씀. 손으로 고치지 않음. 이미 게시된 편의 caption.txt·first_line은 바꾸지 않음(중복 확인이 첫 줄 비교).
- 2026-11-24 14시 게시 뒤 company-focus-media/ai/ 에서 옮겨 옴(그때까지의 기록은 그 저장소 git 이력).

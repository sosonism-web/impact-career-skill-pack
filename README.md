# 🎁 Impact Career Builder (임팩트 경력기술서 & 커리어 확장 리포트 스킬셋)

> **"엑셀 시트 몇 줄의 숫자에 다 담기지 않는 당신의 체화된 문제해결력을 증명합니다."**

이 저장소는 정성적 지표가 많거나 정량 지표가 미미해 자신의 커리어를 증명하기 막막한 **임팩트 생태계(소셜벤처, 비영리, CSR/ESG, 로컬, 중간지원조직 등) 실무자**를 위한 AI 커리어 인터뷰 및 **A4 2-Page 경력기술서 & 커리어 확장 리포트 생성 스킬(Skill)**입니다.

---

## 📂 디렉토리 구조 (Skillset Structure)

AI 에이전트(Antigravity, Claude Code, Cursor 등)의 표준 스킬 및 플러그인 규격에 맞춰 설계되어 있습니다.

```text
impact-career-skill-pack/
├── plugin.json                                     # 플러그인 패키지 메타데이터
├── README.md                                       # 사용 가이드 및 GitHub 업로드 안내
├── STANDALONE_PROMPT.md                            # 일반 웹 AI(ChatGPT/Claude) 복붙용 단일 프롬프트
└── skills/
    └── impact-career-builder/
        ├── SKILL.md                                # 핵심 스킬 정의 및 5단계 인터뷰 워크플로우
        ├── references/
        │   └── career-mapping-framework.md         # 시장 직무 호환성 및 인접 산업 확장 매핑 데이터
        └── resources/
            └── impact-career-template.html         # PDF 원클릭 다운로드 버튼이 내장된 A4 2-Page HTML 템플릿
```

---

## 🚀 활용 방법 2가지

### 방법 1. 에이전트 스킬(Skill)로 설치하여 사용하기 (Antigravity / Claude Code 등)
1. **특정 프로젝트(워크스페이스)에서 사용할 때**:
   - 프로젝트 루트의 `.agents/skills/` 폴더 안에 `skills/impact-career-builder` 폴더를 복사해 넣습니다.
2. **내 컴퓨터 전역(Global)에서 사용할 때**:
   - `~/.gemini/config/skills/` (또는 `~/.gemini/config/plugins/`) 경로에 이 폴더를 넣습니다.
3. **실행**:
   - 채팅창에 `"임팩트 경력기술서 정리해줘"` 또는 `"올해 프로젝트 회고 도와줘"`라고 입력하면 스킬이 자동으로 활성화되어 1:1 인터뷰를 시작합니다.

### 방법 2. 일반 ChatGPT / Claude 웹 채팅창에서 사용하기
- [`STANDALONE_PROMPT.md`](./STANDALONE_PROMPT.md) 파일 안의 프롬프트 전문을 복사하여 ChatGPT나 Claude 대화창에 붙여넣으면 즉시 인터뷰와 PDF 다운로드 페이퍼 생성이 진행됩니다.

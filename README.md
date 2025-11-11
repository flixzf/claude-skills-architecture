# Claude Code 스킬 - 건축/건설 업무 문서 자동화

건축/건설 업무에 특화된 Claude Code 스킬 모음입니다.

## 스킬 목록

### 1. company-docs
회사 공식 문서 작성 지원 스킬

**지원 문서:**
- 공문
- 보고서
- 회의록
- 제안서
- 표준서
- 설문지

**사용법:**
```bash
/skill company-docs
```

**템플릿 위치:** `company-docs/templates/`

### 2. presentation
회사 프레젠테이션 작성 지원 스킬

**지원 프레젠테이션:**
- 사업 제안
- 기술 발표
- 실적 발표
- 기획 보고
- 프로젝트 보고
- BIM 워크샵
- 킥오프 미팅

**사용법:**
```bash
/skill presentation
```

**템플릿 위치:** `presentation/templates/`

## 설치 방법

### Claude Code에 스킬 추가하기

1. 이 저장소를 클론합니다:
```bash
git clone https://github.com/flixzf/claude-skills-architecture.git
```

2. `.claude/skills` 폴더에 복사합니다:
```bash
cp -r company-docs ~/.claude/skills/
cp -r presentation ~/.claude/skills/
```

3. Claude Code를 재시작합니다.

## 폴더 구조

```
skills/
├── company-docs/
│   ├── SKILL.md              # 스킬 정의 파일
│   ├── reference.md          # 참고 자료
│   └── templates/            # 문서 템플릿
│       ├── 공문.md
│       ├── 보고서.md
│       ├── 회의록.md
│       ├── 제안서.md
│       ├── 표준서.md
│       ├── 설문지.md
│       └── 설문지_템플릿.docx
└── presentation/
    ├── SKILL.md              # 스킬 정의 파일
    ├── reference.md          # 참고 자료
    └── templates/            # 프레젠테이션 템플릿
        ├── 사업제안.md
        ├── 기술발표.md
        ├── 실적발표.md
        ├── 기획보고.md
        ├── 프로젝트보고.md
        ├── BIM워크샵.md
        └── 킥오프미팅.md
```

## 사용 대상

건축/건설 업무 문서 자동화를 필요로 하는 프로젝트

## 버전 관리

이 저장소는 Git으로 버전 관리됩니다.

### 변경사항 커밋하기

```bash
git add .
git commit -m "변경 내용 설명"
git push
```

### 이전 버전으로 돌아가기

```bash
git log                    # 커밋 히스토리 확인
git checkout [커밋 해시]   # 특정 커밋으로 이동
```

## 라이센스

MIT License

## 업데이트 내역

- 2025-11-11: Git 저장소 초기화
- 2025-11-06: presentation 스킬 추가
- 2025-11-05: company-docs 스킬 생성

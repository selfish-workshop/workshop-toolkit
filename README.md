# workshop-toolkit

GitHub 협업 워크숍을 위한 Claude Code 슬래시 커맨드 모음입니다. 이 레포는 워크숍 참여자 전용 **Claude Code 플러그인 마켓플레이스**로 동작합니다.

## 설치 가이드 (워크숍 참여자용)

Claude Desktop 앱의 **Code 탭**을 열고 아래 두 커맨드를 순서대로 입력하세요.

### 1. 마켓플레이스 등록

```
/plugin marketplace add selfish-workshop/workshop-toolkit
```

### 2. 플러그인 설치

```
/plugin install website-prd-builder@workshop-toolkit
```

설치가 완료되면 Claude Code 세션을 다시 시작해 주세요.

## 사용법

Code 탭에서 아래 커맨드를 입력하면 PRD 프레임과 팀별 폴더가 자동으로 생성됩니다.

```
/website-prd
```

## 포함된 플러그인

| 플러그인 | 커맨드 | 설명 |
|---|---|---|
| `website-prd-builder` | `/website-prd` | 웹사이트/웹서비스 PRD 프레임 자동 생성 + 5개 팀(기획/디자인/CX/마케팅/전략) 폴더 구조 생성 + GitHub 푸시 |

## 문의

- 운영: Selfish Club Workshop
- 이메일: cs.selfishclub@gmail.com

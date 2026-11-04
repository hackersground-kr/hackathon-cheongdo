# 청도 바이브코딩 해커톤

청도 바이브코딩 해커톤 참가자를 위한 안내입니다. 행사 관련 최신 공지는 [청도 해커톤 안내 페이지](https://hackersground.kr/hackathons/cheongdo)에서 확인해 주세요.

## 행사 정보

- 진행 방식: 웹 앱 개발
- 사용 언어: 자유
- 배포 플랫폼: Azure
- 사용 도구: [VS Code + GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot-chat), [GitHub Copilot CLI](https://docs.github.com/copilot/how-tos/copilot-cli), [GitHub Copilot app](https://docs.github.com/copilot/how-tos/github-copilot-app). 타사 AI 코딩 도구는 사용할 수 없습니다.
- 도전 과제와 세부 일정: 행사 안내 페이지의 공지를 확인해 주세요.

## 참가 순서

### 1. 체크인 및 GitHub 핸들 등록

체크인할 때 운영진에게 GitHub 핸들을 알려 주세요. 이메일 주소가 아닌 GitHub 핸들을 사용하며, 계정에 GitHub Copilot 라이선스가 활성화되어 있어야 합니다. 운영진이 핸들을 등록한 뒤 팀 등록을 진행할 수 있습니다.

### 2. 팀 등록

결과 제출 전에 팀을 등록해 주세요. 팀 리더가 본인의 GitHub 계정으로 [팀 등록 양식](https://github.com/hackersground-kr/hackathon-cheongdo/issues/new/choose)을 제출해야 합니다. 팀원은 GitHub 핸들로 입력하고, 혼자 참가하는 경우 팀원 항목은 비워 둘 수 있습니다.

- 먼저 참가자 핸들이 등록되어 있어야 합니다.
- 한 참가자는 하나의 팀에만 소속될 수 있습니다.
- 팀 이름은 다른 팀과 중복될 수 없습니다(대소문자 구분 없음).
- 팀 등록 마감은 따로 없지만, 앱 결과를 제출하기 전에 등록해야 합니다.
- 같은 팀 리더가 양식을 다시 제출하면 새 팀이 생기는 대신 기존 팀 정보가 갱신됩니다.

### 3. 앱 개발 및 배포

웹 앱을 개발해 Azure에 배포해 주세요. 심사 항목에는 **GitHub Copilot SDK와 Microsoft Agent Framework의 효과적인 활용**이 포함됩니다. 전체 평가 기준은 [해커톤 평가 기준](./judgement/judgement-criteria.md)에서 확인할 수 있습니다.

### 4. 결과 제출

팀 등록 후 팀 리더가 [결과 제출 양식](https://github.com/hackersground-kr/hackathon-cheongdo/issues/new/choose)을 작성해 주세요.

- 제출 마감: **2026년 11월 5일 16시 30분 (한국 시각)**
- 팀당 최대 2회 제출할 수 있으며, **가장 나중에 제출한 내용**을 기준으로 평가합니다.
- 팀 리더 본인의 **공개 GitHub 저장소**를 제출해야 합니다.
- 저장소 루트에 `PRD.md`와 `TRD.md`를 포함하고, 심사할 커밋 해시와 앱 배포 URL을 제출해 주세요.
- 앱은 Azure에 배포해야 하며, `*.azurewebsites.net`, `*.azurecontainerapps.io`, `*.azurestaticapps.net` 등의 Azure 기본 도메인 URL을 사용해야 합니다. 커스텀 도메인은 허용되지 않습니다.
- 심사 에이전트가 로그인이나 별도 자격 증명 없이 앱의 핵심 기능을 사용할 수 있어야 합니다. 심사에 필요한 핵심 기능을 공개적으로 접근 가능하도록 준비해 주세요.
- 제출 이슈는 공개되므로 비밀번호, 토큰 등 자격 증명을 입력하지 마세요.
- 심사는 AI 에이전트가 저장소의 `PRD.md`, `TRD.md`와 앱의 실제 동작을 중심으로 진행합니다. `README.md`는 보조 자료입니다.

## 참가 등록 및 현황

- 참가자 핸들 등록, 팀 등록, 앱 결과 제출은 [양식 선택 페이지](https://github.com/hackersground-kr/hackathon-cheongdo/issues/new/choose)에서 진행합니다.
- 제출 결과와 심사 현황은 [리더보드](https://hackersground.kr/hackathons/cheongdo/leaderboard)에서 확인할 수 있습니다.

# 제미나이 Gems로 만드는 활동지 웹앱

초등학교 교사 연수용 인터랙티브 HTML 프레젠테이션입니다. (30장, 단일 HTML 파일)

## 파일 구성

| 파일 | 설명 |
|---|---|
| `index.html` | 발표 자료 전체 (HTML·CSS·JS와 활동지 이미지가 모두 들어 있음) |
| `README.md` | 이 안내 문서 |

## 실행 방법

- **내 컴퓨터에서:** `index.html`을 크롬·엣지·웨일·사파리로 열면 됩니다. 서버가 필요 없습니다.
- **인터넷 주소로:** 아래 GitHub Pages 배포를 따라 하세요.
- 주소 끝에 `#16`을 붙이면 16번 슬라이드로 바로 이동합니다.

## 발표 조작

| 키 | 기능 |
|---|---|
| → ↓ Space PageDown | 다음 단계 / 다음 슬라이드 |
| ← ↑ Shift+Space PageUp | 이전 |
| Home / End | 처음 / 끝 |
| F | 전체화면 |
| M | 모션 줄이기 |
| T | 디자인 바꾸기 (기본 · 클레이모피즘 · 글래스모피즘) |

## GitHub Pages로 배포하기

1. GitHub에 로그인한 뒤 오른쪽 위 **+ → New repository**를 누릅니다.
2. Repository name에 `gems-webapp-training`을 입력하고 **Public**을 선택한 뒤 **Create repository**를 누릅니다.
3. 새 저장소 화면에서 **uploading an existing file**(또는 **Add file → Upload files**)을 누릅니다.
4. `index.html`과 `README.md`를 끌어다 놓고 **Commit changes**를 누릅니다.
5. 저장소의 **Settings → Pages**로 이동합니다.
6. **Build and deployment**의 Source를 **Deploy from a branch**로, Branch를 **main / (root)**로 정하고 **Save**를 누릅니다.
7. 1~2분 뒤 페이지를 새로고침하면 위쪽에 주소가 나타납니다.
   `https://<내 GitHub 아이디>.github.io/gems-webapp-training/`

내용을 고친 뒤에는 `index.html`을 다시 업로드(같은 이름으로 덮어쓰기)하면 1~2분 뒤 같은 주소에 반영됩니다.

## 참고

- Public 저장소와 GitHub Pages는 누구나 볼 수 있습니다. 활동지 이미지(책 표지 포함)를 공개해도 되는지 확인하세요.
- 슬라이드 속 학생 이름과 답안은 연수용 예시입니다.
- 외부 리소스는 Pretendard 웹폰트(jsDelivr CDN) 하나뿐이며, 연결이 안 되면 시스템 글꼴로 대체됩니다.

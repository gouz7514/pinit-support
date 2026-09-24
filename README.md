# pinit 지원 사이트

App Store에 제출한 **지원 URL**과 **개인정보 처리방침 URL**이 가리키는 정적 사이트다.
GitHub Pages로 배포되며, `main`에 푸시하면 몇 분 안에 반영된다.

- 지원: https://gouz7514.github.io/pinit-support/
- 개인정보 처리방침: https://gouz7514.github.io/pinit-support/privacy.html

## 구성

| 파일 | 용도 |
|---|---|
| `index.html` | 지원 페이지 (FAQ, 한국어 + 영어) |
| `privacy.html` | 개인정보 처리방침 (한국어 + 영어) |
| `style.css` | 애플 기본 앱 톤, 라이트/다크 자동 |
| `logo.png` | 앱 아이콘 128px |

빌드 단계와 JS가 없다. 원문은 앱 저장소의 `docs/support.md`, `docs/privacy.md`다.

## 내용을 고칠 때

처리방침 본문을 바꾸면 위쪽 최종 수정일도 함께 고칠 것.

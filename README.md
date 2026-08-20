# 성전으로 가는 한 주

예수 그리스도 후기 성도 교회 회원을 위한 가족 역사 · 성전 준비 안내 페이지.
2026년 8월 24일(월)부터 29일(토)까지, 하루치 미션을 따라가면 패밀리트리에 조상을
올리고 성전에 가져갈 QR 코드까지 준비됩니다.

여는 날짜(한국 표준시)에 맞춰 해당 일자로 자동 스크롤되고, 단계별 체크는 브라우저에
저장됩니다.

## 파일

| 경로 | 용도 |
| --- | --- |
| `docs/index.html` | 공지 목록 페이지 (사이트 첫 화면) |
| `docs/temple-week/index.html` | **성전으로 가는 한 주.** doctype·viewport·`lang="ko"`·OG 태그를 갖춘 독립 문서 |
| `docs/temple-week/og.jpg` | 카카오톡·페이스북 공유 미리보기 이미지 (1200×630) |
| `index.html` | Claude Artifact 전용 사본. `<head>`가 없으므로 웹 서버에 직접 올리지 말 것 |

안내를 새로 추가할 때는 `docs/<이름>/` 폴더를 만들고 `docs/index.html`의 목록에 항목을
한 줄 넣으면 됩니다.

이미지는 모두 파일 안에 data URI로 들어 있어 외부 요청은 Google Fonts뿐입니다.

## 배포 (GitHub Pages)

**Settings → Pages → Source: `main` 브랜치 / `/docs` 폴더**

- 목록 <https://trustspirit.github.io/announcements/>
- 성전으로 가는 한 주 <https://trustspirit.github.io/announcements/temple-week/>

`og:url`과 `og:image`는 위 주소로 이미 채워져 있습니다. 폴더 이름을 바꾸면 각
`index.html` 머리말의 두 줄도 함께 고쳐야 카카오톡 미리보기가 뜹니다.

## 자료 출처

- 앱 화면 — [FamilySearch](https://www.familysearch.org/ko/) (한국 App Store 스크린샷)
- 제적등본 화면 — [대법원 전자가족관계등록시스템](https://efamily.scourt.go.kr)
- 서울 성전 사진 — [교회 뉴스룸](https://newsroom.churchofjesuschrist.org/article/seoul-korea-temple)

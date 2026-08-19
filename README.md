# HADES — 건강도시아틀라스 고도화 연구단 홈페이지

건강도시 문제해결을 위한 의사결정지원도구로서 건강도시아틀라스 고도화 연구(HADES)
연구단 공식 홈페이지입니다. Jekyll로 만들어져 GitHub Pages에서 자동으로 빌드됩니다.

- 홈페이지: https://hpolicy.github.io/hcityatlas/
- 소식 게시판: 홈페이지의 "소식" 섹션 및 /news/ 페이지

---

## ✏️ 소식 글쓰기 (연구진용)

### 방법 1 — 웹에서 바로 글쓰기 (권장, 지금 바로 사용 가능)

1. GitHub에 로그인한 상태에서 아래 링크를 클릭하면 글 양식이 미리 채워진 편집 화면이 열립니다.

   👉 [**새 소식 글쓰기**](https://github.com/hpolicy/hcityatlas/new/main/_posts?filename=2026-08-20-post.md&value=---%0Alayout%3A%20post%0Atitle%3A%20%22%EC%97%AC%EA%B8%B0%EC%97%90%20%EC%A0%9C%EB%AA%A9%EC%9D%84%20%EC%93%B0%EC%84%B8%EC%9A%94%22%0Adate%3A%202026-08-20%2010%3A00%3A00%20%2B0900%0A---%0A%0A%EC%97%AC%EA%B8%B0%EC%97%90%20%EB%B3%B8%EB%AC%B8%EC%9D%84%20%EC%93%B0%EC%84%B8%EC%9A%94.%0A%0A%EC%82%AC%EC%A7%84%EC%9D%84%20%EB%84%A3%EC%9C%BC%EB%A0%A4%EB%A9%B4%20assets%2Fimages%2Fuploads%20%ED%8F%B4%EB%8D%94%EC%97%90%20%EB%A8%BC%EC%A0%80%20%EC%82%AC%EC%A7%84%EC%9D%84%20%EC%98%AC%EB%A6%B0%20%EB%92%A4%20%EC%95%84%EB%9E%98%20%ED%98%95%EC%8B%9D%EC%9C%BC%EB%A1%9C%20%EC%94%81%EB%8B%88%EB%8B%A4.%0A%0A%21%5B%EC%82%AC%EC%A7%84%20%EC%84%A4%EB%AA%85%5D%28%2Fhcityatlas%2Fassets%2Fimages%2Fuploads%2F%ED%8C%8C%EC%9D%BC%EB%AA%85.jpg%29%0A)

2. 파일명을 실제 날짜와 제목으로 바꿉니다. 형식: `연도-월-일-영문제목.md` (예: `2026-09-01-symposium.md`)
3. 본문에서 `title`과 `date`, 내용을 수정합니다.
4. 오른쪽 위 **Commit changes** → 다시 **Commit changes** 를 누르면 1~2분 내에 홈페이지에 게시됩니다.

### 사진 올리기

1. 저장소에서 `assets/images/uploads` 폴더로 이동합니다.
2. **Add file → Upload files** 로 사진을 끌어다 놓고 **Commit changes**.
3. 글 본문에 아래 형식으로 넣습니다.

   ```
   ![사진 설명](/hcityatlas/assets/images/uploads/파일명.jpg)
   ```

   ※ 커스텀 도메인(hcityatlas.org) 연결 후에는 `/hcityatlas` 부분을 빼고 `/assets/images/uploads/파일명.jpg` 로 씁니다.

### 방법 2 — /admin 관리자 페이지 (Decap CMS)

`admin/` 폴더에 웹 에디터(Decap CMS)가 포함되어 있습니다. GitHub 로그인 버튼이 작동하려면
OAuth 연동(무료, Cloudflare Workers 등)이 한 번 필요합니다. 연동 후에는
`https://<홈페이지주소>/admin/` 에서 로그인해 워드프로세서처럼 글과 사진을 올릴 수 있습니다.
연동 방법은 `admin/config.yml` 의 주석을 참고하세요.

---

## ⚙️ 관리 메모

- 글은 `_posts/` 폴더의 마크다운 파일 하나가 게시글 하나입니다. 파일을 삭제하면 글이 내려갑니다.
- 커스텀 도메인 연결 시 `_config.yml` 의 `url`/`baseurl` 주석을 참고해 두 줄을 수정하세요.
- 연구진에게 글쓰기 권한을 주려면: Settings → Collaborators → **Add people** 로 GitHub 계정을 초대합니다.

문의: 김기훈 (elitegroup93@korea.ac.kr)

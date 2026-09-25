KeyHelper — GitHub Pages 배포 안내
==================================

이 폴더 안 파일들 (index.html, manifest.json, icon-192.png, icon-512.png,
apple-touch-icon.png)을 그대로 GitHub Pages에 올리면 링크 하나로 누구나
접속해서 쓸 수 있고, 갤럭시(안드로이드) 홈 화면에 추가하면 "KeyHelper"
이름과 건반 아이콘으로 뜹니다. 외부 서버나 구글시트는 전혀 쓰지 않는
완전히 독립적인 정적 웹앱입니다.

1) GitHub 저장소 만들기
   - github.com 에서 로그인 후 우측 상단 + 버튼 → New repository
   - 저장소 이름은 아무거나 (예: keyhelper), Public으로 생성

2) 파일 업로드
   - 방금 만든 저장소 페이지에서 "Add file" → "Upload files"
   - 이 폴더에 있는 5개 파일(index.html, manifest.json, icon-192.png,
     icon-512.png, apple-touch-icon.png)을 그대로 끌어다 놓고 Commit

3) GitHub Pages 켜기
   - 저장소의 Settings → 왼쪽 메뉴 Pages
   - "Branch" 를 main(또는 master), 폴더는 / (root) 로 선택 후 Save
   - 잠시 기다리면 상단에 주소가 뜹니다:
     https://내아이디.github.io/저장소이름/

4) 링크 확인 및 공유
   - 그 주소로 접속해서 코드구성음 · 전조 · 리하모니 · 진행 조 바꾸기가
     잘 작동하는지 한 번씩 눌러 확인합니다.
   - 이 링크를 카카오톡, 문자 등으로 사람들에게 보내면 누구나 클릭해서
     바로 쓸 수 있습니다.

5) 갤럭시 홈 화면에 아이콘으로 추가하기
   - 갤럭시 크롬으로 그 주소에 접속
   - 오른쪽 위 점 세 개(⋮) 메뉴 → "앱 설치" 또는 "홈 화면에 추가"
   - manifest.json에 설정된 이름(KeyHelper)과 건반 아이콘으로 홈 화면에
     생기고, 이후로는 일반 앱처럼 탭 한 번으로 켤 수 있습니다.

참고
- 커뮤니티 라이브러리(공유) 기능은 이번 버전에서 빠졌습니다. 코드구성음,
  전조 코드진행, 리하모니, 그리고 개인용 "코드 진행 조 바꾸기"(재생 포함)
  는 그대로 있고, 외부 서버 없이 그 자리에서 모두 계산·재생됩니다.
- 아이콘을 바꾸고 싶으면 icon-192.png / icon-512.png / apple-touch-icon.png
  파일만 같은 이름으로 교체해서 다시 업로드하면 됩니다.
- 내용을 수정한 뒤에는 GitHub 저장소에 파일을 다시 업로드(Commit)하면
  몇 분 안에 실제 주소에도 반영됩니다.

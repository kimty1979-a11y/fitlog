FIT LOG v0.5 — 아이폰 설치형 PWA

1. PC에서 index.html을 더블클릭하면 기존처럼 로컬 테스트할 수 있습니다.
2. 아이폰에 설치하려면 이 폴더의 파일 전체를 HTTPS 웹 호스팅에 게시해야 합니다.
3. 예: GitHub Pages (개인 GitHub 계정 필요)
   - 개인 PC 또는 허용된 환경에서 새 공개 저장소를 생성합니다.
   - 이 폴더 안의 파일(index.html, manifest.webmanifest, sw.js, icon PNG)을 저장소 최상위에 올립니다.
   - Settings > Pages > Deploy from a branch > main / (root) > Save.
   - 발급된 https://계정.github.io/저장소/ 주소에 접속합니다.
4. 아이폰 Safari에서 해당 HTTPS 주소를 열고 공유 > 홈 화면에 추가를 누릅니다.

주의: 회사에서 파일 업로드가 금지되어 있다면 회사 PC에서 업로드하지 마세요. 개인 기기나 정책상 허용된 환경에서 배포하세요.
주의: GitHub Pages 공개 저장소의 소스코드는 공개됩니다. 개인 운동/식단 기록은 코드에 넣지 마세요.
주의: 기록은 각 기기의 브라우저 저장소(localStorage)에 저장되며 다른 기기로 자동 동기화되지 않습니다.
주의: 현재 사진 AI 영양 분석은 미구현이며 사진은 미리보기만 지원합니다.
주의: 호스팅 URL을 바꾸거나 Safari 웹사이트 데이터를 삭제하면 기존 기록에 접근하지 못할 수 있습니다.
주의: 이전 file:// 방식의 v0.3/v0.4 데이터는 새 HTTPS 주소로 자동 이전되지 않습니다.

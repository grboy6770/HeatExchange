CORE45 HEAT EXCHANGE — 배포 폴더

이 폴더 전체를 GitHub 저장소 루트에 올리세요.
index.html / support.js / delivery-map.html / crops/ / .nojekyll 이 같은 위치에 있어야 합니다.

1) GitHub: 새 저장소 → 파일 업로드(이 폴더 안의 내용 전부) → Settings → Pages → Branch: main / root → Save
2) Cloudflare 도메인 연결: Pages 설정의 Custom domain에 도메인 입력 →
   Cloudflare DNS에 CNAME (이름: 서브도메인 또는 @, 값: <github아이디>.github.io) 추가, 프록시는 DNS only(회색 구름) 권장
3) GitHub Pages 설정에서 Enforce HTTPS 체크

아이패드: Safari로 접속 → 공유 → 홈 화면에 추가 → 설정 > 손쉬운 사용 > 사용법 유도 켜기
작물 이미지 교체: crops/ 폴더의 같은 파일명으로 덮어쓰기

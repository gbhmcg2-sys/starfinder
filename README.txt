별자리 찾기 — 설치형 앱(PWA) 패키지
====================================

[들어 있는 파일]
  index.html            앱 본체 (맨 위 CONFIG에서 이름·색·미션·프리셋·신화 이야기를 고칠 수 있어요)
  three.min.js          3D 엔진 (앱 안에 들어 있어서 인터넷이 필요 없어요)
  manifest.webmanifest  앱 이름·아이콘·전체화면 설정
  sw.js                 인터넷 없이 실행되게 해 주는 파일 (VERSION 값이 들어 있어요)
  privacy.html          개인정보처리방침 (맨 아래 운영자 이름·이메일 칸을 채워 주세요)
  icons/                앱 아이콘 4종
  fonts/                한글 글꼴 2종 (주아, 고운돋움 — 자유롭게 쓸 수 있는 OFL 글꼴, 사용 조건은 fonts/OFL.txt)
  README.txt            이 안내서


[깃허브 페이지에 올리는 방법 — 처음 한 번]
1. github.com 에 로그인하고 오른쪽 위 ＋ 버튼 → New repository 를 눌러요.
2. Repository name 에 starfinder 라고 쓰고, Public 을 고른 뒤 Create repository 를 눌러요.
3. 새 저장소 화면에서 "uploading an existing file" 글자(또는 Add file → Upload files)를 눌러요.
4. ★ 받은 zip 파일의 압축을 먼저 풀어요.
   ★ 압축을 푼 폴더 "안의" 파일과 폴더를 전부 골라서 업로드 화면에 끌어다 놓아요.
     (index.html, three.min.js, manifest.webmanifest, sw.js, privacy.html, README.txt, icons 폴더, fonts 폴더)
   ★ 폴더째 올리면 안 돼요. index.html 이 저장소 맨 위(첫 화면 목록)에 바로 보여야 해요.
5. 아래쪽 Commit changes 를 눌러요.
6. 저장소 위쪽 Settings → 왼쪽 Pages 를 눌러요.
   Branch 에서 main 과 / (root) 를 고르고 Save 를 눌러요.
7. 1~2분 뒤 아래 주소로 들어가면 앱이 열려요.
   https://gbhmcg2-sys.github.io/starfinder/
8. 휴대폰으로 열고 아래 패널의 "앱 설치" 버튼을 누르면 홈 화면에 설치돼요.
   (아이폰은 Safari → 공유 버튼 → 홈 화면에 추가)


[수정본을 올릴 때]
1. 새로 받은 zip의 압축을 풀어요.
2. 저장소에서 Add file → Upload files 를 누르고, 압축을 푼 폴더 안의 파일을 전부 다시 끌어다 놓은 뒤 Commit changes 를 눌러요.
   (같은 이름의 파일은 새 파일로 바뀌어요. index.html 은 계속 저장소 맨 위에 있어야 해요.)
3. ★ 새 버전은 앱을 "두 번째" 열 때부터 보여요.
   처음 열 때 새 파일을 몰래 받아 두고, 다음에 열 때 바뀐 화면이 나와요.
   (수정본마다 sw.js 안의 VERSION 값이 바뀌어 있어서 자동으로 새로 받아요.)


[알아 두면 좋은 것]
- 위치·방향 센서·카메라는 https 주소(깃허브 페이지)에서만 동작해요. 내 컴퓨터에서 파일을 바로 열면 이 기능은 꺼져요.
- 한 번 열고 나면 인터넷이 없어도 실행돼요.
- 광고, 회원 가입, 개인정보 수집, 이용 추적이 없어요.

현재 버전: starfinder-v3 ("내 위치" 버튼: 휴대폰 방향의 하늘 보여 주기)

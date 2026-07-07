# WAM Releases

[WAM (Work As a Map)](https://github.com/jaywapp/wam)의 **설치본 배포 저장소**입니다.
앱 소스는 비공개이며, 여기에는 Windows 설치 프로그램만 공개 배포됩니다.

## 다운로드

최신 설치본은 [Releases](https://github.com/jaywapp/wam-releases/releases)에서 받으세요.

- 파일: `WAM-Setup-<version>.exe`
- **현재 사용자 전용 설치**(관리자 권한 불필요). 실행 후 안내를 따르면 됩니다.
- self-contained 빌드라 별도 .NET 런타임 설치가 필요 없습니다.

## 릴리스 방식

WAM 저장소에서 앱 버전이 올라가면 CI가 설치본을 빌드해 이 저장소의 Releases로
자동 게시합니다. 이 저장소에는 소스 코드가 없습니다.

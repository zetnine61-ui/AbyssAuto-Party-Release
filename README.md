# AbyssAuto-Party-Release

Abyss Auto **파티장 전용 클라이언트**의 공개 배포 파일 저장소입니다. 파티 프로그램 소스코드는 비공개 `abyss-auto-party` 저장소에서 관리합니다.

- 정식 릴리스: [최신 버전](https://github.com/zetnine61-ui/AbyssAuto-Party-Release/releases/latest)
- 매니페스트: `https://github.com/zetnine61-ui/AbyssAuto-Party-Release/releases/latest/download/update.json`
- 제품 식별자: `Product=Party`
- 독립 설치 경로: `%ProgramFiles%\AbyssAuto-Party`
- 솔로 배포 저장소 `AbyssAuto-Release`와 업데이트 경로, 설치 위치가 분리돼 있습니다.

파티 **v1.0.2 (base 솔로 v5.3.5)**부터 프로그램 실행 시 업데이트를 확인하고 10초 안내창을 표시합니다. v1.0.1은 자동 업데이트 기능이 없으므로 v1.0.2를 **한 번 직접 설치**해야 합니다.

업데이트 시 `config/party-settings.json`, `party-logs`, `party-errors`, `party-reports` 및 일반 `logs`, `errors`, `reports` 폴더를 보존합니다. 캐릭터 이름은 별도 LocalAppData 저장 경로에 있으며 런처는 해당 경로를 건드리지 않습니다.

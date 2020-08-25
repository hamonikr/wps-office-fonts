# hamonize-connect

하모나이즈 커넥터는 중앙관리 프로그램 하모나이즈 센터에 쉬운 연동을 지원하는 프로그램입니다.

## 주요기능

 * 하모나이즈 센터 사용을 위한 메타데이터 생성
 * 하모나이즈 센터 연동을 위한 Split Tunneling 설정 
 * 모든 데이터는 AES-256-CBC(256Bit) 블록모드 알고리즘으로 암호화 전송
 * 하모나이즈 센터와 연동을 위한 LDAP 서버 또는 Active Directory 서버에 기기 등록
 * 전용 APT 서버 추가
 * 하모나이즈 에이전트 자동 설치 
 * PC방 관리 프로그램 자동 설치 
 * guest 계정 활성화 및 자동 로그인 설정
 * PC 주변장치 제어 프로그램 설치 (usb, 키보드, 마우스, 스캐너, 웹캠, 프린터 등)
 * 백업 복구 기능 사용을 위한 초기 백업 스냅샷 생성


## 데비안 패키지 빌드

다운로드 받은 디렉토리 안에서 아래와 같이 빌드하면 release 폴더 안에 설치 가능한 데비안 파일 생성

```
./build
```

## 프로그램 설치

```
sudo dpkg -i release/hamonize-connect-*_amd64.deb
```

## 프로그램 삭제

```
sudo apt purge hamonize-connect
```

## 버그 또는 이슈 제출

사용 중 발견한 버그나 이슈는 help@hamonikr.org 로 메일을 보내주세요

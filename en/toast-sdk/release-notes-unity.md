## TOAST > User Guide for TOAST SDK > Release Notes > Unity

## 0.21.2 (2020.10.05)

### plugin version

- Android : 0.23.2

## 0.21.1 (2020.09.16)

### plugin version

- Android : 0.23.1
- iOS : 0.27.0

### Common 

- Native Plugin Version Update

## 0.20.3 (2020.07.10)

### plugin version

- Android : 0.22.0
- iOS : 0.25.1

### 버그 수정

- InstanceLogger 사용시, 암호화키를 호출하지 않는 버그 수정

## 0.20.2 (2020.07.08)

### plugin version

- Android : 0.22.0
- iOS : 0.25.1

### Common 

- Native Plugin Version Update

## 0.20.1 (2020.06.23)

### plugin version

- Android : 0.21.0
- iOS : 0.23.0

### Fixed

- 빈 파일이 생성된 경우, 복호화 에러 수정

### Enhanced

- Windows 환경에서 C++ DLL 의존성 제거


## 0.20.0 (2020.03.26)

### plugin version

- Android : 0.21.0
- iOS : 0.23.0

### 버그 수정

- CrashFilter관련 처리에서 Exception 이슈

## 0.19.1 (2020.01.23)

### 버그 수정

- OnHandleException 콜백 호출 이슈

## 0.19.0 (2019.12.27)

### Added

- Unity Play Services Resolver 적용

## 0.18.0 (2019.12.06)

### Common

- iOS 0.20.1 framework 적용
- Android 0.19.4 aar 포함해서 배포
- Native Plugin (Windows, MacOS) 배포

## 0.17.0 (2019.10.02)

### TOAST IAP

- 구매 요청시 사용자 데이터 설정 기능 추가

## 0.16.0 (2019.08.28)

### TOAST IAP

#### Changed

- 소비성 구독 상품 추가

## 0.15.1 (2019.07.29)

### Common

- iOS 0.16.1 framework 적용

## 0.15.0 (2019.07.23)

### TOAST IAP

#### Changed

- ActivedPurchases -> ActivatedPurchses

## 0.14.0 (2019.07.02)

### TOAST Log & Crash

#### Added

- Unity Standalone/WebGL 버전 추가
  - Logger
  - Instance Logger

### TOAST IAP

#### Added

- ActivedPurchases 추가

## 0.13.1 (2019.03.26)

### TOAST Log & Crash

#### Improved

- Improved to be able to send logs on non-unity thread.
- Rename ProjectKey to AppKey
  - setProjectKey is still available

#### Fixed

- Fixed a issue that sends a unexpected SDK exception when message is empty in Android.

## 0.13.0 (2019.02.26)

### TOAST Log & Crash

#### Added

- Add a feature that filter crash logs

## 0.12.0 (2019.01.08)

### TOAST IAP

#### Added

- Add module

## 0.11.0 (2018.12.27)

### TOAST Log & Crash

#### Added

- Add a feature that sends automatically unexpected exception logs that occurs in Unity
- SetCrashListener API

## 0.10.0 (2018.11.20)

### TOAST Log & Crash

#### Added

- SetLoggerListener API
- Support of Network Insights

#### Changed

- Removed mainTemplate.gradle from Unity Package
  - See guide for setting of mainTemplate.gradle

## 0.9.0 (2018.09.04)

### TOAST Log & Crash

#### Added

- Add module

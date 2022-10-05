# Cordova-tutorial
참고: https://cordova.apache.org/docs/en/11.x/guide/platforms/ios/

<br>

---

### 환경 세팅

1. Xcode CLI Tools 설치 
```xcode-select --install```
2. Homebrew 설치
```/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"```
3. 경로에 Homebrew 추가
```eval "$(/opt/homebrew/bin/brew shellenv)"```
4. Deployment tool 설치
```brew install ios-deploy```
5. CocoaPods 설치
```sudo gem install cocoapods```

<br>

### 프로젝트 생성

- Cordova CLI 설치
  - [여기서](https://nodejs.org/en/download/node.js) node.js 설치
  - Cordova module 설치 ```sudo npm install -g cordova```
1. Cordova 프로젝트 생성
```cordova create hello com.example.hello HelloWorld```
2. 프로젝트 디렉토리로 이동 ```cd hello```
3. 플랫폼 설정
```cordova platform add ios```
  > 현재 설정 된 플랫폼 확인 

  <img width="461" alt="스크린샷 2022-10-05 오후 3 21 52" src="https://user-images.githubusercontent.com/65107199/193994328-e9152d6b-1b3a-4b20-bf6d-1c11159ec263.png">
  
  
  > 빌드를 위한 요구사항 설치 확인

  <img width="426" alt="스크린샷 2022-10-05 오후 3 23 20" src="https://user-images.githubusercontent.com/65107199/193994538-7c3c8e09-6bfd-4e79-af26-47e4548a4493.png">
  
4. 시뮬레이터로 실행
```cordova emulate ios```

  <img width="226" alt="스크린샷 2022-10-05 오후 3 23 20" src="https://user-images.githubusercontent.com/65107199/193999668-c7cbee0d-1e83-4e0d-a70d-a91cce40cb0a.png">


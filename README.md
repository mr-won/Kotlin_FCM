# Kotlin_FCM
FCM(Firebase Cloud Messaging)을 이용한 백그라운드 알림 기능 구현     
[FCM 참고 문헌](https://devforyou.tistory.com/62)       
[팀노바 FCM](https://stickode.tistory.com/335)       
[FCM](https://minchanyoun.tistory.com/101)

#### FCM Architecture
![image](https://github.com/mr-won/Kotlin_FCM/assets/58906858/499c8018-fd8f-4e3e-943e-39a93fc49e8c)

#### App Gradle
![image](https://github.com/mr-won/Kotlin_FCM/assets/58906858/f0719a3a-03fa-4004-8570-8b70b6dc07df)
```
FCM 관련 의존성을 주입한다.
```
#### MainActivity에서 기기 토큰값 받아오는 함수 호출
![image](https://github.com/mr-won/Kotlin_FCM/assets/58906858/edc46d51-b259-4a55-9b0a-24cb27da9ce8)

#### AndroidManifest Service 추가
![image](https://github.com/mr-won/Kotlin_FCM/assets/58906858/c9504658-6b5a-4a48-bdd6-6a84f8aec837)

# splash-screen
A splash screen is mostly the first screen of the app when it is opened.  
It is a constant screen which appears for a specific amount of time, generally shows for the first time when the app is launched.   
The Splash screen is used to display some basic introductory information such as the company logo, content, etc just before the app loads completely.

### Files structure
```
├── app
│   ├── java
|   |   ├── MainActivity.kt
|   |   ├── SplashScreen.kt
│   ├── res
|   |   ├── drawable
│   |   |   ├── Folable.png
│   |   |   ├── ic_launcher_foreground.xml
│   |   |   ├── phone.png
|   |   ├── layout
|   |   |   ├── activity_main
|   |   |   ├── activity_splash_screen.xml
└── README.md
```
I just put the files that need. first you sould create new project and add two activities, one of them for showing splash screen (it must set as launcher) and one is MainActivity and i used the default android icon and color brand for splash screen look like below.<br>  
![Phone view](https://raw.githubusercontent.com/mitiebh/splash-screen/main/app/res/drawable/phone.png)
![Foldable view](https://raw.githubusercontent.com/mitiebh/splash-screen/main/app/res/drawable/Foldable.png)

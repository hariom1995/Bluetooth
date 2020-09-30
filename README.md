Bluetooth Integration in React Native
    
As per resource, We have two types of Bluetooth 
    1) BLE(Bluetooth Low Energy)
    2) Bluetooth Classic

 

My motivation to establish a connection between two Bluetooth Classic devices and Subscribe the data(getting continuously data);

 

for achieving the above task am using "React-Native-bluetooth-serial" lib
but In a development phase, I am getting All Bluetooth peripheral devices and also established a connection but when I am trying to build the apk I got "Task :react-native-bluetooth-serial:verifyReleaseResources FAILED" error and its open issue in git(https://github.com/rusel1989/react-native-bluetooth-serial/issues/102).

 

// in /android/build.gradle
        buildToolsVersion = "29.0.2"
        minSdkVersion = 28
        compileSdkVersion = 29
        targetSdkVersion = 29 

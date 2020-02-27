## react-native-video orkney fork

There are lots of libraries included in this fork for Mux to work with iOS, but the important modifications to the `exoplayer` and iOS `video player` are:

### Android

 - **build.gradle files**: added mux imports and dependencies
 - **android-exoplayer/src/main/java/com/brentvatne/exoplayer/ReactExoplayerView.java**: main mux integration into the exoplayer
 - **android-exoplayer/src/main/java/com/brentvatne/exoplayer/ReactExoplayerViewManager.java**: extension to receive the environment key via react-native props
 
### iOS

 - **ios/Video/RCTVideo.m**: main mux integration into the iOS video player
 - **ios/Video/RCTVideoManager.m**: extension to receive the environment key via react-native props

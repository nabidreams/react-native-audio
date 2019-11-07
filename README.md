# react-native-audio-recorder

## Getting started

`$ npm install react-native-audio-recorder --save`

### Mostly automatic installation

`$ react-native link react-native-audio-recorder`

### Manual installation

#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-audio-recorder` and add `AudioRecorder.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libAudioRecorder.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`

- Add `import nabidreams.AudioRecorderPackage;` to the imports at the top of the file
- Add `new AudioRecorderPackage()` to the list returned by the `getPackages()` method

2. Append the following lines to `android/settings.gradle`:
   ```
   include ':react-native-audio-recorder'
   project(':react-native-audio-recorder').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-audio-recorder/android')
   ```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
   ```
     compile project(':react-native-audio-recorder')
   ```

## Usage

```javascript
import AudioRecorder from 'react-native-audio-recorder';

// TODO: What to do with the module?
AudioRecorder;
```

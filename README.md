
# react-native-global-payments

## Getting started

`$ npm install react-native-global-payments --save`

### Mostly automatic installation

`$ react-native link react-native-global-payments`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-global-payments` and add `RNGlobalPayments.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNGlobalPayments.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNGlobalPaymentsPackage;` to the imports at the top of the file
  - Add `new RNGlobalPaymentsPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-global-payments'
  	project(':react-native-global-payments').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-global-payments/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-global-payments')
  	```

## Usage
```javascript
import RNGlobalPayments from 'react-native-global-payments';

// TODO: What to do with the module?
RNGlobalPayments;
```
  
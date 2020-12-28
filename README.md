# tollguru-poc

# Context and goal

This is a POC app using Mapbox sdk for reactnative. When the app is launched, a login screen is displayed with email and password fields which are mandatory. Enter any vaild email and any text as password and click on Login button. This will navigate to the Home screen. On first time launch of Home screen, a card with country selection will be displayed with the map loaded in the background.. The countries displayed are India, United States & United Kingdom. On selection of the country, the card will close and the view will zoom towards the selected country in the map. For example, if India is selected, view will zoom towards India in the map and map of India will be displayed. In the bottom, a card will be displayed with the following details of the selected country/region. Currency symbol, units of speed, distance and volume (kmph, kilometers, liters etc), timezone(s). The selected country and its details will be saved to the asyncstorage, so that upon 2nd launch, bu default the last selected country will be selected. There will be a drawer menu in the home screen. Drawer will displaye the email entered while logging in. There will be a Logout button clicking on which will navigate back to the Login screen. There will be a switch to toggle nightmode in the drawer menu.

## Main technologies used

- [React Native](https://github.com/facebook/react-native)

> A framework for building native apps with React.

- [Redux Toolkit](https://redux-toolkit.js.org/)

> Redux is a predictable state container for JavaScript apps.

- [React Native Paper](https://callstack.github.io/react-native-paper/)

> Cross Platform React Native UI Toolkit

- [Map Box](https://www.mapbox.com/)

> Maps and Location SDK

## Running the project


- [Install NodeJS](https://nodejs.org/en/) on your computer.

- Install react-native-cli globally on your computer
```
npm install react-native-cli --save
```
### IOS steps

- Install XCODE.
- Then from the root of the project run
```
npm install
```
> This will install all react native project dependencies.


- cd to the ios folder, then run.
```
pod install
```
> This will install all IOS dependencies.

- Go back to the root of the folder and run
```
npm run ios
```
> This will launch the app in the simulator.


### Android steps

- Launch a virtual android device [(through *Android Studio* for instance)](https://developer.android.com/studio/run/managing-avds.html#viewing)

> If you have never installed any android virtual device, [follow those instructions](https://developer.android.com/studio/run/managing-avds.html#createavd)

Then from the root of the project run
```
npm install
```
> This will install all react native project dependencies.

- Then, run the project in executing on your project folder:

```
npm run android
```
```

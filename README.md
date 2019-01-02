# Naked Camera App
**Problem**: Quicktime allows you to record the screen of a connected iOS device. If you want to record a video using your device as a USB webcam, you would be stuck with the UI that's present on the native iOS Camera app. A cleaner solution would be to download a webcam app, but those cost anywhere from 5 to 50 bucks. 

**Solution**: This is a dirt simple, UI-free camera app that utilizes the back camera of your device. No buttons or status bar - just pure video. 

Note that there's no orientation lock on the app currently, so you lock your preferred orientation in the *app.json* config as follows:

"orientation": "landscape"

or 

"orientation": "portrait"

Build the app as you would any normal Expo/React-Native app
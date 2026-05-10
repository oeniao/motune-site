# Motune

**Wrist gestures for music control while you move.**

Motune lets you control music playback from your Apple Watch with simple wrist gestures. It is designed for running, walking, gym workouts, and other moments when your iPhone is in your pocket, on an armband, or out of easy reach.

## What Motune Does

- Controls the current music playback on your iPhone.
- Recognizes wrist gestures on Apple Watch.
- Sends recognized gestures from Apple Watch to iPhone.
- Supports configurable gesture actions.
- Works without an account, cloud service, ads, or tracking.

Motune focuses on music playback control. It is not a social app, medical app, or fitness coaching service.

## Requirements

- iPhone running iOS 18 or later.
- Apple Watch running watchOS 11 or later.
- A paired Apple Watch connected to the iPhone.
- Motion and Fitness permission on Apple Watch.
- Health permission for the local workout session that keeps gesture recognition active during movement.

## How to Use

1. Install Motune on iPhone and Apple Watch.
2. Open your preferred music app and start playback.
3. Open Motune and turn on gesture control.
4. Keep Apple Watch on your wrist.
5. Use wrist gestures to control playback.

Default gesture mapping:

| Gesture | Default Action |
|---|---|
| Rotate wrist outward and return | Previous track |
| Rotate wrist inward and return | Next track |
| Turn palm upward and return | Play |
| Bend palm downward and return | Pause |

You can customize which music action each gesture performs in Settings.

## Notes on Recognition

Gesture recognition depends on how the watch is worn, arm movement, motion noise, and the current activity. Motune uses motion sensor data on the watch to classify gestures locally. If recognition is unstable, try making one clear gesture and returning your wrist to a relaxed position before the next gesture.

## Privacy Policy

Last updated: 2026-05-08

Motune is designed to minimize data collection.

### Data Collection

Motune does not collect personal data from this app.

Motune does not use:

- User accounts.
- Advertising SDKs.
- Third-party analytics SDKs.
- Cross-app tracking.
- A backend server for user profiles.

### Motion Sensor Data

Apple Watch motion sensor data is processed locally on the device for gesture recognition. The app does not upload motion sensor data automatically.

If you explicitly use the gesture sample tool, motion samples may be saved locally on your device for debugging or model improvement. These samples are not uploaded automatically.

### Health Permission and Health Data

Motune may request Health permission only to start a local workout session on Apple Watch. This allows gesture recognition to continue during workouts, while another Watch app is in the foreground, and while iPhone receives gesture control events in the background or on the lock screen.

Motune does not read heart rate, steps, calories, workout history, activity rings, or other health records. Motune does not store, upload, sell, or share HealthKit data with third parties.

The workout session is used as a system runtime mechanism for continuous gesture recognition and real-time Watch-to-iPhone control. Motune is not a medical, fitness coaching, or health analysis app.

### Music Playback Data

Motune controls current music playback. It does not upload your listening history, playlists, library, or account information. Any currently playing information shown in the app is used locally for display and control.

### Data Sharing

Motune does not sell, rent, or share personal data with third parties.

### Data Retention and Deletion

Motune has no remote account database. Local settings and optional local gesture samples remain on your device. You can remove local app data by deleting the app from iPhone and Apple Watch.

### Contact

For support or privacy questions, contact: [motune.app@gmail.com](mailto:motune.app@gmail.com).

## Support

If gestures are not controlling music:

1. Confirm music is already playing or paused in a music app.
2. Confirm Motune is installed on both iPhone and Apple Watch.
3. Confirm gesture control is enabled.
4. Keep iPhone and Apple Watch nearby and connected.
5. Open Motune on Apple Watch once to start gesture recognition.

## Disclaimer

Motune is a convenience tool for music playback control. It is not intended for medical diagnosis, health treatment, emergency use, or safety-critical situations.

# flutterdeployment

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

### generate playstore key

```
keytool -genkey -v -keystore $PATH/key.jks -keyalg RSA -keysize 2048 -validity 10000 -alias key
# Windows
certutil -encode $PATH/key.jks tmp.b64 && findstr /v /c:- tmp.b64 && del tmp.b64
# Linux
base64 key.jks
```

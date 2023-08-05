### Flutter tips
**startup time measuring :**
```text
flutter run --trace-startup --profile
```
**show performance overlay**
```dart
void main() {
  return runApp(
    GetMaterialApp(showPerformanceOverlay: true),
  );
}
```
**Launcher icon set in flutter**
```yaml
flutter_launcher_icons: ^0.13.1
```
```yaml
flutter_launcher_icons:
  android: "launcher_icon"
  image_path: "assets/logo/logo.png"
```
```text
flutter pub get
```
```text
flutter pub run flutter_launcher_icons 
```
**Splash screen icon set in flutter**
```yaml
flutter_native_splash: ^2.3.1
```
```yaml
flutter_native_splash:
  color: "#FFFFFF"
  image: "assets/logo/launcher_icon.png"
```
```text
flutter pub get
```
```text
dart run flutter_native_splash:create
```
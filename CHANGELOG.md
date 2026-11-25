## 2.3.0

* Support Swift Package Manager on iOS: the plugin is now Swift only, in `ios/quitter/Sources/quitter`, with a `Package.swift` that depends on Flutter's `FlutterFramework` package; CocoaPods builds keep working
* Bump min Flutter SDK to 3.44.0, the first release with the `FlutterFramework` package

## 2.2.0

* Align the Android and iOS build setup with the Flutter 3.47 plugin template: namespace, compileSdk 36, minSdk 24, Java 17, AGP 9.1.0 in the buildscript, mavenCentral() instead of jcenter(), and iOS 15.0
* Regenerate the example app with Flutter 3.47.9
* Drop the `package` attribute from the plugin manifest, which the namespace replaces

## 2.1.0

* Bump minSdkVersion to 21, compileSdkVersion to dynamic value, and min Flutter SDK to 3.38.0

## 2.0.0-nullsafety

* Migrate to null safety.

## 1.0.0

* Initial release.

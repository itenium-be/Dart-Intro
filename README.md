Dart
====

Installation
------------

```ps1
choco install -y dart-sdk
dart pub global activate devtools
dart pub global activate webdev

# ATTN:
# Add manually to path:
# C:\Users\%username%\AppData\Local\Pub\Cache\bin

dart pub get
webdev serve --debug --auto=refresh
webdev build
```

Visual Studio Code extensions: `dart-code.dart-code` & `dart-code.flutter`

CLI
---

```ps1
cd web\Examples\01-Basics
dart run .\Showcase.dart
```

Cheat Sheets
------------

Try the [DartPad](https://dartpad.dev/?null_safety=true) playground.

- [Cheat Sheet](Dart-Cheatsheet.pdf) (4 pages)
- [Temidtech Cheat Sheet](https://github.com/Temidtech/dart-cheat-sheet) (11 pages)
- [Official Cheat Sheet](https://dart.dev/codelabs/dart-cheatsheet) (26 pages)

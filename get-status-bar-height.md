## Sample code AppBar

https://stackoverflow.com/questions/49441187/how-to-change-status-bar-and-app-bar-color-in-flutter

```dart
appBar: PreferredSize(
  preferredSize: Size.fromHeight(0),
  child: AppBar(
    backgroundColor: Colors.white,
  ),
),
```

## Sample code using context

https://flutter-examples.com/get-status-bar-height-in-flutter/

```dart
double statusBarHeight = MediaQuery.of(context).padding.top;
```
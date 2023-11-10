# Flutter Opacity Widget

https://api.flutter.dev/flutter/widgets/Opacity-class.html

![image](https://github.com/luiscoco/flutter_opacity_widget/assets/32194879/a2d38d0e-077e-4f5a-b748-0f09edaaca69)

```dart
import 'package:flutter/material.dart';

void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          title: Text('Opacity Widget Sample'),
        ),
        body: Center(
          child: Opacity(
            opacity: 0.5, // Set the opacity value between 0.0 and 1.0
            child: Container(
              width: 200,
              height: 200,
              color: Colors.blue,
              child: Center(
                child: Text(
                  'Hello Flutter!',
                  style: TextStyle(color: Colors.white),
                ),
              ),
            ),
          ),
        ),
      ),
    );
  }
}
```

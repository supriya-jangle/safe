import 'package:flutter/material.dart';
void main() => runApp(MyApp());
class MyApp extends StatelessWidget {
 @override
 Widget build(BuildContext context) {
 return MaterialApp(
 home: SafeAreaDemo(),
 );
 }
}
class SafeAreaDemo extends StatelessWidget {
 @override
 Widget build(BuildContext context) {
 return Scaffold(
 body: SafeArea( // ⬅️ Wrap your content inside SafeArea
 child: Center(
 child: Text(
 'This text is inside SafeArea!',
 style: TextStyle(fontSize: 20),
 ),
 ),
 ),
 );
 }
}

# stack
flutter
import 'package:flutter/material.dart';

void main() => runApp(MyApp());

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          title: Text("Stack"),
        ),
        body: Stack(
          children: <Widget>[
            Column(
              children: <Widget>[
                Flexible(
                  flex: 1,
                  child: Row(
                    children: <Widget>[
                      Flexible(
                        flex: 1,
                        child: Container(
                          color: Colors.white38,
                        ),
                      ),
                      Flexible(
                        flex: 1,
                        child: Container(
                          color: Colors.lightBlue,
                        ),
                      )
                    ],
                  ),
                ),
                Flexible(
                  flex: 1,
                  child: Row(
                    children: <Widget>[
                      Flexible(
                        flex: 1,
                        child: Container(
                          color: Colors.blueGrey,
                        ),
                      ),
                      Flexible(
                        flex: 1,
                        child: Container(
                          color: Colors.redAccent,
                        ),
                      )
                    ],
                  ),
                )
              ],
            ),
            ListView(
              children: <Widget>[
                Column(
                  children: <Widget>[
                    Text(
                      "Lapisan tengah stack",
                      style: TextStyle(fontSize: 30),
                    ),
                    Text(
                      "Lapisan tengah stack",
                      style: TextStyle(fontSize: 30),
                    ),
                    Text(
                      "Lapisan tengah stack",
                      style: TextStyle(fontSize: 30),
                    ),
                    Text(
                      "Lapisan tengah stack",
                      style: TextStyle(fontSize: 30),
                    ),
                    Text(
                      "Lapisan tengah stack",
                      style: TextStyle(fontSize: 30),
                    ),
                    Text(
                      "Lapisan tengah stack",
                      style: TextStyle(fontSize: 30),
                    ),
                    Text(
                      "Lapisan tengah stack",
                      style: TextStyle(fontSize: 30),
                    ),
                    Text(
                      "Lapisan tengah stack",
                      style: TextStyle(fontSize: 30),
                    ),
                    Text(
                      "Lapisan tengah stack",
                      style: TextStyle(fontSize: 30),
                    ),
                    Text(
                      "Lapisan tengah stack",
                      style: TextStyle(fontSize: 30),
                    ),
                    Text(
                      "Lapisan tengah stack",
                      style: TextStyle(fontSize: 30),
                    ),
                    Text(
                      "Lapisan tengah stack",
                      style: TextStyle(fontSize: 30),
                    ),
                    Text(
                      "Lapisan tengah stack",
                      style: TextStyle(fontSize: 30),
                    ),
                    Text(
                      "Lapisan tengah stack",
                      style: TextStyle(fontSize: 30),
                    ),
                    Text(
                      "Lapisan tengah stack",
                      style: TextStyle(fontSize: 30),
                    ),
                    Text(
                      "Lapisan tengah stack",
                      style: TextStyle(fontSize: 30),
                    ),
                  ],
                )
              ],
            ),
            Align(
              alignment: Alignment(0, 0.7),
                child: RaisedButton(
              child: Text("TOMBOL"),
              color: Colors.deepOrange,
              onPressed: () {},
            ))
          ],
        ),
      ),
    );
  }
}

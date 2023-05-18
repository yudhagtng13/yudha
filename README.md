import 'package:flutter/material.dart';

void main() {
  runApp(MaterialApp(
    debugShowCheckedModeBanner: false,
    home: Scaffold(
      floatingActionButton: FloatingActionButton(
        onPressed: () {},
        child: const Icon(Icons.download),
        ),
        body: Padding(
          padding: const EdgeInsets.all(8.0),
          child: Column(
            children: [
              const TextField(
                decoration: InputDecoration(labelText: "Username"),
                ),
              const TextField(
                obscureText: true,
                decoration: InputDecoration(labelText: "password"),),
              const SizedBox(
                height: 10.0,
              ),
              ElevatedButton(onPressed: () {

              }, child: const Text("Login"))
            ],
          ),
        ),
        appBar: AppBar(
          title: const Text("Catering yudha"),
        )),
  ));
}


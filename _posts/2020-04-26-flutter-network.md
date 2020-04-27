---
layout: post
title:  "Restful API with Flutter"
date:   2020-04-24
excerpt: "Calling and parsing RESTful API with native flutter library"
tag:
- Flutter 
- Restful
- example
- dark
- startup
comments: true
---

# What is Flutter 

**Flutter** is a multi cross-platform tool that lets us build iOS, Android, and Web apps using just one programming language: Dart. It's a framework backed by Google.  

You can find a lot of help, examples, cookbook recipes from the [official page](https://flutter.dev) and the [awesome Flutter community](https://flutter.dev/community) 

## Calling the RestFul API and parse the json response.

The main aim is to show you how to call a Restful API using native flutter network library, well let's try out. To achieve we're using the NASA API, and for what you need to subscribe to the service and it is totally free. Also, I going to provide some examples of responses in JSON format for our test. Please [subscribe to the service](https://api.nasa.gov) to get your own key.

* https://api.nasa.gov/EPIC/api/natural/images?api_key=DEMO_KEY 
* https://api.nasa.gov/EPIC/api/natural/date/2019-05-30?api_key=DEMO_KEY 
* https://api.nasa.gov/EPIC/api/natural/all?api_key=DEMO_KEY 
* https://api.nasa.gov/EPIC/archive/natural/2019/05/30/png/epic_1b_20190530011359.png?api_key=DEMO_KEY


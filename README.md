
## Lightyear front-end test task

### Flutter

First things first, you'll need to set up and get familiar a bit with Flutter. We suggest to use the official guide over at https://docs.flutter.dev/get-started/install

Flutter is very much like React so if you have a background in web and React, picking up Flutter should not be an issue. If you have absolutely no experience with Flutter it would be wise to go through a basic code example, for example: https://docs.flutter.dev/get-started/codelab

### Requirements

The goal of the task is to create a small flutter application that lists stock news. The design requirements can be seen in the screenshot below:

![Stock News Requirements](/requirements/stock_news.png?raw=true)

- The news data is included in the project in the file `./data/news.json`
- The instrument data can be requested from our public endpoint: https://golightyear.com/api/v1/instrument
- The brand colors that we use are included in the file `./lib/colors.dart`
<!-- 
This README describes the package. If you publish this package to pub.dev,
this README's contents appear on the landing page for your package.

For information about how to write a good package README, see the guide for
[writing package pages](https://dart.dev/guides/libraries/writing-package-pages). 

For general information about developing packages, see the Dart guide for
[creating packages](https://dart.dev/guides/libraries/create-library-packages)
and the Flutter guide for
[developing packages and plugins](https://flutter.dev/developing-packages). 
-->

This package contains utilities methods

## Features

This package contains methods for converting date to string, string to dates, random methods to get list of data for listview when prototyping

## Getting started

Use the class Utils with static methods like convertDateToStr, 
convertStrToDate and getRandomListViewData


## Usage

```dart
const String dateConverted = Utils.convertDateToStr(dateObject);
const Date dateParsed = Utils.convertStrToDate(stringLikeDate);
const List<Proverb> dataList = Utils.getRandomListViewdata(();
```

## Additional information

The method getRandomListViewdata will return random list of proverbs, in a form of list of type Proverb  
"iwaju_utils"

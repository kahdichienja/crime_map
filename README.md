# Crime Map

### Background

Develop an application that visualizes crime loations:

* Areas with less than 5 crime reports are marked with a green marker ,those with between 5 and 20 are marked with a yellow marker while those above 20 reports are marked with a red marker.

* Areas within 500 meters radius are categorized as one crime location and have a circle marking the areas with respect to number of crime reported.

* Adding a new area that is within 500 meter radius of an existing location will just update the crime report number else a new crime spot will be created.

* Users can upload images of the crime spots.


## Tech-stack

* Tech-stack
    * [Flutter](http://flutter.dev/) - a cross-platform, framework for building mobile applications.
    * [Dart](http://dart.dev/) - client-optimized language for fast apps on any platform.
    * [Provider](https://pub.dev/packages/provider) - A wrapper around InheritedWidget to make them easier to use and more reusable.(State management)
    * [Google Sign in](https://pub.dev/packages/google_sign_in) - A plugin to access Google Sign in.
    * [Geocoding](https://pub.dev/packages/geocoding) - A Flutter Geocoding plugin which provides easy geocoding and reverse-geocoding features.
    * [Google Places](https://pub.dev/packages/google_place) - A new Flutter package for handle google place api that place search and details and photos and autocomplete and query autocomplete requests
    * [Cloud Firestore](https://pub.dev/packages/cloud_firestore) - Flutter plugin for Cloud Firestore, a cloud-hosted, noSQL database with live synchronization and offline support on Android and iOS.
    * [Firebase Storage](https://pub.dev/packages/firebase_storage) - Flutter plugin for Firebase Cloud Storage, a powerful, simple, and cost-effective object storage service for Android and iOS.
    

* Architecture
    * Clean Architecture

## Dependencies

All the dependencies (external libraries) are defined in the single place - `pubspec.yaml` file. This approach allows to easily manage dependencies and use the same dependency version across all modules.

## Screenshots

The screenshot below shows the working application:

|<image src="screenshots/1.jpg"> | <image src="screenshots/2.jpg"> | <image src="screenshots/3.jpg">| <image src="screenshots/4.jpg">|
|:---:|:---:|:---:|:---:|
|LogIn|Map Screen|Add Crime|Location Images|




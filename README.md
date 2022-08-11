# GoPlaces

GoPlaces is a companion app for tourists new to a city. The app gets the location of your device and provides suggestions of places of touristic interests nearest you.

## Getting Started

On downloading the app, you are requested to sign in using your Google account. On sign-in, you are requested to enable location permission for the app, else th itenarary function and guidance function will not work.

## Features of the app

Clicking on the marker denoting any place of interest opens a pop up window.  
Here at the top, you are shown a slideshow in images of the place.  
Below this, You get the star rating on the left and like button on the right.  
Next, you have a scrollable information about the place.

### Rating

In this application you can give the touristic place a star based rating of your choice. You have to drag across the stars to submit your rating.  
The star rating displayed is an average of all the ratings given by various users of the app.

You also can like the place.  
The number of likes is updated for all users

### My Places/Visit Later

You can add the places of interest in your My Places list using the Visit Later option. This list data is stored with your Google account. This enables you to have your personal list on any device as long as you login with your account.

### Lets Go

The Lets Go... option gives you a line giving directions from your current location to the selected destination

### Make a trip for me

Another exiting feature of this app is that it will give you a custom itenarary for a city tour. The order is determined by the nearest point of interest from your current loaction and subsequent nearest locations.

## To run g.dart file creation

WARNING : Use these commnads only while building the app from the source code in this repository.  
You should have flutter installed in your device.

```sh
flutter pub get
flutter pub run build_runner build --delete-conflicting-outputs
flutter pub run flutter_launcher_icons:main
```

## TODOs

- Add audio guide


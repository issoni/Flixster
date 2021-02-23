# Flixster

Flixster is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).
---
## Flixster Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [ ] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthrough GIF

<img src="http://g.recordit.co/xHh7XnkAH2.gif" width=250><br>

### Notes
* I had an error with af_setImage command even after importing AlamofireImage but I copy pasted again and it worked.
* At the end, my collection view looked bunched together but I set the estimated size to none and it became normal.  

## Flixster Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [ ] (1pt) Run your app on a real device.

### App Walkthrough GIF

<img src="http://g.recordit.co/dB52B2BWQh.gif" width=250><br>

### Notes

* I had some trouble setting up the CocoaPods for the posters. The command provided to install CocoaPods couldn't work on my end so I ended up using a different command: "sudo gem install cocoapods -v 1.7.5".

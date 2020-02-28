#  Cocoa Design Patterns Project

1. Objective Challenge - Pair off, and with a peer, each choose a design pattern and think of an instance you’ve used it code you’ve written or have seen it used in UIKit.

I am choosing Extensions and Delegation Patterns. One example of a time that I used both in my code is on my "MyMovies" project. I used extensions on my "MyMoviesTableViewController" for an NSFetchedResultsControllerDelegate as well "MyMoviesTableViewCellDelegate". I used the delegate pattern with my "MyMoviesTableViewCell" to inform the view controller that the "Watched" button was tapped and toggle a bool property of my "Movie" Object, which would update the buttons title to say "Watched" or "Unwatched".

GitHub Link: https://github.com/maybemichael/ios-sprint-my-movies

2.  Objective Challenge - Look through the documentation and find at least one UIKit class that uses the singleton pattern.

UIApplication uses the singleton pattern.

Developer Documentation Link: https://developer.apple.com/documentation/uikit/uiapplication

3. Objective Challenge - Think about a time we’ve used the facade pattern before. Are there places that we could have used it to write better code but didn’t? Discuss with a peer.

We have essentially been using the Facade Pattern this entire time, a good example of this is making our model controllers or api controllers with all the CRUD methods which we then initialize in our view controller for very simple implementation of much more complicated logic.

4. Objective Challenge - Write code to post a notification when a button is tapped indicating a bell has rung. In another class, sign up to be notified when this notification is posted, and make sure it works.

Added notification and observer to "Reading List" project.

GitHub Link: https://github.com/maybemichael/ios-reading-list

5.  Objective Challenge - Add support for state restoration to another app you’ve built.

Added support for state restoration in my 1st build week project "CountdownApp"

GitHub Link: https://github.com/maybemichael/Unit1-Build-Week-Countdown-App

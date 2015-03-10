# Authentication

## Description
This is a simple example of an authentication system built from scratch.

This was also an exercise in installing, creating, and running a Rails app on older versions of Ruby (1.9.3-p551) and Rails (3.2.16).

## Issues
Even though I generated a `welcome` controller and changed the root to go to `welcome#index`, for some reason Rails wouldn't redirect properly. Therefore, to see the welcome page, the url should be "http://localhost:3000/welcome/index".

## Contributors
This app was built by following the instructions in [RailsCasts #250](http://railscasts.com/episodes/250-authentication-from-scratch-revised).

I was able to install old versions of Ruby and Rails by loosely following the instructions [here](http://stackoverflow.com/questions/8877772/how-do-you-use-multiple-rails-versions-with-rbenv).

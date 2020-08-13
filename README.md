## A smart Assistant, developed in Rust


### Goal
The goal is to provide a smart assistant that can do the basics of the Google Assistant.

The following functionality should be provided:
- Setting/Deleting Timer
- Play Music via Spotify
- Current time/date
- Current weather
- basic search with duckduckgo



### Architecture
The basic architecture should be one server maniging all the business logic and providing an REST interface, storing everything in a MongoDB.
Multiple clients with microphone and speaker, processing the language of the user and calling the servers REST interface
A Web UI to configure the server and clients

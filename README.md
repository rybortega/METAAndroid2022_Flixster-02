# Project 3 - *Flixster Part 1*

**Flixster** shows the latest movies currently playing in theaters. The app utilizes the Movie Database API to display images and basic information about these movies to the user.

Time spent: **21** hours spent in total

## Features

The following **required** functionality is completed:

- [X] (6pts) **Make a request to [The Movie Database API's `now_playing`](https://developers.themoviedb.org/3/movies/get-now-playing) endpoint to get a list of current movies**
- [X] (6pts) **Parse through JSON data and implement a RecyclerView to display all movies**
- [X] (6pts) **Use Glide to load and display movie poster images**

The following **stretch** features are implemented:

- [ ] Improve and customize the user interface through styling and coloring
- [X] Implement orientation responsivity
  - App should neatly arrange data in both landscape and portrait mode
- [X] Implement Glide to display placeholder graphics during loading
  - Note: this feature is difficult to capture in a GIF without throttling internet speeds.  Instead, include an additional screencap of your Glide code implementing the feature.  (<10 lines of code)

The following **additional** features are implemented:

* [x] Added 'Read More...' button and YouTube play button

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://github.com/sophiatxiang/Flixster/blob/master/flixster_portrait_bonus_1.gif' width='' alt='Video Walkthrough' />
<img src='https://github.com/sophiatxiang/Flixster/blob/master/flixster_landscape_bonus.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIFs created with [Kap](https://getkap.co/).

## Notes

Describe any challenges encountered while building the app:
- Initially a bit confused on how to access/use APIs and YouTubePlayerView
- Didn't know what view binding was- did a good amount of research to understand

## Open-source libraries used

- [Android Async HTTP](https://github.com/loopj/android-async-http) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright [2021] [Sophia Xiang]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

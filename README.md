# Twiter Client
 Twitter Client is an android app that allows you to view your Twitter timeline and post new Tweet.
Submitted by: **Smath Cadet**

Time spent: **48** hours spent in total

## User Stories

The following required functionality are completed:

* [x] User can sign in to Twitter using OAuth login
* [x] User can view the tweets from their home timeline.
* [x] User should be displayed the username, name, and body for each tweet
* [x] User should be displayed the relative timestamp for each tweet "8m", "7h"
* [x] User can view more tweets as they scroll with infinite pagination
* [x] User can compose a new tweet
* [x] User can click a "Compose" icon in the AppBar on the top right
* [x] User can then enter a new tweet and post this to twitter
* [x] User is taken back to home timeline with new tweet visible in timeline
Newly created tweet should be manually inserted into the timeline and not rely on a full refresh

The following optional functionality are completed:

* [x] While composing a tweet, user can see a character counter with characters remaining for tweet out of 140.
* [x] Links in tweets are clickable and will launch the web browser.
* [x] User can refresh tweets timeline by pulling down to refresh.
* [x] User can open the twitter app offline and see last loaded tweets
* [x] Tweets are persisted into sqlite and can be displayed from the local DB.
* [x] User can tap a tweet to display a "detailed" view of that tweet  
* [x] Compose activity is replaced with a modal overlay 
* [x]  Leverage RecyclerView as a replacement for the ListView and ArrayAdapter for all lists of tweets.
* [x] Move the "Compose" action to a FloatingActionButton instead of on the AppBar.
* [x] On the Twitter timeline, leverage the CoordinatorLayout to apply scrolling behavior that hides / shows the toolbar.
* [x] Replace Picasso with Glide for more efficient image rendering. 


## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://i.imgur.com/MRI46GW.gif' width="300" />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

dapt or bind elements to the listview or, in my case, to the recyclerview.



## License

    Copyright 2018 Smath Cadet

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

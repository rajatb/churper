Churper - A twitter Client
=========================

Time spent:  24 hours spent in total

Completed User Stories: 

- [x] User can sign in using OAuth login flow.
- [x] User can view last 20 tweets from their home timeline
- [x] The current signed in user will be persisted across restarts 
- [x] In the home timeline, user can view tweet with the user profile picture, username, tweet text, and timestamp.  In other words, design the custom cell with the proper Auto Layout settings.  You will also need to augment the model classes.
- [x] User can pull to refresh 
- [x] User can compose a new tweet by tapping on a compose button.
- [x] User can tap on a tweet to view it, with controls to retweet, favorite, and reply 


Optional
- [x] When composing, you should have a countdown in the upper right for the tweet limit.
- [x] After creating a new tweet, a user should be able to view it in the timeline immediately without refetching the timeline from the network.
- [x] Retweeting and favoriting should increment the retweet and favorite count.
- [x] User should be able to unretweet and unfavorite and should decrement the retweet and favorite count.
- [x] Replies should be prefixed with the username and the reply_id should be set when posting the tweet,
- [x] User can load more tweets once they reach the bottom of the feed using infinite loading similar to the actual Twitter client.

Cocoa Pods Used: 

AFNetworking
BDBOAuth1Manager
Mantle
SVProgressHUD
MHPrettyDate  - Awesome for dates!! 

Description of the project:

Project Twitter APIs to login using Oauth. After login it calls the APIs to get the data and do basic twitter functionality of creating a tweet, retweet, reply and favorite.  

Gif Image


![Alt Text](Twitter%20Client.gif)

CodePath HW1 Rotten Tomatoes Due: June 10. 2014 10pm


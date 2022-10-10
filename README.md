# ~ Facebook filters ~ #

For use in uBlock Origin.
<br />
<br />
Filters for blocking Sponsored*, Suggested posts, Paid Partnership posts and miscellaneous items in Facebook.

Works with most languages. 

__Notes:__<br />
- Most of the rules do not use keywords to find the items, instead they look for a particular structure pattern.

__(*)Sponsored posts__

Due to FB using HTML's _shadow-root_ facility, it is not so easy to create a generic rule for filtering out News Feed sponsored posts for all users. This [script](https://github.com/zbluebugz/facebook-clean-my-feeds/tree/main/uBO-sponsored-filter), will create a customised rule that most likely works with your computer setup.


### List of filters ###

These rules are in __live__ mode.
<br />
i.e. the rules hide the items that meets the rule's criteria.
<br />
<br />
#### fb-suggested.txt : ####
- Suggested posts (all types of suggested posts)
  - News feed
  - Groups feed
<br />

#### fb-sponsored-basic-except-newsfeed-sponsored.txt ####
- Sponsored posts in Groups feed 
- Sponsored posts in Videos feed
- Sponsored posts in Marketplace feed
- Sponsored posts in Search feed
- Paid partnership in News feed
- Sponsored * paid for by ... in News feed
- Sponsored item in News feed's aside column
<br />



#### fb-miscellaneous.txt : ####
Following applies to the News Feed:
- Friends may know
- Stories | Reels | Rooms
- Reel/Short videos (collection)
- Reel posts
- Information boxes
  - Climate info
  - Coronavirus info
  - Subscribe

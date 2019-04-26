
# brennan web app noiseless why ?

brennan b2 music & radio media player is a great bit of kit and relatively easy to modify, the web app is i understand no longer being developed, the web app final release continually polls the b2 unit every half a second for sync & status updates, this polling creates problems;

-  uploading new music via a network
-  mutiple devices accessing the B2
-  radio drop outs
-  performance and browser memory leaks
-  network bandwidth overhead
-  internet issues for other users

Other small UI issues may need some attention, which are discussed below.

# brennan web app noiseless release

noiseless web app release is a branch of the original brennan B2 web app UI based on the last release web app [20|03|2019] to focus on just playing music & radio without 'noise' with excellence

# noiseless release roadmap

web app will be maintained here together with any UI improvements major or minor updates to the original code base.

major changes include; removal of constant polling of the B2, scrolling graphs and other continued status updates this will remove the problems associated with mutiple devices accessing the B2, music file uploads, radio drop outs and performance and browser memory leak issues created from constant polling to minor fixes which include; removal of hash in the URL and the requirment of an internet connection and a number of other minor performance improvements

UI controls have been tweeked together with improve mobile web UI modal & improve responsive design

## noiseless mobile update

the current official last brennan B2 update offered an experimental mobile only UI, the UI navigaton and controls seem to work well, however, from a quick review, the underlying code is not in a happy place, it seems to want to be event driven with passive constant polling of the B2 resulting in the UI not being able to control the B2 ( not possible to play music or radio ) !

it is after all an experiment, and not a high priority, however, probably for noiseless version two, time permitting I plan to modify and rewrite parts of this code base to fix this experimental mobile UI to a functional noiseless version  
 
## noiseless current version web app maintenance release 

version one is currently being developed ready for final version release, still to do; implement version control & HTML commments per file and finally, clean up, remove commented out lines & delete all old redundant code and redundant files

## noiseless has two branches, current & dev

- current release index.html     -> v1.0.0
- dev ... release index-dev.html -> v1.0.1 

new official experimental UI is being developed by brennan ... https://github.com/geometryzen/brennan-app 

if you are a b2 brennan owner and you stumble onto this page, and you prefer a simpler stable maintained noiseless version of this web app and want to contribute please get in touch

###### * please note, all web app upgrades & updates are implemented at your own risk

project341
==========

#Subsonic Android App

Kirk Xenos Smith, Harish Kumar Lall, Javier Ignacio Camino
Allendesalazar

##Project: 
A mobile app for the Subsonic media server system

###Features:

1.  Playlist and directory listing
2.  Audio streaming
3.  Video streaming
4.  Offline caching
5.  File uploading

###Reason: 
We want to be able to stream media from our computer to our
smartphones and tablets. Initially subsonic/android, later other
combinations. We would also like to be able to upload media from our
phone to our computer for archival.


###Existing Subsonic mobile apps:

####1.  [Android
    app](https://play.google.com/store/apps/details?id=net.sourceforge.subsonic.androidapp&feature=search_result#?t=W251bGwsMSwyLDEsIm5ldC5zb3VyY2Vmb3JnZS5zdWJzb25pYy5hbmRyb2lkYXBwIl0.)

1.  Video streaming requires the use of Flash on any device, which is no
    longer available from Adobe
2.  Doesn’t allow media uploading
3.  Not open source


####1.  [Best third party iOS app](http://isubapp.com/)

1.  Costs \$4.99.
2.  Doesn’t allow media uploading
3.  Not open source

###Technical information:

Subsonic has an [extensive API](http://www.subsonic.org/pages/api.jsp).
It exposes HTTP live streams that are compatible with iOS (3.0+) and
Android (3.0 or 4.0 +)[[1]](#ftnt1)[[2]](#ftnt2). However, it does
not allow file uploading, and we would have to propose this change to
the community. There is a potential security risk involved with
uploading files through the API, so they might refuse to accept our
addition. We could either fork or abandon this feature if this happens.

We might use a cross platform framework such as
[PhoneGap](http://phonegap.com/), [Cordova](http://cordova.apache.org/),
or the [Titanium
Framework](http://www.appcelerator.com/platform/titanium-platform/) so
that we can easily target multiple platforms. We will use some form of
version control, probably git, and maybe basecamp to coordinate the
project. Or perhaps a google doc.

###Schedule of development:

####Weeks 1-3:

1.  Select development framework
2.  Design mockups
3.  Start prototype app

####Weeks 4-7:

1.  Finish up prototype app
2.  Improve app UI/UX
3.  Create a patch for Subsonic API file upload and submit to project

####Weeks 8-10:

1.  Polish app
2.  Test on multiple devices
3.  Release on App Store/Market
4.  Create website

###Future: 
Integrate with other media servers
([Ampache](https://github.com/ampache/ampache/), [Orb
Caster](http://www.orb.com/en/updated-orb-caster/testfeatures.html),
[Sockso](http://pu-gh.com/), etc...) and other mobile platforms.

Why 341: The speed of sound is 340m/s. Our app is therefore supersonic
:)

* * * * *

[[1]](#ftnt_ref1) [http://developer.android.com/about/versions/android-3.0-highlights.html](http://developer.android.com/about/versions/android-3.0-highlights.html)

[[2]](#ftnt_ref2) [http://en.wikipedia.org/wiki/HTTP\_Live\_Streaming](http://en.wikipedia.org/wiki/HTTP_Live_Streaming)

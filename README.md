# JiocinemaDownloader
Download both DRM and DRM free videos from jiocinema

# Steps
1. Install required dependencies
2. edit the field 'accesstoken' in python script and copy your own value like this:
![SCR-20230819-jqs](https://github.com/swappyison/JiocinemaDownloader/assets/88504971/310d8f8c-2d28-4c13-946c-6c594fc67914)

here i went to network tab under developer tools and typed method:POST. I selected the url with key-jiocinema and scrolled down to see the access token value. I then copied it by right clicking on it.


3.run python script in terminal: python3 jiodownloader.py
4. Simply copy and paste the jiocinema url
5. Choose which format to download
6. enjoy!

NOTE: access token gets expired after every 15 minutes so you need to edit the python file for a fresh token everytime.

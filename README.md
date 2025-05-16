Here's a little adblock list to remove the "previous" and "next" buttons on mobile web version of YouTube!

The buttons in this list are overlayed on a video next to the "play/pause" button when the video is tapped or paused.  Double-tapping on the left or right side of a video also seeks 10 seconds back and forward, but if you tap where one of these navigation buttons appear, you'll navigate to a different video instead.  I personally never use these buttons, so I created this adblock list to stop accidentially tapping them.

Here's a before and after look at what this adblock list does:

|Before|After|
|---|---|
|![image](https://github.com/user-attachments/assets/10e6ad71-76e8-4973-b373-3338209b1a2b)|![image](https://github.com/user-attachments/assets/5edc2cc7-ae2c-46ba-a64d-dd37d07d7c2c)|

To add this list to uBlock Origin, open uBlock's settings page and click on the "Filter lists" tab.  At the bottom of the page, expand the "Custom" tree and check the "Import..." box.  Then, add this URL to the textarea that appears:

    https://raw.githubusercontent.com/synthead/youtube-mobile-remove-navigation-buttons/main/youtube-mobile-remove-navigation-buttons.txt

Click the "Apply changes" button on the top-left of the page, and you're done!  This URL reflects the latest commit to this list, so your ad blocker will auto-update accordingly.

This list can be used on all the other common ad blockers too, but they have their own settings page that I won't get into detail about.  If you don't know about [uBlock Origin](https://ublockorigin.com), you might consider switching to it as it's fast, light, and is [GPL-licensed](https://github.com/gorhill/uBlock/blob/master/LICENSE.txt).

Enjoy!

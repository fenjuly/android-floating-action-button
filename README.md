FloatingActionButton
====================
This project is forked from [futuresimple/FloatingActionButton](https://github.com/futuresimple/android-floating-action-button).

And I add some special characteristics which I "stoled" from this project[makovkastar/FloatingActionButton](https://github.com/makovkastar/FloatingActionButton)

Before I did this, I opened an [issue](https://github.com/futuresimple/android-floating-action-button/issues/27) to ask "is there any plan to add ScrollListener?". Unfortunately, the author didn't have intention to do so.This's the reason I did the job, just for my personal use~

New Feature
===
 When srolled down , the FloatingActionButton or FloatingActionsMenu would be hiden.


ScreenShot
===
![Imgur](http://i.imgur.com/Q2TBeKc.gif)

Usage
===
	ListView listView = (ListView) root.findViewById(android.R.id.list);
    FloatingActionsMenu fam = (FloatingActionsMenu)root.findViewById(R.id.multiple_actions);
    fam.attachToListView(listView);
As for more usage you should go to the original project [futuresimple/FloatingActionButton](https://github.com/futuresimple/android-floating-action-button).

Other
===
```all rights unreserved,I just play a role as Porter, if the original authors are disgruntled with my job, please let me know , i'll delete this repo~```


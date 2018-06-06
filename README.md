# Compact Sidebar Bookmarks for Firefox Quantum

With every new redesign of Firefox, the sidebar requires more and more space.
Back in the old days of Firefox 1&ndash;2, the sidebar compactly showed only Unsorted Bookmarks. 
First, Firefox 3 changed the default list of showed groups.
Next, somewhere along the way, spaces between bookmarks got bigger.
Nonetheless, it was possible to revert these changes with extensions.
But now, with the arrival of Firefox Quantum, extensions can no longer modify the sidebar.

This tweak is trying to recreate the old compact appearance of bookmarks in the sidebar with the use of custom styles. Note, however, that this technique has its limitations. 

**Status:** completed (maintained)  
**Tested on:** Windows 7/10, Firefox 59+


## Instructions

Copy `userChrome.css` into `<firefox-profile>\chrome\`.  
For more detailed instructions on how to use custom styles in Firefox see [Aris-t2/CustomCSSforFx](https://github.com/Aris-t2/CustomCSSforFx).


## Screenshots

* Firefox 4 + Basic Bookmarks extension
* Firefox 60
* Firefox 60 + tweak

![Firefox 4 + Basic Bookmarks](/screenshots/firefox4+basic-bookmarks.png)
![Firefox 60](/screenshots/firefox60.png)
![Firefox 60 + Tweak](/screenshots/firefox60+tweak.png)


## License
MIT License
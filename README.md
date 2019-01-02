# UX Manifesto

This is a raw beta preview version.

## Laws
### 1. The most useful elment must be the most accessible

Negative examples:
- Google YouTube on Android. Open video in fullscreen. (You need to click anywhere on video, then click on tiny icon in the corner. Clicking on the video is already used for pause, and tiny icon is so small and near the end of the video progress bar, so I more often rewind video to the end instead of making it fullscreen). Solution: big button always visible in non fullscreen mode.
- Android sound volume. You need to lower the volume of the video before openning it, but you lower the call ring tone instead.

### 2. Navigation must have the opportunity to return

Negative examples:
- Google YouTube on Android. Press back, try to return where you've just been. (Accidentally press Back button and there is no forward button, so you have to go to the history to return to your video)

### 3. Navigation must be consistent
Checks:
- If you press Back and Forward or Forward and Back nothing must change. The same for multiple presses.

Negative examples:
- Instagram on Android. Touch the right part of the screen in the last story of the user and you will go to the next user's first unseen story. Touch the left part of the screen and you will go to the the previous story of this user, not to the previous user.
- Instagram on Android. Screen off and on and main screen is refreshed and you lost your position.

### 4. Nothing can be changed during user interaction without explicit permission

Negative examples:
- Microsoft Excel. Automatically autocomplete cell content without asking user.
- Microsoft VS Code. Autoclosing comment section.
- T9

### 5. Do not swallow important errors

Negative examples:
- Google Translate. Sometimes when pressing the star to add translation to your dictionary, the star just lights on, but nothing added. Solution: error notification.

### 6. No silent events

Negative examples:
- Mozilla Firefox. You accidentally close the tab and don't event notice it. Solution: notification.
- Microsoft Windows Explorer right mouse button context menu. Sometimes you know you miss-click, but you don't know where, and what happened. Solution: notification.

### 7. User input must be treated like god's gifts

Negative examples:
- Mozilla Firefox. You open new tab and start typing. The focus is not in search bar. You typings is going to nowhere.
- Google Translate. You can relogin and your text will be lost.

### 8. User needs to know what he already did, and what he already read

Negative examples:
- Instagram. You must remember the last photo you see, to not repeat yourself. And there can be gaps in between sessions that you never saw.

### 9. Long lists must be paged or virtualized.

Negative examples:
- Old Google Translate. Starred phraces list. Now fixed with paging.

### 10. No fake elements

Negative examples:
- Google Chrome on Android. Start screen. You click into the input box in the center of the screen to type text, but it animates itself to the top.
- Google Translate. Click on text box and it moves to top.

### 11. There can be no Internet connection

Negative examples:
- Google Play. White screen when Internet is not available nut Wifi is on.

### 12. There must be context

Negative examples:
- Browser. When you open a link from a search in a new tab and then navigate to it later, you don't know why you come opened it in a first place. Solution: history for new tabs, some indicator of the previous page. Tree Style Tab addon for Firefox allows align child tabs into parent tabs.

### 13. Sounds and vibrations must have the ability to be toggled off

### 14. No useless empty space

Negative examples:
- Windows Search initial screen.

### 15. No out of screen elements without indications

Negative examples:
- Google Search tools on mobile.

### 16. Errors must be informative

Negative examples:
- Microsoft SQL. Union All columns missmatch.
- SSRS. Parameter is not passed.

### 17. No implicit functions

Negative examples:
- LG TV. Dlna icon must appear but sometimes it does not, without any progress indication or error. Solution: button to connect to Dlna with informative error.
- Google Youtube on Android. The Cast to TV icon must appear but sometimes it does not. Solution: button to connect to TV with informative error.

### 18. List with more then five elements must have quicksearch.

Negative examples:
- MIUI App List

### 19. Ask everything possible before the long operation not during it

Negative examples:
- File copy with overwrite prompt. You wait for two big files to copy and only on third there is a dialog to overwrite. Solution: check all files and ask before operation, if something changes during operation postpone to the end of operation.

### 20. Do all quick checks before asking the user to enter some text

Negative examples:
- Borland Starteam. Asks for a comment and then shows error that the item must be locked before checking in.

### 21. Operations with multiple elements

Negative examples:
- Microsoft SSRS Designer. Try to change the font for multiple cells with different fonts.

### 22. Elements must not dissapear under the click

Negative examples:
- Microsoft Windows terminal in a window and language icon in parent system.
- Microsoft Windows uninstall list populating asyncronously.

### 23. Make it easy to remove errors

Negative examples:
- Mozilla Firefox. You once typed the misspelled url and will be seeing it forewer, until you search how to remove it from a list

### 24. Textbox must be followed by a button for long operations

Negative examples:
- Microsoft Nuget Package Manager. Search textbox works on key press not on enter or button click.

### 25. Long lists must have the ability to mark items as favorite and bring them on top

Negative examples:
- Microsoft Excel. Currency format list.

### 26. Advanced forms must have presets to return to previous options

Negative examples:
- IMDB Advanced Search

### 27. Remember user choice and suggest it. Allow user to remove suggestions.

Negative examples:
- Google Chrome on Android opens Google Map app without my persmission. Just because I chosed it once. To disable I must go to the apps, find maps, and clean defauls. Solution: floating notification with ability to disable navigation

### 28. No unnecessary constraints

Negative examples:
- Google Music playlist size
- Mi Band number of app for showing notifications

### 29. Language must contain language name in that language locale. And the language button must be universal to recognize.

Negative examples:
- Many chinese site where you try to toggle english version

### 30. No stale data on refresh

Negative examples:
- GMail. Shows old letters for a seconds when opening site for the first time in a session.

### 31. Undo everything

Negative examples:
- Microsoft Issue Vote. How to unvote?

### 32. Focus main element

### 33. Show some progress and allow cancelling of the asyncronous process

### 34. Text for checkbox must toggle it too

### 35. Do not lost search text on search

### 36. Make popups easy to dismiss

### 37. Explain non standard user interface features

### 38. Notify user if the operation is restarted from the beginning

Negative examples:
- Microsoft Word search.

### 39. Do not leave users with error. Make refresh button.

Negative examples:
- Google YouTube on Android. When no Internet connected.

### 40. Do not make tiny elements inside other active elements

Negative examples:
- MIUI Contact list. Every time you try to change conact info, you accidentally dial to it.
- Google YouTube video list.

### 41. Do not force the user to scroll your infinite scroll to top just to change filter settings

Negative examples:
- Reddit app

### 42. Child options must be disabled if main property is disabled

Negative examples:
- Insight timer options

### 43. Do not make tiny popups with menu that hide on mouse leave

Negative examples:
- IMDB vote from search

## Useful Links:
https://overreacted.io/the-elements-of-ui-engineering/

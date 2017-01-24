# Gitscout Desktop changelog

All notable changes to this project will be documented here.

## 0.6.2 - 24/1/2017

### community requests

- reorder Orgs/Users in sidebar [#46](https://github.com/gitscout/gitscout-feedback/issues/46)
- application self-update [#112](https://github.com/gitscout/gitscout-feedback/issues/112)
- added link to give feedback/report bugs [#96](https://github.com/gitscout/gitscout-feedback/issues/96)

### bugfixes

- fixed `quit` behavior [#127](https://github.com/gitscout/gitscout-feedback/issues/127) [#134](https://github.com/gitscout/gitscout-feedback/issues/134)
- fixed mouse to select some text from the search bar [#80](https://github.com/gitscout/gitscout-feedback/issues/80)
- fixed upload warning modal
- fixed a lot of typos

### new features

- customizable quick actions on issue swipe

## 0.6.0 - 11/1/2017

### community requests

- filter notifications by `participating` [#3](https://github.com/gitscout/gitscout-feedback/issues/3)
- refresh tickets/issues list/repository meta using `cmd+R` [#56](https://github.com/gitscout/gitscout-feedback/issues/56)

### bugfixes

- fixed typos [#108](https://github.com/gitscout/gitscout-feedback/issues/108)
- fixed sync repository labels/milestones [#110](https://github.com/gitscout/gitscout-feedback/issues/110)
- fixed milestones sorting

### new features

- improved `author` filtering
- improved @mention suggestion list
- saved search

## 0.5.8 - 2/1/2017

### community requests

- images use 100% of the available width [#98](https://github.com/gitscout/gitscout-feedback/issues/98)
- style inline code with a monospaced font [#102](https://github.com/gitscout/gitscout-feedback/issues/102)

### bugfixes

- fixed left click + CMD key on an issue [#11](https://github.com/gitscout/gitscout-feedback/issues/11) [#103](https://github.com/gitscout/gitscout-feedback/issues/103)
- fixed app auto launch [#101](https://github.com/gitscout/gitscout-feedback/issues/101)
- fixed unassignable with uppercase logins [#100](https://github.com/gitscout/gitscout-feedback/issues/100)
- fixed 'Close Window' behavior [#75](https://github.com/gitscout/gitscout-feedback/issues/75)
- fixed mute repository with upper case

### new features

- new login screen
- cristal clear account creation form
- add links to privacy policy and account benefits
- various UI tweaks

## 0.5.7 - 17/12/2016

### bugfixes

- fixed account creation [#91](https://github.com/gitscout/gitscout-feedback/issues/91)

## 0.5.6 - 16/12/2016

### community requests

- authentication in browser [#63](https://github.com/gitscout/gitscout-feedback/issues/63)
- remove "user full access" permission [#81](https://github.com/gitscout/gitscout-feedback/issues/81)
- mute repository notifications [#52](https://github.com/gitscout/gitscout-feedback/issues/52)

### bugfixes

- handle GitHub changes in `timeline` API
- fixed search pattern [#73](https://github.com/gitscout/gitscout-feedback/issues/73)
- hide meta options based on permission [#50](https://github.com/gitscout/gitscout-feedback/issues/50)
- prevent re-apply migrations [#89](https://github.com/gitscout/gitscout-feedback/issues/89)
- fixed 2FA by auth user in browser [#69](https://github.com/gitscout/gitscout-feedback/issues/69)

### new features

- prevent user to add a forked repositoy and propse original
- search, add support for "no:" filter

## 0.5.4 - 7/12/2016

### community requests

- Copy issue link [#51](https://github.com/gitscout/gitscout-feedback/issues/51)

### bugfixes

- fixed case sensitive organization/repository name
- fixed error when adding a new repository
- fixed navigation between issues in notifications view
- fixed search reset
- fixed search pills with multiple quotes
- fixed search escape filters
- fixed add reactions to new comment
- prevent reorder issues reorder when patch a ticket
- Arrow keys [#53](https://github.com/gitscout/gitscout-feedback/issues/53)

### new features

- add optional spellcheck
- auto-resize new comment form
- Smart Timeline, merge or remove similar events in Issue activity feed
- add navigation in the Image Viewer between images from the same comment
- add pagination to search results
- add subscribers in `@mention` list

## 0.5.2 - 15/11/2016

### bugfixes

- Users without personnal repositories can not access to App
- Display default message in search dropdown if no property in list like milestone
- Explicit placeholder to comment

### community requests

- Close popup with ESC key [#43](https://github.com/gitscout/gitscout-feedback/issues/43)

## 0.5.0 - 15/11/2016

### community requests

- Reactions!! :postal_horn: [#41](https://github.com/gitscout/gitscout-feedback/issues/41)
- Closed/Opened issues design [#27](https://github.com/gitscout/gitscout-feedback/issues/27)/[#30](https://github.com/gitscout/gitscout-feedback/issues/30)
- New comment box composer [#26](https://github.com/gitscout/gitscout-feedback/issues/26)
- Easy close issue [#19](https://github.com/gitscout/gitscout-feedback/issues/19)
- Notifications view [#3](https://github.com/gitscout/gitscout-feedback/issues/3)
- Inline comment [#40](https://github.com/gitscout/gitscout-feedback/issues/40)
- Manage owners/repositories from sidebar [#38](https://github.com/gitscout/gitscout-feedback/issues/38)

### new features

- Drafts: Now you can save new/edited ticket/comment as a draft :sunglasses:
- From the Notifications panel you can easily switch from new notifcations to archived ones
- A nifty `Mark all notifications as read` buttons, because to be honest, we all hate having a red dot notification thingie! :smile:


## 0.4.2 - 31/08/2016

### bugfixes

- Fixed broken icon in Settings Repositories section
- Fixed internal link color in issues comment
- Enlarge Quick switcher clickable zone
- Speed up form window opening
- Fixed left click + CMD key on an issue opens a new window [#11](https://github.com/gitscout/gitscout-feedback/issues/11)

### community requests

- Paste image from clipboard into comments [#39](https://github.com/gitscout/gitscout-feedback/issues/39)


## 0.4.0 - 29/08/2016

### community requests

- Keyboard navigation (up/down arrow keys) to navigate through issues [#33](https://github.com/gitscout/gitscout-feedback/issues/33)
- Repositories quick switch [#31](https://github.com/gitscout/gitscout-feedback/issues/31)

### bugfixes

- Fixed inline code block style in comments
- Clear Github authorization window session on logout
- Fixed Issues Filter Box when label contains a semicolon [#35](https://github.com/gitscout/gitscout-feedback/issues/35)

### new features

- Add extra repositories to your list
- Hit the `?` key to check out the shortcuts guide
- various UI tweaks


## 0.3.8 - 02/08/2016

### community requests

- fixed search text highlight/drag [#28](https://github.com/gitscout/gitscout-feedback/issues/28)
- add redo functionality for text [#24](https://github.com/gitscout/gitscout-feedback/issues/24)

### bugfixes

- @mention list now include repository subscribers
- do not display notification in dock icon for hidden repositories
- reinforce upload security

### new features

- updated issues are reodered on notification
- new look for comments from current user
- added comment deletion
- modal dialog to prevent user to close form while writing
- active ticket is updated upon receiving a notification

## 0.3.6 - 26/07/2016

### community requests

- define visible repos/organizations in the sidebar (in Preferences > Repositories) — This is the first step to let you reorder your repos/organizations and add extra repositories [#7](https://github.com/gitscout/gitscout-feedback/issues/7) [#2](https://github.com/gitscout/gitscout-feedback/issues/2) [#17](https://github.com/gitscout/gitscout-feedback/issues/17)
- put current user on top of filter lists [#18](https://github.com/gitscout/gitscout-feedback/issues/18)

### bugfixes

- edit/post new comments from todo tickets
- fixed missing emojis

### changes

- remove open issues number badge from sidebar
- update cog, search, comment and issue meta icons
- update settings tabs icons
- update form buttons design


## 0.3.4 - 19/07/2016

### community requests

- submit a new issue/comment in preview mode [#6](https://github.com/gitscout/gitscout-feedback/issues/6)
- add `cmd+h` and `alt+cmd+h` shortcuts [#8](https://github.com/gitscout/gitscout-feedback/issues/8)
- enable `cmd+f` shortcut to focus search input [#10](https://github.com/gitscout/gitscout-feedback/issues/10)
- display relative date for 7 days from today then use full date. Add tooltip for more accurate information [#12](https://github.com/gitscout/gitscout-feedback/issues/12)
- display last updated date in list rather creation date [#4](https://github.com/gitscout/gitscout-feedback/issues/4) and [#13](https://github.com/gitscout/gitscout-feedback/issues/13)

### bugfixes

- fixed issue state in search
- display all member of a repository [#16](https://github.com/gitscout/gitscout-feedback/issues/16) and [#5](https://github.com/gitscout/gitscout-feedback/issues/5)
- markdown support for table and blockquote

### new features

- allow multiple assignees on issue
- close meta popup on `esc`
- scroll sidebar list to active repository

### change

- issue states look more obvious.

# MakeCode Arcade Common Questions
This is a list of common questions and answers, to answer questions that people frequently ask about Arcade! If you have a question about Arcade that isn't on this list, feel free to open an issue about it, including the question and the answer if you know it. I will most likely add it to the list if the answer is stated or known by me! You can also submit a pull request but be sure to include an entry in the table of contents as well as the question and answer! If there is something on this list that isn't factual and/or is unclear, then also feel free to make an issue about it.

## Table of Contents
- [User Interface](#user-interface)
	 - [How do I share my project?](#how-do-i-share-my-project)
	 - [How do I host an online multiplayer game?](#how-do-i-host-an-online-multiplayer-game)
	 - [How do I allow other people to join my online multiplayer game?](#how-do-i-allow-other-people-to-join-my-online-multiplayer-game)
	 - [What do I do if the simulator next to the editor has a black screen or is extremely slow?](#what-do-i-do-if-the-simulator-next-to-the-editor-has-a-black-screen-or-is-extremely-slow)
- [Code](#code)
	- [Why do my sprites go the wrong way when I change their "Y" value?](#why-do-my-sprites-go-the-wrong-way-when-i-change-their-y-value)
	- [How do I add extensions?](#how-do-i-add-extensions)
	- [How do I run an action for every sprite of a certain kind or every one of a certain tile?](#how-do-i-run-an-action-for-every-sprite-of-a-certain-kind-or-every-one-of-a-certain-tile)
- [Where can I communicate to the MakeCode team and other users about issues I have?](#where-can-i-communicate-to-the-makecode-team-and-other-users-about-issues-i-have)

## User Interface

### How do I share my project?
To share your project, copy/pasting the link at the top of the page will **not** work. You must click on the share button near the top-right corner of the screen. This will bring up a window showing a preview of what you are sharing. If signed in, you can either check or uncheck the box for "update existing share link", and if this box is checked, the existing share link will update. Otherwise, it will make a new share link. Click "Share Project" to get your link or "Host a multiplayer game", which will ask you if you want to share and host a multiplayer game. If you click "Share and Host", it will take you to a separate tab for hosting multiplayer of that game.

### How do I host an online multiplayer game?
To host an online multiplayer game, you can either click "Host a multiplayer game" in the share preview, or click "Host Game" on the top-right in an already-shared game that any code for controls for another player.

### How do I allow other people to join my online multiplayer game?
- Send them the link that can be copied by clicking the button next to the join code (The join code is in the middle of the screen before the game, but moves below the simulator once the game starts.)
- Have them go to [https://aka.ms/a9](https://aka.ms/a9) and enter the code shown
- They can also scan the QR code (only before the game starts).

### What do I do if the simulator next to the editor has a black screen or is extremely slow?
If this is happening and is not the result of slow code, the first thing to try in a situation like this is to close the simulator using the arrow to the right of the simulator in the center of the screen vertically, then open it again by clicking the arrow again (it has now moved to the far-left of the screen.) If that doesn't fix the issue, try reloading the page. If the simulator still doesn't work properly, you may want to file a bug report [here](https://github.com/microsoft/pxt-arcade/issues/new/choose).

## Code

### Why do my sprites go the wrong way when I change their "Y" value?
In Arcade, the "Y" axis is the opposite of most other game development platforms and graphs. To go down, the "Y" position must be increased, and to go up, the "Y" position must be decreased.

### How do I add extensions?
To add an extension, you can go down to the bottom of the blocks categories, and the last button before the "Advanced" section says "Extensions." Once you click the "Extensions" button, it will take you to a separate screen showing a list of recommended extensions. You can either click on the one you want from the list or search for one in the search bar. In the search bar, you can also type the URL of extensions that are not shown in the "Recommended" list. There are many great extensions that are not considered "Recommended", many of which can be found UnsignedArduino's list of [Awesome Arcade Extensions](https://github.com/UnsignedArduino/Awesome-Arcade-Extensions). (The extension list is what inspired me to make this list of common questions.)

### How do I run an action for every sprite of a certain kind or every one of a certain tile?
A "for "value" of "list" do {}" block is the easiest way to do this. After you pull out one of these blocks, place an "array of all sprites of kind (kind)" block into the area that says "list" to repeat for all sprites of a certain kind, or use an "array of all (tile) locations" block in the area that says "list" to repeat for all instances of a certain tile. You can drag out the "value" block from the "for "value" of "list" do {}" block and it will act like the sprite or tile that is currently being looped over.

## Where can I communicate to the MakeCode team and other users about issues I have? 
- A great place to communicate to other users as well as the MakeCode team is the [MakeCode forum](https://forum.makecode.com/). Here, you can ask questions, collaborate with other users on projects, and even share your own projects just for fun!
- Another great way to communicate with the MakeCode team is on their Twitch stream, the [MakeCode Arcade Advanced Stream](https://www.twitch.tv/msmakecode). This stream is currently on Monday, Wednesday, and Friday at 4:00 PM EST and 1:00 PM PST. In this stream, some developers from MakeCode team make games, play game jam/mini game jam games, answer questions from the chat, and interact in other ways with the chat.
- There is also a [MakeCode YouTube channel](https://www.youtube.com/@MicrosoftMakeCode) where the developers share tutorials and tips about MakeCode. They also stream the MakeCode Arcade Advanced Stream here.

Written with [StackEdit](https://stackedit.io/).

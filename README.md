# Sun Spot Beta

This is a tutorial/guide for using SunSpot Beta.

## Start

Once the app is installed, and you open it, you will be presented with a login screen, asking you to login with facebook. Log into the application using a facebook account. Once logged it you will be presented with the Rooms screen:


## Rooms

![img](https://raw.githubusercontent.com/i3i2uno/sspot/master/images/roomBlank.png)

Start by clicking the "+" button in the bottom right. This will open up a create room window:

![img](https://raw.githubusercontent.com/i3i2uno/sspot/master/images/createRoom.png)

The top line is the important part and is the only thing required when creating a room. This is your "roomID" and this is what is important when telling friends or others what room to join. Once created, this room will exist forever!

The other fields are optional. Password, if used the room will require a password to be input in order for others to be able to join the room.

Once your room is created click on your room. This room will now be in your list moving forward. Rooms with a Orange "user" icon to the left of the room are rooms that you created, and that you have control over, you are the "Super Admin". If you see a grey "user" icon to the left of the room this means that you are the "Current Admin". If there is no icon then you are neither.

### Room Search

You can toggle between your rooms and searching for other available rooms by toggling between the two top header buttons.

![img](https://raw.githubusercontent.com/i3i2uno/sspot/master/images/roomSeachToggle.png)

When you click the button on the right, signifying that you are searching for rooms, you will be presented with three buttons on the bottom on the screen. The first button which is automatically selected will be the top 100 most popular rooms, based on the amount of current live users listening. The second button is a list of all of your friends. When you click on a friend, it will then show you all of his/hers rooms. Click any room at any time to join it. If it has a password, you will be asked for it, if successful you will join the room. The search Button allows you to search by roomId, or by tags, or both.

![img](https://raw.githubusercontent.com/i3i2uno/sspot/master/images/roomSeach.png)

Once you join the room, if it isn't currently in your list, you can click the "squared arrow" button in the bottom left.

![img](https://raw.githubusercontent.com/i3i2uno/sspot/master/images/addToRoomBtn.png)

## Tracks

Once you click into a room you will then see the "Tracks" screen. This is the collection of tracks that are in the room. 

![img](https://raw.githubusercontent.com/i3i2uno/sspot/master/images/tracks.png)

If this is your room, or you have "Admin" capabilities then the "+" icon will be in the bottom right of the screen. This is what you will click on to add tracks. Click this icon and you will see the "Add Tracks" search screen:

![img](https://raw.githubusercontent.com/i3i2uno/sspot/master/images/createTrack.png)

Start typing on the search bar to begin receiving results. Right now the search is pulling from youtube. So you are essentially searching youtube. Once you find a track you like click it. Otherwise click the top x to clear your results and then close the page.

![img](https://raw.githubusercontent.com/i3i2uno/sspot/master/images/trackSearch.png)

If you do not have "Admin" access in the room, and are instead just a listener, you can still click the "three dots" to the right of the track to add to any of your rooms. So if you see a track of someone elses that you like select this option to quickly add it to your own room.

![img](https://raw.githubusercontent.com/i3i2uno/sspot/master/images/addTrackToRoom.png)

The "play" icon in the top right of the black bar is a toggle switch to toggle between the room information, and the current track playing. 

### Take control

You can take control of a room if no one is in the room. When you enter the room you will see the "Take Control" icon in the top right of the black bar next to the "current track" btn:

![img](https://raw.githubusercontent.com/i3i2uno/sspot/master/images/takeControl.png)

This button will give you "Temp Admin" control of the room, and you can click any of the tracks in the room to start DJ'ing. If the "Super Admin" or the "Current Admin" joins the room, they can click that button and take contol at anytime.

You will also see this "Take Control" feature on the "Middle button" of the Users page:

## Users

The users screen gives you three options. The furthest left, first, option is the list of your friends that are currently using the app, and what room they are currently located in. You can click on any user in the list to join the room that he/she is immediately and start listening with them.

![img](https://raw.githubusercontent.com/i3i2uno/sspot/master/images/users.png)

The second, middle, option is all of the users in the room that you are currently in. 

If you are the "Super Admin" of the room then you will see a "Take Control" icon next to the user. 

![img](https://raw.githubusercontent.com/i3i2uno/sspot/master/images/userControl.png)

If you click the button next to the user you will pass control to that person and then they will have the ability to control the room. They can add tracks, reorder tracks, and play tracks. They become the current DJ. But you can always click the "Take Control" icon on the Tracks screen to "Take Back Control".

The furthest, third, option is a chat window, where you can talk with all of the users currently in the room that you are in.

## Misc

To logout click the hamburger icon in the top left, then select, "logout".

# Thing Added in V2

* Graceful WIFI/DATA switch, and alert the user when the device is not actually "connected" to the room
* Room Search
* Better user aknowldgement
* Start to a tutorial driven experience
* Better shuffling
* Help button that will shoot you right to this site

# Known Issues

* ~~Messages screen on android spreads full screen.~~
* ~~Switching from Wifi to Cell Data will crash (Not tested on iOS)~~
* ~~Coming in and out of Sleep/Lock screen can cause disconnect from room. Completely close/destroy the app. Then restart.~~
* Music stops on incoming call, but __NOT__ once you answer the call! Need to pause the music then answer the call. (Not sure about this on iPhone)
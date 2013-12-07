# Simple WebRTC Demo

This is a fork of keithnorm's [Simple Webrtc Video Chat](https://github.com/keithnorm/simple-webrtc-video-chat).  The purpose is for showing 
some of WebRTC's features to the members of the [Louisiana State Bar Association's Access to Justice Tech Committee.](http://www.lsba.org/atj/)

WebRTC is a peer to peer standard allowing browsers to connect directly and transfer information without a central server. This means you can video chat
with clients and colleagues without the use of third-party services like Skype and Google Hangouts. Note that all webRTC streams are encrypted with 128-bit AES.

# Get It Running
## (Requires node.js)
    git clone https://github.com/judsonmitchell/simple-webrtc-video-chat.git
    cd simple-webrtc-video-chat
    npm install
    node app.js

Then open up two browser windows pointed to `localhost:3002/your_room_name`. 

You should see something like this two video images of yourself.  

If you want to chat with someone, simply send them the url, e.g http://your_web_facing_server:3002/your_room_name

![screenshot1](http://f.cl.ly/items/0d223G2I1K3H381v1H3E/Screen%20Shot%202013-01-13%20at%203.09.17%20PM.png)

Note that, as of December 2013, WebRTC is only supported in Chrome and Firefox.

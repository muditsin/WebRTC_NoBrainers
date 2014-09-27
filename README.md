webRTC_video_chat_NobRainers
============================

A Basic webRTC video call system 

INstructions :
1) Start apache / any other server of your choice.

2)Place the extracted  files to a folder named webrtc (for convenience) inside its htdocs or www(in case of wamp).


2) Fire up the terminal and do a change directory i.e. cd to the extracted folder (webrtc) inside htdocs.

3) write the following commands in terminal :
    
    
      " npm install peer -g"   // for Installing the library
      
      then 
      
      "peerjs --port 9000 --key peerjs" //  for  Running the server
      
4) then go to http://localhost/webrtc in your browser . and enjoy

Note : ports and key can be changed since it is a custom server .

Further plans: 

1) to implement file sharing and group chat in it so as to easily share ID among users .

2) to work upon UI .

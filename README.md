# javascript-record-video

Learn how to access media devices in browser, manipulate video and capture video from camera using browser's navigator object


Many browsers now have the ability to access video and audio input from the user. However, depending on the browser it might be a full dynamic and inline experience, or it could be delegated to another app on the user's device.


The easiest thing to do is simply ask the user for a pre-recorded file. Do this by creating a simple file input element and adding an accept filter that indicates we can only accept video files and a capture attribute that indicates we want to get it direct from the camera.

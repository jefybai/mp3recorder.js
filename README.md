# mp3recorder.js
mp3 recorder tool using a worker for encoding into mp3 format
<b>Object<b>
var r= new Recorder(options) where options is object setting possible events
<b>Api</b>
<pre>
pause: to pause the recorder
resume: to resume the recorder
getElapsedTime: get the recording elapsed time
isPaused: if the recorder is recording or not
start: to start the recordering
stop : to stop the recordering
</pre>
<b>Events</b>
<pre>
onInit(context,processor): when the audio context is created
onPause: paused the recorder
onResume: resumed the recorder
onStart: started the recordering
onStop : stopped the recordering
onCompleted(blob,elapsed): when mp3 is generated
onError(message): when a error occurs
</pre>

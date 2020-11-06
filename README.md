# shapeMaker
Shapemaker a tool designed to help cut shapes from a corpus of tiny sound files (perhaps made with [FluCoMa](https://www.flucoma.org/) or [Aubio](https://aubio.org/)). 

# shapeMaker is not clever, but you are 
This tool was built for sound designer, not computer programmers. When you understand the principles of how it works, it's your design skills that will be key to getting the best out of it. Your decsisions on timing, sound naming and structuring end up having direct consequences on what sounds come out, though you may of course begin playing with the tool in a fairly arbitrary way. There is also the possiblity to be able to perform with the shape maker using a live microphone, or to use a sound file to trigger playback through a curve of sound files. 

Crucially, shape maker does not use any clever analysis tools to understand your audio better and to understand your sound for you, rather, you organise it into folders and use your ears, organisation, taste and design skills to make decent sound outputs in the end. If you're looking for tools that will help you at an algorithmic level, then watch developments at [FluCoMa](https://www.flucoma.org/) and further developments by amazing python programmers such as [Chris Tralie](https://github.com/ctralie), [James Bradbury](https://github.com/jamesb93/) or [Brian McFee](https://github.com/bmcfee). 

# stereo or mono
shapeMaker detects if a file is two channel or mono. When mono, the sound is panned according to the path you design, if it is stereo, the line is bypassed and the stereo sound is played (and recorded). 

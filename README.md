Hello, welcome to my sound project. Thank you for your time for looking at this.

This project is something i tried to do when i was in university using matlab, but i never was able to get this working back then.
Now i would like to give it another go, this time using python.

The project is in the field of TRANPORTATION - SMART CITIES. The goal is to be able to identify the state of traffic lights those are near pedestrian crossings
and let the user know if they should WALK or WAIT.

(You know) each traffic light is also assisted with some "clicks", to help the deaf people.
If the clicks are faster you should WALK, if they are slow you should WAIT.

The goal of the program is to "listen" to the environment and detect BPM of this clicks and decide if WALK or WAIT.
I have started on PC, not even using mic, just loading prerecorded wav files, and i am using Pycharm.
i have ideas to carry this on mobile, just to have the experience of it.

I am thinking my project has to go following steps in development:

1. Using simple only pre-recorded beat sample audio files, find bpm of each clicks
2. decide wait or walk
3. do the same thing with harder audio files, field recordings with backgroud noice etc, try identify the clicks.. (use some kind of fourrier transforms?)
4. do the same thing now with mic, using PyAudio, listen to environment, find bpm, decide wait or walk
5. move to mobile platform (in what language?)
6. try design good simple interface, easy to use.. just to learn how to best design for mobile applications.

So far i am working with very simple beat samples,
https://www.youtube.com/watch?v=uweCjzCSXR0 (180 bpm) and 
https://www.youtube.com/watch?v=DWQeXSq3L1I (100 bpm)

and am just able to read these files using wave module and plot it using matplotlib.
(i found this code from
https://www.geeksforgeeks.org/plotting-various-sounds-on-graphs-using-python-and-matplotlib/)

i can clearly see the beats in this graph,
but i am clueless how to spot the peaks, how to count the beats, and eventually get it back to time frame and find the BPM.

# Voice-Controlled-Car
This was an ECE hackathon that I participated in this past week (January 2025). My team made a car that was controlled by speech commands.

For the project, we used an ESP32 to connect to the computer via Bluetooth and then control the motors in the car via Arduino software. 
My role in the project was primarily to work on the javascript and HTML code that made up the website and ran the speech recognition software.

The esp 32 code was built from this walkthrough by Random Nerd Tutorials: https://randomnerdtutorials.com/esp32-web-bluetooth/. 
It was a big help in understanding how esp32s work and how to use them effectively in JavaScript/HTML.

The speech recognition code was built using compromise pulled from: https://unpkg.com/compromise@14.14.3/builds/compromise.js.
This was an enjoyable thing for me to implement because I did not know a lot about it, so working to implement it and seeing the processing in real-time on the webpage was super cool.

After implementing the speech recognition and the esp32 code I needed to add a NLP to parse the words being said and turn them into commands that could be sent to the esp32. 
Part of me thinks that the NLP stuff was basically if the string includes "go" or stuff like that but it worked well so we kept it. 
I also implemented fuzzy matching from https://cdn.jsdelivr.net/npm/fuse.js@6.4.6/dist/fuse.min.js but, again, I am not entirely too sure if that added anything to the project.

After implementing the core functionality, a lot of the tweaks were UX/beauty upgrades to make the website more appealing.
We did a Mario kart theme so music and sounds were added to fit into the Mario theme.
I also learned about making HTML more interactive and hiding divs after pressing buttons which was cool to see and implement.

In the end, this was a super fun project and the last time I could do this ECE hackathon with my friends so I am super happy and proud of the work that I accomplished.
I have done some javascript and html before but it was fun to go back to it and refresh my memory.

If I had more time, I would have loved to implement multi-step commands but a lot of that would have been on the Arduino side which was one of my teammate's focus.
The functionality was there on the JavaScript side, theoretically, but it still would have been fun to see it in action. 

I also think it could be interesting to try to train my own NLP model because, in this project, I used a preexisting one. 
On the other hand, a large aspect of life is using other people's tools effectively with limited understanding.

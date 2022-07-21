# Drum-Kit

## Demo: https://islamkamalx1.github.io/Drum-Kit/

-We have 9 divs and 9 audios each one with [data-key] custom attribute that specifies the key code for the characters [A,S,D,F,G,H,J,K,L].

-playSound() function that select the div and audio which you click it's character on the keyboard, play the sounds, and adding the class playing to the div with the key you clicked.

-Adding the playSound() to an event Listener ("keydown") as a callback function.

-removeTransition() function that check if the div dosen't has property name => "transform" then skip this div, if has? remove the class playing from the div.

-Then select all keys and foreach key will add an event Listener ("transitionend") and passing the removeTransition as a callback function.

-You can play the sound on "keydown" or "click" event😂.

![speak-number-guessing-game](https://user-images.githubusercontent.com/74613776/110243584-0701cf80-7f81-11eb-972d-181a1a94f8d0.PNG)

# Speak Number Guessing Game

This is a number guessing game but instead of typing in a number you're actually going to speak it. As soon as you start talking it's going to record your voice.

This projects uses [SpeechRecognition API](https://developer.mozilla.org/en-US/docs/Web/API/SpeechRecognition) which still is in experimental technology.

## IMPORTANT (for Firefox Users):

* In order to use microphone in the application Firefox users has to change flags in the browser.
* Go to the URL bar and search for, "about:config".
* Then click on "Accept the Risk and Continue".
* On Search preference name, search for "media.webspeech.recognition.force_enable" and set it to true.
* Again on Search preference name, search for "media.webspeech.recognition.enable" and set it to true as well.

## NOTE:

* You have to allow the application to access your microphone on prompt.
* On some browsers, like Chrome, using Speech Recognition on a web page involves a server-based recognition engine. Your audio is sent to a web service for recognition processing, so it won't work offline.

## Deployment

https://speak-number-guessing-game.netlify.app/

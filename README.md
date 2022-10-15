# Text_To_Speech
Text to speech is a process to convert any text into voice. Text to speech project takes words on digital devices and convert them into audio with a button click or finger touch. Text to speech python project is very helpful for people who are struggling with reading.

To implement this project, we will use the basic concepts of Python, Tkinter, gTTS, and playsound libraries.

# Tkinter
A standard GUI Python library that is one of the fastest and easiest ways to build GUI applications using Tkinter.

# gTTS (Google Text-to-Speech)
A Python library, which is a very easy library that converts the text into audio.

# Playsound module
The playsound module is used to play audio files. With this module, we can play a sound file with a single line of code.


The objective of this project is to convert the text into voice with the click of a button. This project will be developed using Tkinter, gTTs, and playsound library.

In this project, we add a message which we want to convert into voice and click on play button to play the voice of that text message.

<ul>
<li>Importing the modules</li>
<li>Create the display window</li>
<li>Define functions</li>
</ul>


## 1. Import Libraries
## 2. Initializing window

Tk() to initialized tkinter which will be used for GUI
geometry() used to set the width and height of the window
configure() used to access window attributes
bg will used to set the color of the background
title() set the title of the window

### Label() widget is used to display one or more than one line of text that users can’t able to modify.

root is the name which we refer to our window
text which we display on the label
font in which the text is written
pack organized widget in block
Msg is a string type variable
Entry() used to create an input text field
textvariable used to retrieve the current text to entry widget
place() organizes widgets by placing them in a specific position in the parent widget

## 3. Function to Convert Text to Speech in Python

Message variable will stores the value of entry_field
text is the sentences or text to be read.
lang takes the language to read the text. The default language is English.
slow use to reads text more slowly. The default is False.

As we want the default value of lang, so no need to give that to gTTS.

speech stores the converted voice from the text
speech.save(Converted.mp3’) will saves the converted file as DataFlair as mp3 file
playsound() used to play the sound


## 4. Function to Exit

root.destroy() will quit the program by stopping the mainloop().

## 5. Function to Reset

Reset function set Msg variable to empty strings.

## 6. Define Buttons

Button() widget used to display button on the window
root.mainloop() is a method that executes when we want to run our program.

# Summary
We have successfully developed the text to speech python project. We used the popular tkinter library for rendering graphics on a display window, gTTs (google text to speech) library to convert text to voice, and playsound library to play that converter voice from the text.
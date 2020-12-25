# Voice Controller

Voice Controller is a desktop application that facilitates its users to operate computer using voice. 
The software can recognize **Bangla** and **English** language. So, we can choose the language whether we want to operate it in Bengali or English. 
The motivation was making computer to a higher level where we have to ask it to do something and that will be done, without any direct interaction with it.

There are some fixed commands that can be done with this software like: "open file explorer", "minimize", "close window", "press enter" etc. The available command list for 
both languages are given in instructions section in the software.

We also have two modes - Safe Mode (recommended) and Full Active Mode. User can select any mode. In safe mode some sensitive commands like "shut down computer" or 
"delete it" etc. will not work. User can also send the application to system tray.

## Technology Used

Java and Java Swing is used to make this software. We also use Python, Perl and some codes and tools of CMUSphinx for training and testing the speech recognition models.

For speech recognition we followed the instructions provided by **CMUSphinx** https://cmusphinx.github.io/wiki/tutorial/ . 

The models for English language was been taken from CMUSphinx and we collected dataset for Bengali language and train models by following the instructions of 
CMUSphinx.

## Notes

Read the instructions carefully before use. The speech recognition models can't give 100% accurate result so sometime it can misread a command. 
A noisy environment can cause some costly actions. So, it is recommended to use the safe mode option, give command clearly and keep the software in sleeping in idle time.
One must have jre to run this software.


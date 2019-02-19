# Dante
A privacy focused voice assistant written in Python.  Modular, Simple.  
Skills can be written in Python as a simple function (see the example file)

How it works:
  1) Once pocketsphinx hears the wake word, Google is called to transcribe the rest of the command.
  2) The 'skills' file is checked to see if the word matches a function.


To Do:
  Thinking about implementing Docker or Kata Containers in one of the following ways:
    1) Either containerizing all of it
    2) Containerizing the Google portion so the Google packages are not even on the main system
    3) Containerizing 'skills' so that they are easily swappable.
  Implement an alias or 'fuzzy' command system

# TriviaGame
html5 trivia game

the things you might want to change:
The image which is in the assets folder, keep the size at 1200x600 and in the js folder change the line in the Main.js (game.load.image("backing", "assets/backing1.jpg");) the part that says backing1.jpg change to your image name and extension once you place it in the same folder
Other Main.js lines you can change
to add more questions and answers, make sure the answers are in the same order as the questions or they will appear wrong
questions are in the questionArray array
answers are in the answerArray below it
make sure they have placed between "" and add a comma at the end (except the last q and a)
I kept each one on a separate line to make it easier.
When you add a q and a also add another number to the startArray (which reads how many their is, if you don't add another number it will only read the amount that it shows ie: in this example it will only read the first 4 question as arrays start with 0 not 1).
you can change the question and answer font color in these 2 sections (vars)
questColor and answColor
If you want to change the speed on how long the q and a appear you can change the number in the maxTimeAllowed section (var) question will be half the time, example question will be around 10 seconds as will the answer

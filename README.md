# Rock-Paper-Scissors-Game
This project allows the user and the computer to play rock-paper-scissors. The user can select rock-paper-scissors by using switches. Pressing switch 0 selects rock, pressing switch 1 selects paper, pressing switch 2 selects scissors.
● Switch 0 = Rock
● Switch 1 = Paper
● Switch 2 = Scissors

Push Button 0 is pressed to finalise the decision and select an option on the computer. The choices made by the user on the computer are shown on the seven-segment display screen. If a rock is selected, “r” appears on the rightmost screen. If rock is selected on the computer, “r” appears on the 2nd screen from the right. “P” appears for the paper option and “S” for the scissors option.
● User preference is indicated in HEX0 by the symbols “r”, “P”, and “S”
● The machine preference appears with the same symbols in HEX1

The score of the game is displayed on the first 2 screens of the Seven segment display. For example, if the user wins 1 game, then “0,1” is displayed. The first person who reaches 5 in the game wins the game. If the user wins, 6 LEDs light up and “U” appears on the seven-segment display screen. If the computer wins, only 2 LED lights up and “L” is written on the seven-segment display.
● If the user wins, 6 LEDs light up and the letter “U” appears.
● If the machine wins, 2 LEDs light up and the letter “L” appears.

After the first round of the first game, the PUSH button 1 must be pressed for the second round. After push button 1 is pressed, the second round can be started. After reaching the first 5 and finishing the first game, the PUSH button 3 must be pressed for a new game. If you want to start a new game in the middle of the game, PUSH button 2 must be pressed.
● Button 1 = Continues to the next round
● Button 2 = Resets the instant game
● Button 3 = Starts a new game at the end of the game

-------------------------------------------------------------------------------------------------------------------------------------------------------

As seen in Figure 1, when we press the switch 0 button and press the PUSH button 0, our “rock” selection appears on the seven segment screen. In Figure 1, the user has selected “rock” and the machine has selected “paper. And it seems that the machine is 1-0 ahead.
<img width="798" height="374" alt="Ekran Resmi 2025-07-24 23 01 14" src="https://github.com/user-attachments/assets/6a787005-f0a3-47e1-8eea-7c434fb6bd05" />


Figure 2 shows that the user selects “paper” and the machine selects “rock”. In the Seven segment display, this situation is shown as “P” for the user and “r” for the machine. As a result, the situation is a “1-1” draw.
<img width="802" height="298" alt="Ekran Resmi 2025-07-24 23 01 56" src="https://github.com/user-attachments/assets/0ef5ec53-2a1d-4383-aac8-ff989e65a499" />


Figure 3 shows the user's selection of “scissors” and the machine's selection of “paper”. In the Seven segment display, this situation is shown as “S” for the user and “P” for the machine. In this situation, the user is “1-2” ahead.
<img width="798" height="278" alt="Ekran Resmi 2025-07-24 23 02 38" src="https://github.com/user-attachments/assets/318c4725-cc96-42a1-9da6-b80f6fd0cf32" />


Figure 4 shows that PUSH button 1 is pressed for a new round in the same game.
<img width="796" height="300" alt="Ekran Resmi 2025-07-24 23 03 13" src="https://github.com/user-attachments/assets/1e3edac4-41d8-4814-aa67-869d65d10784" />


In Figure 5, it is seen that when the user wins the game, that is, when the user wins the 5 rounds, 6 LEDs light up and “U” is written on the seven-segment display screen.
<img width="800" height="286" alt="Ekran Resmi 2025-07-24 23 03 45" src="https://github.com/user-attachments/assets/cb33a77a-50de-4347-af86-0daeaa6a9232" />


Figure 6 shows that when the machine wins the game, 2 LEDs light up and “L” is written on the seven-segment display screen.
<img width="800" height="310" alt="Ekran Resmi 2025-07-24 23 04 21" src="https://github.com/user-attachments/assets/4c67c53e-7f1a-424c-bc07-1c4d59e882bc" />


To start a new game, PUSH button 3 must be pressed as shown in Figure 7. After the push button 3 is pressed, the new game and new round starts from zero.
<img width="801" height="303" alt="Ekran Resmi 2025-07-24 23 04 54" src="https://github.com/user-attachments/assets/4e4d1d77-b846-4aff-a923-6f202a66b978" />



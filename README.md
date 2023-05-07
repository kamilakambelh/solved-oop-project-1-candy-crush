Download Link: https://assignmentchef.com/product/solved-oop-project-1-candy-crush
<br>
5/5 - (1 vote)

The objective of project is to make a game in which Player swap one gem with an adjacent gem with the help of mouse(Drag &amp; Drop) to form only horizontal or vertical chain of three or more gems of the same color, (an idea of game can be taken from the screenshot given at end). Bonus points are given to player when chains of more than three identical gems are formed, but also when two chains are formed in one swap. When chains are formed, the gems disappear, and gems fall from the top to fill in gaps. Sometimes chain reactions (referred to as cascades) are triggered, where chains are formed by the falling gems. Cascades are awarded with bonus points. Be creative as you can in drawing gem and game board.

Following features should be added to the game:

<ol>

 <li>1)  Take Name of player as input.</li>

 <li>2)  Drawing of game board in the start of game</li>

 <li>3)  You can match Rows and columns (No diagonal matches allowed)</li>

 <li>4)  ThereshouldbeaHintbutton,whentheplayerclickshintbutton,highlightthegemsthatcanform a chain and the score &amp; progress bar should be depleted.</li>

 <li>5)  Progress Bar should be displayed.</li>

 <li>6)  Next Level will require specific amount of points/coins.</li>

 <li>7)  A menu also be included optioning Levels, Level Modes, Highest scores and Settings etc.

  <ol>

   <li>a)  LevelsincludeListoflevels(completedlevelsshouldbedisplayedbrightandincomplete levels be dark)0</li>

   <li>b)  Level Modes include difficulty of level (at least two modes)</li>

  </ol></li>

</ol>

i) Normal Mode

In Normal Mode, the player fills up the progress bar on the bottom of the screen by matching gems. The game starts with an empty progress bar and the game will not ends in between level in this mode. When the progress bar is filled up completely, the player goes to the next level. As the level progresses, more points are required to proceed to the next level. As the player levels up, they get more points by matching gems (example: Level 1= 100 pts., Level 2= 150 pts. etc.).

ii) TimeTrialMode

In this mode, the gameplay mechanics are like Normal Mode, but the progress bar starts half- way filled. The player must keep the bar filled by matching gems, and they will level up by filling the progress bar. The game ends if the progress bar is depleted completely.

Note: Game difficulty will increase (means more points will be require for completing current level), with the level increase.

c) Highest Scores include top 4 highest scores, the player has achieved till then

d) Settings will include Music and sound option, Player profile and How to Play options etc. 8) Game must include Play and Pause Button.

9) There should be at least 5 types of gems (max 8 gems), each gem will carry equal points. When four gems chain are formed, player gets bonus triple points (x3). When Player forms five gems, points will be added 5 times more (x5).

10)Game Control will be Mouse only. While Play/Pause, Hint, Music On/Off, How to play, profile Buttons can be control using some keyboard keys (for example, H key for Hint)

File Handling

<ol>

 <li>1)  Playercanresumegame(afterleavingmidway).Youneedtostorenameandhiscurrentstate of game</li>

 <li>2)  High scores will be stored in files with names.</li>

 <li>3)  Playerprofilewillalsobestoredinfiles.Inplayerprofileyouneedtostorethenameandhishighest level along with the game state of his highest level.</li>

</ol>

Marks Deduction

<ol>

 <li>1)  If more than 1 Global Variable has been used in coding (Maximum 1 variable allowed).</li>

 <li>2)  If code has been written without classes.</li>

 <li>3)  If coder has not applied Programming Practice.</li>

</ol>

Bonus Points

Bonus marks will be given based on

<ol>

 <li>1)  Creativity on Game Board.</li>

 <li>2)  Graphics of Game.</li>

 <li>3)  lives of players to clear game board/level.</li>

 <li>4)  GameAesthetics.</li>

 <li>5)  Player Profile (can include Name of Player, number of levels completed both in normal andtime trial mode, Language, completion rate etc)</li>

</ol>

Some guidelines from the given code:

In the skeleton code you are given game.cpp, util.cpp, util.h, install-libraries.sh and Cimg.h files

In game.cppYou have been given “MouseClicked” function in which you can code for right click or left

click.

Also a function named as “MouseMoved” which is called when the mouse cursor is moved and the coordinates of mouse will be stored in x and y variables.

But you need to drag the gems so another function named “MousePressedAndMoved” is given, which you can use and build your logic according to the functionality.

For game execution:

First you have to install libraries by opening terminal in project folder and run a commad “ bash install-libraries.sh”
# Deep Learning Mahjong [麻將]

## Mahjong [机器学习 深度学习 麻將] 

#### Game Play
* 3 or 4 player **draw-and-discard game** with 144 tiles based on Chinese characters and symbols.
* Match open pairs of identical tiles, remove from board, exposing the tiles under them for play. 
* Game ends when all pairs of tiles have been removed from the board or no more exposed pairs remaining.


#### Types [Make Configurable]
* Old Hong Kong/ Cantonese Mahjong [DEFAULT MODE :)]
* Competitive Mahjong International Standard
* Three-Player Mahjong [3-ka]
* Battle Mahjong [Player vs Cartoon NPC]


#### Game Tile Count Per Set [Total 144]
* **Simples** [108]
    * Dots 36
    * Bamboo 36
    * Characters 36
* **Honors** [28]
    * Winds - [North West South East] 16
    * Dragons - [Red Green White] 12
* **Bonus** [8]
    * Flower - [Plum Blossom, Orchid, Chrysanthemum, Bamboo] 4
    * Seasons - [Spring, Summer, Autumn, Winter] 4


#### Mahjong Combos 
* Heavenly Hand [天糊]
* Great Winds [大四喜]
* Great Dragons [大三元]
* All Kongs [十八羅漢]
* All Honor Tiles [字一色]
* Thirteen Orphans [十三幺]
* Nine Gates Hand [九蓮宝燈]
* Self Triplets [四暗刻]
* All in Triplets [對對糊]
* Mixed One Suit [混一色]
* All One Suit [清一色]
* Common Hand [平糊]
* Small Dragons [小三元]
* Small Winds [小四喜]



## Technical Mahjong Game Documentation

#### Deep Learning
* **ML Algorithms** allows game to react and respond more **dynamically and in more imaginative ways**. 
* Players get more realistic experiences and playable content in a game that involves skill, strategy, calculation, and chance.
* **Deep Neural Network** with reinforcement learning implemented. 
* Learn from its own game and top human players (via Classic Supervised Learning) where computations are made for every move or position.


#### Machine Learning  
* Non-Player Characters (NPCs)
   * Algorithms playing as NPCs (with adjustable difficulties) respond to player’s actions in unique, unexpected ways. 
   * NPCs are non hard-coded. 
   * Train NPCs by **imitating Top Mahjong Players** to learn dynamic movements and actions.
   * **Natural Language Processing [NLP]** to build realistic interactions in conversations. Key for Battle Mahjong [Player vs Cartoon NPC] style. 

* Computational Modelling 
   * Complex game states modelled such that game can predict and alter downstream effects:
   * Ex1: **Team chemistry score calculated** based on personalities of each gamer. 
   * Ex2: Morale of each player’s abilities as game is played in real-time.
   
* Game Aesthetics
   * Ex: **Computer Vision Algorithms** used for mahjong textures and objects to **render dynamically** as player moves tiles on the board.


#### Deep Learning 
* DL Game Play
   * **AI will win through intelligence** rather than faster mechanicals speed.
   * Computers can programatically issue commands instantly whereas humans must physically move a mouse or hit the keyboard. *    * Specifically, humans average 300 actions per minute.
   * Knowledge based hierarchy foundation with **Goals, Strategies, Tactics, and Chains**. 
   * Each objective inspects current game state and decides which lower level objective will be best to achieve it. 
   
* Deep Neural Network
   * 3 **Hidden layers** of 120 neutrons.
   * 3 **Dropout layers** to optimize generalization and reduce over-fitting.
      * Input - State
      * Output - Values related to Mahjong Actions
   * Last layer uses **Softmax Function** to return probabilities.
   
* Reinforcement Learning
   * **Markov Decision** process to make decisions involving chain of if-then statements. 
   * **Positive or Negative Reward**. 
   * Algorithm will learn what actions will maximize the reward and which to be avoided.
   
* Deep Q-Learning
   * Q-table matrix that updates Q-table based on the **Prediction of Future Mahjong States**.
   * Q-values updated according to the **Bellman Equation**.
   

#### Search Gaming Optomization Algorithm
* **Alpha-Beta Prunning**
   * AI weeds out bad moves.
* **“Lookahead” Search Algorithms**
* Open World Games 
   * Typically require thousands of hours of developer and artist time to render.
   * Become more efficient using **ML Path-Finding Algorithms**.
   * Have the potential to be unlimited in size.


#### Database
* Optimize game data with databases.
* **Pre-Computed Moves** for the beginning/end phrases of the game.
* Two Databases
   * Opening DB
   * Endgame DB 


#### Technical Tools
* React Native [JS Framework]
   * Bootstrap React Native app on any OS with no build config- https://github.com/react-community/create-react-native-app
   * iOS Moble
   * Android Mobile
* Flask [Python]
   * Flask Framework
   * Flask-SocketIO
* Keras on top of Tensorflow


## References - Books
* Rules of Mah-Jongg - Joseph Park Babcock
* Maajh: The American Version of the Ancient Chinese Game - Viola L. Cecil
* The Complete Book of Mah-jongg - Alan D. Millington

###### For my grandma :)





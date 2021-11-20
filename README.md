# Hasaki
Report of project ‘Hasaki’
## Problem domain & studio context

The problem space for our team is “Ability-centric Interactions.” In this domain, we need to create some interactions from an ability-specific point-of-view. It should be aimed at some particular users. And the interaction designed should be specific to a particular ability at the same time. Therefore, we specify the problem as to what kind of ability is special for that particular group, and what interactions we can design to enhance or utilize that ability.

After related research and brainstorming, we propose designing a hearing and shooting game for the visually impaired people. To help them improve hearing ability in an innovative way. Since hearing ability, as one of the most essential ability for them to feel the world, greatly determines their quality of life, we were lucky to find that this ability can be improved through training, especially the sound source localization ability. Besides, we found that the amount and type of current games for the visually impaired are limited. Based on these, we chose to develop a new hearing and shooting game experience that the users have to listen to and judge where the sound comes from and shoot towards that direction.


## Background research

### Accessibility can be improved by using voice control
We discussed any feasibility of how to facilitate the use of our equipment by the visually impaired. This reminds me of Apple's content about accessibility at the WWDC conference last year. Apple develops some assistive features to give this user group greater control over their lives. These features can help them to control their devices just using their voice. [1] It means that users do not need to purchase any additional equipment to use this feature. 

Based on this principle,  the terminal of voice control is a smartphone ( iOS or Android) in our project. Then we stored some related voice commands,' start' and 'end', to the phone. Also, users can choose to adjust the content of voice commands according to their habits. We use the Bluetooth module as a bridge to connect the mobile phone and the device. The commands received by the mobile phone can be transmitted to the device via Bluetooth to complete a series of operations. This will significantly facilitate the use of our equipment by the visually impaired.

### Hearing ability can be improved through training
The primary purpose of our project is to improve the hearing ability of visually-impaired people through the game. Therefore we first need a theoretical basis to support that hearing can be improved by training for the visually-impaired people and then find out how to train it.

Usually, blind people can develop more impressive hearing skills than the sighted people, one of the most important reasons is that they have to rely more on hearing ability so that this sense can be concentrated and used more. [2] They rely more on hearing to help them navigate through sound source localization ability. L. Dunal et al. [3]Conducted experiments with blind people and found out that they can easily perceive localized sounds, as well as their performance, can be improved after training. It’s worth mentioning that, in the experiments, authors used sounds in a different distance, location, and environment, which provided great inspiration for the settings in our project. Therefore, in our project, we located sound sources in different directions to improve localized hearing and spatial hearing, besides we increased the game difficulty by adding environmental interference sounds.

### Vivid storyline can enhance the player's gaming experience
For the game storyline, it is undeniable that a good storyline has a huge positive effect on the player's game experience. When the story appears, players will feel more sense of identity, presence and arousal. [4] Therefore, if we add a reasonable game plot to the game, it can help to increase the player's participation in the game, immerse him/her in the game environment and constantly motivate them in order to make the game more playable.

Furthermore, the interactive storyline as a new form of storytelling can also bring an impressive game experience for players. In this interactive story, players change from previous story recipients to active co-creators. [5] This interactive story will greatly enhance the user's participation in the game. Moreover, different choices of players may cause different story endings, which provides an unexpected ending for the player and also fills the game with more suspense, thereby stimulating the player's interest in the game.

Additionally, the storyline, game characters and enemy settings in the game should also be moderate and varied. According to the findings of 000, the change of the storyline, missions and enemies is helpful to enhance the game experience. [6] Therefore, when designing game levels and story lines, using multiple enemy types or game scenes has also become a focus of our game development.

### 3D surrounds music could improve game engagement, realism, and enjoyment
Despite the differences in game design and appearance, most successful games have an important common denominator - the ability to attract players.This kind of experience is called “immersion” [7]. According to the research conducted by Laura Ermi and Frans Mäyrä, powerful sounds can easily overshadow sensory information from the real world, while players are completely focused on the excitement brought by the gaming world [8]. Due to the potential user group which is the visually impaired, sound will be one of the breakthroughs in developing the game. So, in our project, developing 3D surround sound as our game sound effect will greatly enhance the user's sensory experience in the game. 

In order to create realistic sound effects. We chose Adobe Audition to create the 3D surround music. The method is to add multiple sound clips, such as rain, zombies, thunder, on a main audio track, and then add a variety of anchor points on the audio tracks to adjust the pan and the volume to simulate the sound effects of 3D surround sound.[9]

In the game, we use different ambient sounds to distinguish the different levels of the game. For example, In level 1, there are only sounds of zombies, and users can clearly distinguish their direction. However, for level 2, we added the sound of rain and thunder, which will make it more challenging to identify the direction of the zombie.

# Findings & Insights for others

## Through our user research and multiple tests during the game development process, we have made some discoveries about improving the game experience of the project. 

1. For special target groups, we should fully consider their convenience in using the game. For our project, our target people are mainly visually impaired, so we have added voice prompts and voice control functions for the game and set up safe areas for the game based on user feedback throughout the game development process. Considering that there is no user interface in the game, the entire game relies entirely on sound to interact, we designed voice prompts which guide players on how to play the game and voice control for players to control the start and end of the game. For security reasons, we deleted the sound from the back of the original conceptual design. This is because, during the test, we found that if the user turned back to respond to the sound of the back when the user was blindfolded, it was easy to get lost. Besides, in order to remind users to move within a safe range, we have also added a safety alarm function. The above are the adjustments we made for the game interaction of our special user groups.

2. Adding a variety of physiological feedback to the game design helps improve the player's participation and integration of the game. In our original concept, we only included sound interaction and situational interaction. But in the actual prototype test, we collected some valuable feedback which mentioned the content of haptic feedback. Therefore, in the second prototype, we added vibration feedback to the pistol, that is, pressing the trigger of the gun will trigger the vibration of the gun, and releasing the trigger will stop the vibration. This allows the user to receive feedback information tactilely at the same time through voice prompts, which helps players to understand their operations more clearly when playing the game.

3. he combination of deliberate training and game storyline can better help players achieve the training effect. According to our problem domain, our goal is to train the listening abilities and sensitivity of target users. Therefore, in the process of game design, adding sounds commonly used in life will subtly improve their listening ability while players enjoy the game. In our project, we not only set the difficulty of the game according to the frequency of enemy attacks but also added the sound of wind, rain and thunder. The use of these everyday sounds in life is to improve their ability to distinguish essential sounds in life so that they can improve their hearing ability in real life while playing games.

# Team reflection ### 

## We are all satisfied with the final project product, and highly pleased the cooperation of teamwork under the restrictions of the pandemic this semester. Through a semester of cooperation, we have summarized some points to ensure the teamwork can be performed efficiently and harmoniously.

### Group Formation
This is the initial stage of teamwork, and the guarantee of effectiveness. We think each team member needs to have one aspect of his own strengths, and at the same time all the abilities can cover the needs of the project. It can be more reasonable and easier when it comes to works allocating as well. Besides, we have to say since all the members are Chinese, therefore many misunderstandings or inconveniences caused by communication were avoided.

### Break down the project
At some point in the beginning, we had no idea about how to carry on the project specifically until we learned how to break down the project. It’s important to do adequate research before, and then a detailed decomposition can lead to clear actions. 

### Assign work
It will be clear about how to assign work when we understand the skills every is good at and a detailed work schedule from project breaking down. We also realized the importance of setting deadlines for each work. Each member needs to communicate timely to ensure everyone’s working on the right way, and has to supervise others’ progress.

### Application of software
Affected by the epidemic, most of the work’s done online. Reasonable use of communications software can improve work efficiency. Since different software has its unique features, and we had various needs in each meeting. For example, Miro is good for breaking down project, Discord can be used for work display and basic communications, Google Doc is perfect for sharing and editing words together, and Github is the best tool for sharing codes.

### Reference

[1]    "Accessibility Support - Official Apple Support", Support.apple.com, 2020. [Online]. Available: https://support.apple.com/en-au/accessibility. [Accessed: 11- Jun- 2020].

[2]     L. Thaler, S.R. Arnott, M.A. Goodale. Neural correlates of natural human echolocation in early and late blind echolocation experts. PLoS One, 6(2011), p. e20162
[3]     D.  Larisa, L. Ismael. P. Fajarnes, Guillermo, B. Fermando:  Virtual Sound Localization by Blind People, Archives of Acoustics, 2015, Vol. 40(4), pp.561-567
[4]	E. F. Schneider, A. Lang, M. Shin, and S. D. Bradley, "Death with a story: How story impacts emotional, motivational, and physiological responses to first-person shooter video games," Human communication research, vol. 30, no. 3, pp. 361-375, 2004.

[5]	J. Laaksolahti, "Plot, spectacle, and experience: contributions to the design and evaluation of interactive storytelling," Institutionen för data-och systemvetenskap (tills m KTH), 2008. 

[6]	Y. L. Prasetio, R. Wijaya, M. P. Sjah, M. R. Christian, and A. Chowanda, "Location-based game to enhance player’s experience in survival horror game,” Procedia computer science, vol. 116, pp. 206-213, 2017.

[7]	C. Jennett et al., "Measuring and defining the experience of immersion in games," International journal of human-computer studies, vol. 66, no. 9, pp. 641-661, 2008.

[8]	L. Ermi and F. Mäyrä, "Fundamental components of the gameplay experience: Analysing immersion," Worlds in play: International perspectives on digital games research, vol. 37, no. 2, pp. 37-53, 2005.


[9]	"How to Create 5.1 Surround Sound Audio in Adobe Audition", Ambisonics - VR-Audio, 2020. [Online].Available:https://ambisonics.de/ambisonics-mastering-vr-audio-mastering-berlin/how-to-create-5-1-surround-sound-audio-in-adobe-audition. [Accessed: 11- Jun- 2020].

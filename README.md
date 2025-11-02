I received my M.S. in Computer Science specializing in Machine Learning from the Georgia Institute of Technology. I graduated with highest honors from Georgia Tech in December 2023 with a B.S. in Computer Science concentrating in Intelligence and Information Internetworks.

I've been interested in computer vision and its applications. I developed a tool in Python that can automatically create football playcards given the video of a football play. Additionally, I am currently involved in research at the Margulies Injury Biomechanics Laboratory at Emory University where we use convolutional neural networks to detect blood-brain barrier leakages after brain injury. 

Professionally, I spent two summers interning at Capital One building applications for internal use. I also spent a summer interning at CDK Global where I helped move their main application to a CI/CD pipeline by hosting the application on Docker containers. I also completed a project for research with Tufts Medical Center where I built a web application that allowed cardiologists to evaluate patient images to see if a type of cardiac disorder could be predicted. I now work at Capital One full-time as a full-stack engineer.

# Notable Projects

## [Football 3D Reconstruction](https://pranav-datta.github.io/Football-3D-Reconstruction/)

![Football play with bounding boxes around each player](/images/football.png)

We developed a method for reconstructing football plays in the Unity game engine so that the play could be viewed from any angle. We used a neural network trained on football players to find player positions and created a novel tracking algorithm to record each player's position on every frame of the video. For the homography of these positions to our virtual field, we used blob detection and Hough Line Transform to detect interest points on the field. In future iterations of this project, we can use pose estimation so that the animations of the reconstructed players are accurate to the movements of the players in the video. This project also demonstrates aspects of my football playcard tool.

## [ManipuLang](https://github.com/pranav-datta/ManipuLang/blob/main/ManipuLang%20Project%20Report.pdf)

![Removal pipeline](/images/removal.png)

Rendering and editing real environments virtually typically involve advanced software that requires expert users. Methods such as Gaussian Splatting have simplified the conversion of real-world images to 3D virtual scenes, but current processes of editing these scenes involve manual specification of tasks, identification of objects, and localization of interest regions (in the form of bounding boxes) for addition tasks. Therefore, modifying 3D scenes using open-vocabulary queries is an open problem. We propose a solution called ManipuLang, which integrates LLMs (GPT-4o and LLaVA-3D) for interpreting arbitrary language prompts for task and object identification. It then uses GroundedSAM to localize the object and removes the associated Gaussians in the scene. We also explored options for performing addition into the scene. We hope this offers an avenue for easily and accessibly manipulating 3D environments generated from real-world images.

## [Music Recommender](https://github.com/pranav-datta/Music-Recommender/blob/main/Final_Report.pdf)

![Spectrogram of song](/images/music.png)

In this study, we compared seven different deep learning models and their ability to predict a song's genre based on its raw audio converted to spectrograms. The idea was that if a model could perform well in this task, then the model may be adopted for music recommendation systems due to its success in classifying similar songs. In this process, we created a new type of neural network architecture called a 1D Convolutional Encoder which borrows from the strengths of 1D CNNs and Encoders. With this architecture, we achieved 70% accuracy in the music genre classification task.

## [NBA Game Predictor](https://pranav-datta.github.io/NBA-Game-Predictor/final.html)

![Visualization of machine learning model output](/images/nba.png)

The goal of this project was to see if machine learning could predict the winner of any NBA matchup using each team's statistics over the previous ten games. We used linear regression, logistic regression, support vector machines, and PCA for this task. Our best approach was able to achieve 84% accuracy. Performing feature reduction gave us insights into the most important statistics in predicting the outcomes of NBA games, which interestingly were different for each decade of the NBA's history. 

# Other Projects

## [iPhone Sensor Recorder](https://github.com/pranav-datta/iPhone-Sensor-Recorder)

iOS application to record and save data from iPhone's accelerometer and gyroscope.

## [Basketball Fatigue Study](https://github.com/pranav-datta/Basketball-Fatigue-Study/blob/main/Project%20Report.pdf)

Study to measure the effect of fatigue on the lower body during basketball shooting using accelerometer, EMG, ECG, and PZT respiration. Signal processing done on Python.

## [Chat Room](https://github.com/pranav-datta/ChatRoom)

A simple local chat room on Python using sockets and threading.

## [Peer 2 Peer File Sharing](https://github.com/pranav-datta/Peer2Peer)

A simple local Peer 2 Peer file sharing application on Python.

## [Meal Planner](https://github.com/pranav-datta/Meal-Planner)

Meal planner database application using MySQL.

## [World's Hardest Easiest GBA Game](https://github.com/pranav-datta/GBAgame)

Simple Gameboy Advanced game that mimics The World Hardest Game.

## [Tower Defense Game](https://github.com/pranav-datta/TowerDefenseGame)

Simple game inspired by Bloons Tower Defense in Java.

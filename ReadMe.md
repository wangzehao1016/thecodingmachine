My Internship at TheCodingMachine HK
===

Background:
---
- No develop experience with react native 
- Had a lesson to study reactjs
- Had a lesson to study php
- And some knowledge with the database management
- Relatively slow typing speed
- Experience with Git on windows instead of Mac

Material Preparation:
---
- If not working fine at touchpad, prepare a good mouse since you are working on two screens
- Try best to get used to french keyboard, I usually need a week to avoid most of the typo. If not confident with the keyboard, you can buy an English one.

Main Development Tools:
---
- Docker
  - The tool that control the version of every other tools used in the development. It will create a virtual container for the application upon every time it runs. It doesn't works fine with
  
- React-native-boilerplate
  - I was informed to practice with it before the internship. It should be noticed that the project use yarn instead of npm. The rest of the instructions can refer: 
  https://github.com/thecodingmachine/react-native-boilerplate
  - there is one thing to notice that, the boilerplate is recommended to run on the Android machine Version 9.0. Set up the device accordingly
 
- Mouf php
  - setting up the database with interface on the browser and can make the database establishment visualised.
  - ( further details will be added later when I attend the backend development )
  
About the Working Environment & Projects:
---
  I attend the project __Sotopia__ . It is the first time I was involved in the real development into business use and I push myself hard. It is relaxing to work in an office locating at the high tower with nice view of sunshine and sea, and they gives me the effort to try new things.

  Jindun spent half a day to help me with the set up of the environment to let sotopia run on the virtual device. There are several comands that need to be remembered at the react native frontend that will be frequently used once you switch for another branch for test or development
  
  First thing, remember to set the Program_name/sources/app as the root to start the work.
  
  ` yarn install ` is the command that build all the package included in the __package.json__. In case any branch included a new package in the program, do it first before running. No need to run for a second time if the package list remains unchange.
  
  ` react-native link ` is the command to link the library. It should be done along with yarn install.
  
  You can see that the packages mentioned in the package.json is already installed under the directory node_modules outside your app deirectory, which is why the package won't be updated unless you do yarn install, and it certainly avoid holding too much space with all the installed package on git, which will derive the result of slow push and pull.
  
  ` react-native run-android ` or ` react-native run-ios ` is to launch or relaunch the program on android or ios. Note that:
  - one program can only run on one machine. One machine can only hold one running program. Make sure to manage the relaunch and ^C correctly to avoid conjestion.
  
  




# seniorProjectNotebook19-20
## Tyler Kaschner,  Christopher Smagacz, Advisor: Dr. Suruz Miah


Notebook for senior project (2019-2020)



Kickoff meeting (Date: 9/13/2019)
---

Meeting minutes
Set up Github site and notebook
9:00-11:00 1:30-2:30 Tuesdays and Thurdsays lab time each week
Lab time is used for coding and hardware work.
We will share work equally.
Dr Miah will help us install Latex and IPE extensible drawing editor outside of formal meeting.
5 members in research group we can collaborate to learn latex.
research meeting every other friday from 12 to 1
Bibtech need to download for bibliography
For report template it will all be in latex
Dr Miah created a google drive folder for us with referenceable material.
Google drive is where bibliography, referenceable documents, and project documents
Our goal for this semester is to code the previous years projects, then next semester add our own elements

Action: Read Previous years final report from page 1 to pg 37 then prepare a presention based on that and appendix e pg 71 to 74 present on those pages as well. The presentation will be a 30 minute presentation.

(Date 9/15/2019)
---
Tyler took notes on pages 1-10 of previous years report

(Date 9/17/19) Tuesday Lab
---
Christopher and tyler worked on understanding last years project progress while working on setting up presentation for 9/20/19 senior project meeting.

(Date 9/19/20) Thursday Lab
---
Christopher and tyler spent half of lab time adding slides to the presentation for 9/20/19 and the other half of the lab finalizing resumes for the job fair taking place that current day.

(Date: 9/20/2019 @ 3:30 PM) Weekly Meeting
---
Tyler and Christopher presented there presentation today.
Dr. Miah shared with us previous years project documentation we are unable to download, delete, or copy an files only allowed to view.
The Things to do before next meeting:
Complete project statement in latex on overleaf,
we need to read areo user manual, and  
look into areo lab guide and implement experiment 4.
we left the meeting at 4:32 Pm

[Overleaf v2 tutorial1](https://www.youtube.com/watch?v=rLWT0z6yvrk)

[Overleaf v2 tutorial2](https://www.youtube.com/watch?v=JwXQb25cpqA)

(Date: 9/23/2019 )
---
Tyler and Chris read the user manual for the helecopters to perpare for working on lab 4 tommmrow.
We plan on working on the project proposal after we implement lab 4.

(Date: 9/24/19) Thursday Lab
---
Christopher and tyler both worked to get the simulink models needed for lab 4 done. We got the models 80% done the last thing we need to add is the Helecopter module's. We were unable to find out where they are located during the lab time. We left the lab around 10:50 am.

(Date: 9/25/19) Weekly Meeting
---
Tyler and Christopher have agreed to finish the project proposal today so that Dr. Miah has time to give us feedback. We finished at 6:31pm and are going to send it to Dr.Miah

(Date: 10/1/19) Tuesday Lab
---
During our lab time we designed our simulink diagram based on the reference file s_aero_2dof_lqr_control. We were slowed down by issues surrounding the installed Quarc files. The Quarc modules we needed to complete the s_aero_2dof_lqr_control model were not found in the current version of simulink we were working with, which was 2018.

![snip5](https://user-images.githubusercontent.com/48564969/66240967-88d23700-e6c3-11e9-8941-350aa78b5022.PNG)


The Drawing shown above shows our Simulink drawing s_aero_2dof_lqr_control model. We are using this drawing to find the control gain value K in our matlab script.
Figure 1

(Date: 10/3/19) Thursday Lab
---
During this lab time we edited and fixed our previously mentioned simulink diagram and we solved this issue by making all necessary edits in Matlab 2017a which has the Quarc software we needed to finish our drawings.

![snip6](https://user-images.githubusercontent.com/55299289/66241113-e8304700-e6c3-11e9-9729-a122336f19b8.PNG)
---
The Drawing shown above shows our simulink drawing named q_aero_2dof_lqr_control and it is used to enable the USB interface for us to connect to the Quanser Aero.
Figure 2

![snip1](https://user-images.githubusercontent.com/55299289/66241103-e23a6600-e6c3-11e9-87ed-7d812985fc70.PNG)
---
The Figure shown above shows the pitch position as the control system runs and how it changes pitch when in use.
Figure 3

![snip2](https://user-images.githubusercontent.com/55299289/66241100-e1a1cf80-e6c3-11e9-8e88-448ef9b7a156.PNG)
---
The Figure shown aboves shows the yaw position as the control system runs and how it changes when in use.
Figure 4

![snip3](https://user-images.githubusercontent.com/55299289/66241101-e1a1cf80-e6c3-11e9-9f5d-0f85874a156c.PNG)
---
The Figure shown above shows the voltage applied to the yaw motor as the simulink model runs and how the voltage needs to be applied.
Figure 5

![snip4](https://user-images.githubusercontent.com/55299289/66241102-e23a6600-e6c3-11e9-9b1c-6cf51addada0.PNG)

The Figure show above shows the voltage applied to the pitch motor as the simulink model runs and how the voltage is applied to the pitch motor in a live system.
Figure 6

(Date: 10/3/2019) Thursday Lab
---

After we finished the first simulink model and got it fully functional we began the secound simulink model based on the file q_aero_2dof_lqr_control. We got this similink model around 85% complete the last part we need to add is the Quarc mdoelules which we have not been able to find yet. 

(Date: 10/8/2019) Tuesday Lab
---
Today we worked on getting the State feedback Control Simulink model named q_aero_2dof_lqr_control we weren't ultimately able to get the simulink model to connect to the connected Quanser Aero, we believe the problem to be that in our current version of matlab we cannot open an older reference file's subsystem which has an integral part to connecting to the quanser aero, we talked with Dr. Miah and discuessed the possibility of emailing the previous year's senior project group that worked on this project to try and resolve this issue.

(Date: 10/9/2019) Weekly Meeting
---
In this meeting we discussed the trouble we ran into trying to get the state feedback lqr control and how we should remedy the situation. Dr. Miah told us to ultimately email the previous years group to ask for their assistance to find the source code we need to get previously mentioned lab functioning. Dr. Miah also asked us to look into the Quarc Quick Start Guide and get that functioning in tommorows lab instead of continuing to waste time on the current lab.

(Date: 10/10/2019) Thursday Lab
---
Today we completed the Quarc Quick Start Guide and managed to get the 2-dof helicopters moving and in the video labeled as 20191010_102427_1[1].mp4 we demonstrate the movement of the helicopters. The video is attached to the project above.
<video src="20191010_102427_1[1].mp4" width="320" height="200" controls preload></video>


(Date: 10/16/2019) Weekly Meeting
---
We first went over any progress we got done over break which was adding to the github descriptions of the screenshots we got from the simulink models. Dr. Miah wants us to work on fixing our Mathematical Model of 2-DOF helicopter document as soon as possible. Our task for our next lab time is to implemient the state feedback control lab and get the helicopters moving agian. 

(Date: 10/17/2019) Thursday Lab
---
Today we finally got the simulink model of state feedback control of 2-DOF LQR lab functioning and managed to get video of the Quanser Aero changing pitch and yaw at desired increments functioning in a live environment. We managed to get this done after the previous year's senior project group responded to our email telling us where a very helpful file was located.

(Date: 10/22/2019) Tuesday Lab
---
Today we worked on remaking the state feedback control of 2-DOF Helicopters using the LQR algorithm simulink model with our own parameters in place to better understand the USB interface connecting the computer to the Aero. We ran into some simulation and build errors slowing our progress and had to remedy those which took up most of our lab time unfortunately.

(Date: 10/23/2019) Weekly Meeting
---
We first discussed our progress from last week, which was mostly additions to our project report. We then discussed our plan for our lab time this week, Dr Miah wants us in lab to create the State feedback Control simulink model from scratch without copying any modules from previous referencable material. Dr Miah also wants us to add him to our finalized project report that is due on 10/24/2019 at 11:55 PM.

(Date: 10/24/2019) Thursday Lab
---
Today Tyler coded the simulink model named q_aero_2dof_lqr_control from scratch doing what Dr. Miah asked of us in the previous meeting. We also edited the gain and saturation parameters in the simulink model to alter the Aero's movement to better understand the way the device operates. In a meeting with Dr. Miah we discussed our learning goals moving forward and he mentioned that he wants us to ultimately re-code this lab from scratch without looking at old referenceable material. 

(Date: 10/31/19) Weekly Meeting
----
Today Dr. Miah had us meet in the lab. We first talked about our progress on understanding the stateFeedbackControl Simulink model. After Dr. Miah on a piece of paper went of some more math with us we learned about the desired state vector's. The Desired state vectors are made up of the pitch and yaw at desried point of the user along with the pitch and yaw rate of change being zero. We also learned more about the Overall Cost Function that includes both voltage and error calculations. The two important variables included in this equation is Q and R, Q coresponds to error while R is voltage. When making the Q bigger and the R value small we are able to get the best performance for the helicopter having the ammount of voltage used not take priority. If the R value was made bigger while the Q value is small the opposite effect will take place. The helicopter would attempt to get to the desired location using the least ammount of voltage it can not taking into account the performance in the process. Me and tyler showed Dr. Miah our files and simulink modles, Dr. Miah has requested us to work on organization after our meeting he did not like how unorganized our files were but did enjoy the progress we had made on operating the helicopter. Currently We have an overshoot problem in our code and this is our main problem to fix before we make more progress.


(Date: 11/20/19) Weekly Meeting
---

(Date: 11/21/19) Thursday Lab
---

(Date: 11/26/19) Tuesday Lab
---
Today Tyler and Christopher worked on having the LQI_USB_implementation simulink model run properly. We needed to change the Gain peramerters so that it could run correctly with out code. we had to take out the signal generators that we originally had in the model from last week on thursday. We wanted to see if we could change the gain block to a number and have the helicopter move to the desired state. If we could do this then adding the signal generators in later wont be to much of a hasle. After some time we were succesful on being able to run the model properly and change the angles to the desired states we entered. 

Kickoff meeting (Date: 1/24/2020)
---
This was the first meeting of the new semester. The objective of this meet was to set up the weekly meeting time that would be best for everyone as well as decide the 2 weekly lab times. Dr.Miah was happy with our work from last semester and spent some time giving us feedback to improve our work for this semester. We need to work on better organizing our docmentation for the lab work we do and keep the github update the github as much as possible. The next weekly meeting Dr.Miah has asked us to prepare a recap of what was done last semester and our plans for the lab work that will be done in the upcomming weeks. 

(Date: 1/28/20) Tuesday Lab
---
This is our first offical lab meeting for this spring semester. We meet in the senior project lab at 1:00 pm. We had discovered that our quanser areo PC's had not been set up yet. We had ran into Christopher Mattus on the way to lab and he was busy with some people so we decided to give him some time before asking him about an update on the setup of our quanser areo PC's. After about 45 minutes we went to his office and asked him politly for an update on the progress of setting up our PC's. He had told us that he hasnt started yet but could set them up right now during our lab time. For the rest of the lab Christopher, Tyler and Christopher Smagacz worked on setting up two benches in the senior project lab that would be the stations we will using for our senior project this spring semester.

(Date: 1/30/20) Thursday Lab 
---
Christopher and Tyler meet in the senior project lab at 1:00 PM. We had our quanser areo PC's set up from last lab time so we were able to get started on our raspberry pie implementation. Before we got to work on the implementation we had to recive both the SD card we will be using and the raspberry pie from our senior project advisor Dr. Miah. After this was done we went back to senior project lab and worked on getting an operating system installed onto the SD card. The first problem we ran into is making sure were are attempting to download the correct operating system. We sent an email to ken and glen asking what operating system would be best with this project but havent recived an email back. We did some reasearch on our own and found an operating system that we feel comfortable with and flashed it to the raspberry pie.

(Date: 2/4/20) Tuesday Lab
---
Christopher and Tyler meet in the senior project lab at 1:00 PM. Last lab we had accomplished flashing our Raspberry Pi 3 with an operating system. So we continued to work on raspberry pie implementation but we are missing a cable that will allow us to trasnfer data to the raspberry pie. We went around the ECE deparment asking professors and searching labs to see if we could find a cable that could satify this problem but we were unsuccesful. With this we had not be able to make progress on reimplementing the Raspberry Pi part of the last years senior project. Christopher and Tyler spent the rest of the senior project lab doing research into app design and the types of modules that will have to be used when interfacing the Quanser Aero with our Raspberry Pi.

(Date: 2/6/20) Thursday Lab
---
Christopher and Tyler met in the senior project lab at 1:00 PM. Today we started working on the previous years Raspberry Pi implementation. We ultimately started setting up the Raspberry Pi O.S (operating system) Raspbian. We enabled serial connectivity if we wished to complete the previous year's Raspberry Pi implementation. However we ultimately decided that the course of action we will take to complete our version of the Raspberry Pi will follow the procedure layed out by the group that completed this project two years ago. The reason we chose to use the 2018 Raspberry Pi implementation guide is because the way we wish to connect in our lab is through ethernet based IP addressing. Since our project will ultimately be implemented on a smart phone it is only logical to approach the Raspberry Pi implementation from the I.P based approach.

(Date: 2/11/20) Tuesday Lab
---
Christopher and Tyler met in the senior project lab at 1:00 PM. Today we continued working on the preivous year's Raspberry Pi implementation. We made a big leap forward in this lab and got the putty based interfacing functional between the desktop and our Raspberry Pi. Next we will work on getting the necessary matlab files uploaded to the Quanser Aero. We also encountered a small problem. The problem we encountered is that in order to connect to the Raspberry Pi through SSH in putty we have to have the desktop and the Raspberry Pi connected through an ethernet cord. The reason this is a problem is because neither my laptop or Christophers has a built in ethernet port. A reasonable step forward following this hurdle is to purchase a USB to Ethernet extenstion cord. This way we use our laptops and use the work station provided for us in the Senior Lab.

(Date: 2/13/20) Thursday Lab
---
Christopher and Tyler met in the senior project lab at 1:00 PM. We are still working on the Raspberry Pi implementation and being able to have our matlab simulink models on the Raspberry pi. We have been looking at the errors we have been encoutering when running the program on matlab and have realized we need to install a couple of packages onto the raspberry pi. The first one is a C cross complier so that our Raspberry Pi can read our code. We also need to download Cmake so that we can have support files for make files that are writen in C. We believe we have been able to download the correct files for this but right now we have to test them. Most of lab time was spent looking online for the correct download and executing it on the raspberry pi. At the end of lab we still ran into the same errors on the computer.

(Week of Febuary 16th - 22nd)
---
We decided to make this weeks lab work apart of the same update. We spent both lab days working on the same situation. The raspberry pi Christopher and tyler were working on was still having trouble being able to run the code from matlab. The new error we began to run into was print_cmd.c we used a lot of time doing some google research on the error to try and find a solution but we came up short due to this error being outdated since we are running on matlab 2017.

![error_mail](https://user-images.githubusercontent.com/55299289/75483475-891de800-596c-11ea-8770-c2baec233b26.PNG)

The error is caused by attempting to run the program on the desktop we used for USB implementation. We got around this problem by realizing that we dont need to run this program on the desktop becasuse our objective is to run the program on the raspberry pi. Our senior project advisor Dr. Miah showed up to lab to help us with some of our problems. Dr. Miah informed us we should wrok with the Raspberry Pi that the previous years senior project group used because it should already have an operating system and the nessasary support packages we need to run the simulink models. We switched out the Raspberry Pi we currently have with one of the pervious years and began working on trying to resolve more of our errors. We began to run into building errors due to the configuration perameters on the program from the previous years not being correct.

(Date: 3/26/2020) Video Chat Test Meeting
---
Today myself, Christopher, Dr Miah, and the previous year's senior project students had a meeting on a remote video chat software to discuss the path of the senior project going forward with the current state of the countries health. Some new goals were set during this meeting time including the new ways we are going to continue the senior capstone project. We will be looking into applying and simulating the optimal control algorithms known as Linear Quadratic Gaussian control scheme,as well as the neural network based ADP control algorithm. During this meeting we also set new weekly meeting times on the video chat program.



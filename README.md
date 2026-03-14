## Teamcity homework ##  
During pre tasks created VMs with dockerized services Teamcity server and Teamcity agent.  
Initialized new teamcity server.  
Authorized new agent in Tamecity server.  
Additionally created VM with Fedora 37 for Nexus and deployed nexus on it.  
Made a fork of given exaple project.  
### Steps 1-3 ###  
Created homework project.  
Autodetected config as Maven.  
Made first build for master.  
### Steps 4-7 ###  
Added condition for Build step for master and changed goals to clean deploy.  
![Build1](build1.jpg)  
Created copy of Build step. Changed golas to clean test and added condition to ignore master branch.     
![Build2](build2.jpg)  
Ran the Build steps and checked for changes in Nexus  
![nexus1](nexus1.jpg)  
### Step 8 ###  
Configured build configuration export to github repo  
![Build2vcs](build2vcs.png)  
### Step 9 ###  
Added feature/add_replay 
### Steps 10-13 ###  
Added new method sayHunter  
Added test for replay with hunter  
Ran build successfully  
![Build3](build3.jpg)  
### Steps 14-15 ###  
Merged changes from add_replay to master  
Ran build successfully  
![build4](build4.jpg)  
No artifacts after build  
### Step 16 ###  
Made changes to build configuration to create .jar  
![build5](build5.jpg)  
### Step 17 ###  


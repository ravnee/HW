# Introduction Sequence
##Level 1
 *git commit*  
 *git commit*

##Level 2
 *git branch bugFix*  
 *git checkout bugFix*

##Level 3
 *git branch bugFix*  
 *git checkout bugFix*  
 *git commit*  
 *git checkout master*  
 *git commit*  
 *git merge bugFix*  

##Level 4
 *git branch bugFix*  
 *git checkout bugFix*  
 *git commit*  
 *git checkout master*  
 *git commit*  
 *git checkout bugFix*  
 *git rebase master*  

# Ramping Up
##Level 1
 *git checkout bugFix*  
 *git checkout C4*  
##Level 2
 *git checkout bugFix^*  
##Level 3
 *git branch -f master C6*  
 *git branch -f bugFix HEAD~2*  
 *git checkout HEAD^*  
##Level 4
 *git checkout pushed*  
 *git revert C2*  
 *git checkout local*  
 *git reset master*  
 
# Git Hub Levels Snapshot
![levels](https://cloud.githubusercontent.com/assets/8634231/9722703/1e066f82-5580-11e5-9c0c-858df50b9f65.PNG)

# post-commit content


    #!/bin/sh  
    echo "start post-commit process"  
    xdg-open "http://google.com" &  
    echo "stop post-commit process"  
    


# Screencast Link
![hw0gif](https://cloud.githubusercontent.com/assets/8634231/9723046/3a29fd8a-5587-11e5-9086-b314def1a2aa.gif)

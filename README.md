# Modifying-CFS-Scheduler

<b> Course Project for Operating Systems (CSE231) </b><br>
<b> Instructor : Dr. Sambuddho Chakravarty </b>

This assignment os based on Modifying th CFS Scheduler based on soft real time requirements as CFS Scheduler is a  non-realtime scheduler, with non-realtime guarantees being given to processes. This task requires adding soft real time requirements to a process.
So, for each call to the scheduler it needs to check if the real-time guarantees of the process with softrealtime requirements are being met or not and also giving higher priority to the soft-realtime requirement of a process as compared to the vruntime that is normally
considered. This repository contains the patch.diff of the modified Linux Kernel as compared to the original one. 

<b> Skills Used : </b> C Programming Language, Linux



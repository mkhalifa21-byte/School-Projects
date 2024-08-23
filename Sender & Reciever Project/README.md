# Sender & Receiver IPC Project

## Team Members
- Mohamed Khalifa, Section 01, mkhalifa@csu.fullerton.edu 
- Mark Perez, Section 01, perezmd3129@csu.fullerton.edu 
- Conrad Chu, Section 01, chuconrad1@gmail.com 
- Ahsan, Section Section 01, ahsanamin90@csu.fullerton.edu

## Introduction
This project implements a sender and receiver using Inter-Process Communication (IPC) mechanisms such as shared memory and message queues. The goal is to transfer files between two processes synchronously.

## Goals
1. To solidify understanding of IPC principles.
2. To develop an appreciation for different IPC mechanisms.
3. To gain hands-on experience using shared memory and message queues.
4. To implement a practical application combining these IPC mechanisms.

## How to Compile
To compile the sender and receiver programs, please run the following commands in terminal:
- cd Project1-Mohamed-Mark-Conrad-Ahsan 
- make

## How to Run The Program
To run the sender and reciever, please use one terminal for the sender and another for the reciever
- First, for the reciever terminal, run ./receiver
- Second, for the sender terminal, run ./sender <FILE_NAME>
    - For example, ./sender <testingfile.mp3>
    - if needed to add a new file just include the file in directory of the project then compile then run the program again from step 1.
- Note: if for some reason the terminal says permission denied please run this: chmod +x sender receiver.

## Team Collaboration:
Since everyone in our group has different schedules, we tried to divide up the work and utilized discord to communicate. Mohamed worked on the sender file and sent it to the group for validation. Conrad and Mark worked on the receiver file and sent it back to Mohamad for validation where he made improvements on the code and sent it back to the group. Once both the sender and receiver files were complete, we ran the code sending a dummy MP3 file to test our work and were successful in having the receiver file play the MP3.

Results Screenshot:
![](Screenshot%202024-06-18%20at%201.59.46%E2%80%AFPM.png) 
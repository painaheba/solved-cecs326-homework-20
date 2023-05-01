Download Link: https://assignmentchef.com/product/solved-cecs326-homework-20
<br>
Chapter 13 (Page 1 through 14)

Purpose: This assignment provides experience with structured files. You also do a couple investigations into the Unix file structure.

Task 1)

Get a copy of the structured_file.c program. Complete the missing functions.

You will need to complete clearFile, writeRecord, and readRecord.

Task 2)

Compute how much disk the inodes use.

Assume you have a 32 gigabyte disk. For simplicity, for a gigabyte we will use 2<sup>30 </sup>bytes, so the disk size is 2<sup>35</sup>. Assume one inode is allocated for every 2048 bytes on disk (2<sup>11</sup>). Assume an inode is 64 bytes (2<sup>6</sup>).

How many bytes of the disk are allocated to inodes? If you want, you may give the answer as a power of 2.

Task 3)

Use the free command to examine how many kilobytes of RAM are allocated to buffers.

Task 4)

Use the df command to inspect the percent of the inodes that have been allocated on the disk. Also report the percentage of the disk space that is allocated.

Demo: Your task 1 code.

Submit: A printed or handwritten sheet with calculations and answers to task 2, 3, and 4.

Nathan Pickrell            13 November 2019 (Week 12 Lecture 1)           Due: 14 November 2019 (Week 12, Lab 2)
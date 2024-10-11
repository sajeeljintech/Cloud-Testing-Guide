# Testing and Reporting Guidelines

### Overview&#x20;

This section of the guide will review a general set of guidelines that are recommended for testing, to ensure that there is a certain level of continuity in our testing. This part of the guide will also advise testers on how to properly report a bug in the program including what status options are available and how best to document bugs or fixes.&#x20;

***

#### Find Your Tasks to Test

SGL staff will assign features (also known as tasks) to one or more user for testing. This is done by setting the "Testing Agent" of the task.To view tasks that are needing testing you can go to the QA - My Items to Test by click below﻿[Software Development - ACTIVE > SGL - Lite & Cloud- Misbah & Uzair > QA - My Items to Test](https://app.clickup.com/8560266/v/l/857ma-10251)﻿This view will show you tasks needing to be test. This will include those that have not had any testing done and are in a status of "Ready to Test" as well as those in status "QA - In Progress"

***

### What Next?

Select a feature or task to test. You can click on the task to view the details. Be aware there is likely very little detail in the task about what was done to make the feature. Below are some general guidelines.

1. Don't Understand the task - If you don't understand what the task is about you can make a note to that effect and leave the task in the "Ready to Test" state.
2. Testing That can't be completed at once - If you can't complete testing on a feature please set the status to "QA - In Progress" this will let us know that you are working on testing and plan to return to complete that work. These items will appear in your QA - My Items to Test list.

***

### Identifying a Bug

If you find an issue with how a feature or function works while testing a particular task please do the following

1. Change Status of Main Task - In the task you are testing change the status to "SGL - QA - Bug Report". If this task is already in that status you can leave it as is.
2. Click to Subtasks

* ![](https://t8560266.p.clickup-attachments.com/t8560266/33d557fb-848c-4ada-96ba-6d83e8a1cf30/image.png)

1. Click + New Task
2. Name task descriptively for the problem you encountered

* The name of the task should include the MODULE that you are testing in eg: Shows, classes, entries as well as a brief description of the bug that you have encountered&#x20;
  1. EXAMPLE: BUG - Shows - Record information not updating with save&#x20;

1. Open Task you created and provide details on what you found
   1. Context - What were you doing when you encountered the bug or issue.
   2. Environment - Please indicate what operating system you are using (Mac/Windows) and what browser you are using (Chrome, Firefox, Edge, Safari)
   3. How To Reproduce - If appropriate provide the steps the developers can take to reproduce the bug.
   4. Screenshots - Screenshots are extremely important. (see directions above for taking screenshots on Windows and Mac)
   5. Anything else to help the team understand the issue. The more details, the better!&#x20;
2. Status - Will default to work on now for the subtask. This can be left as is; two of our Developers will also be automatically assigned so you will not have to worry about assigning anyone to this new task ether&#x20;

### Questions & Suggestions&#x20;

If you have a question about a particular task or a suggestion, but don't believe there is an actual bug that is related to the task you are testing you can add a tag.&#x20;

1. On the main task you can select the "Add Tag" option on the top&#x20;

![](https://t8560266.p.clickup-attachments.com/t8560266/d01ed82f-57a2-4db1-bc82-1347cc91d6f6/image.png)

1. Select the "qu questions" tag&#x20;

![](https://t8560266.p.clickup-attachments.com/t8560266/f509a8a9-5da7-44eb-9421-5814fbacea43/image.png)

1. Add a comment on the task with your reason for adding the tag - either your question or suggestion for the task&#x20;

Coding Assignment 1

We have a student marks table containing subject wise marks. Students can attempt exams for the subject as many time he/she want. In the below example roll no: 1 student attempted DS exam twice. 1st time he got 25 marks, 2nd time he got 40 marks.

Input Dataframe:


<img width="406" alt="Screenshot 2025-05-07 at 11 43 23 AM" src="https://github.com/user-attachments/assets/2c699a2b-a822-4e03-b83a-120a8e8ff59f" />


Input frame contains multiple entries. So, in the output we want a unique Roll no,Subject entry. Where M1 is the latest marks, M2 is the second latest marks, M3 is third latest marks. E.g roll no 1 student scored 25 in 1st attempt and 40 in 2nd DS subject attempt. So, M1 = 40 (latest score) and M2 = 25 (second latest score). M3  = 0 (as there is no third attempt of these subjects). E.g 2: Suppose a student attempted the same subject 5 times. So only the last three attempts are considered, the rest two will be ignored. Date is the last attempted date. E.g M1 attempt date.

Output Dataframe:

<img width="610" alt="Screenshot 2025-05-07 at 11 44 17 AM" src="https://github.com/user-attachments/assets/ff28c502-677e-416d-894d-93e8f71c4600" />









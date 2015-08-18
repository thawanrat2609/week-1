# Instruction

## Read and understand the code, the logic behind it, the limitation of it
* Answer the question 1 - 4 below (you can edit this file directly)
* Change the code such that it will sort from larger to smaller, put the revision of your code below
* Change the code such that there is no flag variable, put the commit number below and answer question 5 


## Revision, put your commit number here
* Sort from larger to smaller: 
* Without flag:

## Questions
1. How this code can sort number from smaller to larger
 
Answer: ตรวจสอบค่าที่iกับตัวถัดไปคือi+1 โดยเริ่มที่กำหนดi=0 ถ้าค่าที่i>i+1ก็จะวนลูปไปเรื่อยๆจนกระทั่งค่าที่i<i+1ก็จะแสดงoutputออกมา
        โดยที่เรียงค่าจากน้อยไปมาก

2. What if two numbers equal, what will happen? 

Answer: ไม่เกิดอะไรขึ้น คือ ไม่มีการเข้าลูปwhile

3. How many times at line 24 will be executed (as a function of the size of input) 

Answer: [x,x*x]

4. Why we need flag variable ? 

Answer: ถ้าไม่มีการกำหนดตัวแปรflag จะมีการวนลูปwhileแค่รอบเดียวและไม่สามารถเรียงตัวเลขจากมากไปน้อยได้ครบทุกตัว

5. When we remove the flag variable, the code will run faster or slower? in which scenario? 

Answer:
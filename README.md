# task-14-a-report-card-system
#include<stdio.h>
main()
{
	printf("\n ////////////////////////////// STUDENT REPORT CARD ///////////////////////////////// \n");
	int num1 = 0 , num2 = 0 , num3 = 0 , num4 = 0 , num5 = 0 ;
	int sum = 0 ;
	float avg = 0 ;
    printf ("enter the name of the student :");
    char name [20];
    scanf("%s",&name);
    int standard = 0;
    printf ("enter the standard of the student :");
    scanf("%d",&standard);
if(standard<=6)
{
printf("the student is not eligeble for scholar badge :");
} 
else if(standard>=6);
{ 
printf("the student is eligeble for scholar badge:                   "); 

}

	printf("enter the student's parent's phone_number :");
	int phone_number [10] ;
	scanf ("%d" , &phone_number);
		printf("************************************************************************************************************************");
    printf("enter the marks in subject (MATHS , OUT OF 100) :");
    scanf("%d",&num1);
printf("enter the marks in subject (SCIENCE , OUT OF 100) :");
scanf("%d",&num2);
printf("enter the marks in subject (ENGLISH , OUT OF 100) :");
scanf("%d",&num3);
printf("enter the marks in subject(HINDI , OUT OF 100):");
scanf("%d",&num4);
printf("enter the marks in subject (SOCIAL SCIENCE , OUT OF 100) :");
scanf("%d" ,&num5);
	printf("************************************************************************************************************************");
	
		sum = num1+num2+num3+num4 +num5 ; 
	avg = sum/5 ;
		if(avg<=60)
{
printf("the student will not be awarded scholar badge :");
} 
else if(standard>=90);
{ 
printf("the student will be awarded scholar badge: \n"); 
	printf("\n ***********************************************************************************************************************");

}
printf("choose the students additional language :\n1. GERMAN \n2. FRENCH \n3. JAPENESE \n4. SPANISH");
int choice = 0;
scanf("%d",&choice);
switch(choice)
{ 
case 1:
printf("You picked GERMAN.                            "); 
break; 
case 2: 
printf("You picked FRENCH.                            "); 
break; 
case 3: 
printf("You picked JAPANESE.                          "); 
break; 
case 4: 
printf("You picked SPANISH.                           "); 
break; 
default : printf("Invalid choice"); 
	printf("************************************************************************************************************************");
} 
printf("enter student's extra curricular activities :");
char ext[50];
scanf("%s",&ext);
	printf("************************************************************************************************************************");
	printf("enter the grade for extra activity : \n1 A+ \n2 A \n3 B+ \n4 B");
	int choice2 = 0;
	scanf("%d" , &choice2);
	switch(choice2)
	{
case 1:
printf("You picked A+. \n"); 
break; 
case 2: 
printf("You picked A. \n"); 
break; 
case 3: 
printf("You picked B+.\n"); 
break; 
case 4: 
printf("You picked B. \n"); 
break; 
default : printf("Invalid choice"); 
	}
	sum = num1+num2+num3+num4 +num5 ; 
	avg = sum/5 ;

printf(" \n************************************************************************************************************************");

	printf("enter the grade for behaviour in school : \n1 A+ \n2 A \n3 B+ \n4 B");
	int choice3 = 0;
	scanf("%d" , &choice3);
	switch(choice3)
	{
case 1:
printf("You picked A+.                                                                                                           "); 
break; 
case 2: 
printf("You picked A.                                                                                                            "); 
break; 
case 3: 
printf("You picked B+.                                                                                                           "); 
break; 
case 4: 
printf("You picked B                                                                                                             "); 
break; 
default : printf("Invalid choice"); 
	}
printf("************************************************************************************************************************");
	printf("enter the grade for parctical (COMPUTER) : \n1 A+ \n2 A \n3 B+ \n4 B");
	int choice4 = 0;
	scanf("%d" , &choice4);
	switch(choice4)
	{
case 1:
printf("You picked A+.                                                                                                          "); 
break; 
case 2: 
printf("You picked A.                                                                                                           "); 
break; 
case 3: 
printf("You picked B+.                                                                                                          "); 
break; 
case 4: 
printf("You picked B                                                                                                            "); 
break; 
default : printf("Invalid choice"); 
	}
printf("************************************************************************************************************************");
	printf("enter the grade for practical (MATHS) : \n1 A+ \n2 A \n3 B+ \n4 B");
	int choice5 = 0;
	scanf("%d" , &choice5);
	switch(choice5)
	{
case 1:
printf("You picked A+.                                                                                                              "); 
break; 
case 2: 
printf("You picked A.                                                                                                               "); 
break; 
case 3: 
printf("You picked B+.                                                                                                              "); 
break; 
case 4: 
printf("You picked B                                                                                                                "); 
break; 
default : printf("Invalid choice"); 
	}
	printf("\n************************************************************************************************************************");
	printf("enter the grade for student's participation in class : \n1 A+ \n2 A \n3 B+ \n4 B");
	int choice6 = 0;
	scanf("%d" , &choice6);
	switch(choice6)
	{
case 1:
printf("You picked A+.\n"); 
break; 
case 2: 
printf("You picked A.\n "); 
break; 
case 3: 
printf("You picked B+. \n "); 
break; 
case 4: 
printf("You picked B \n "); 
break; 
default : printf("Invalid choice"); 
	}



printf("\n ///////////////////// THE FINAL REPORT IS //////////////////////////////////\n");

printf("NAME OF STUDENT : %s \n AND STANDARD %d \n  ",name ,standard);
printf("MARKS IN MATHS : %d  \n MARKS IN SCIENCE : %d \n MARKS IN ENGLISH : %d  \n MARKS IN HINDI : %d \n MARKS IN SOCIAL STUDIES : %d \n  " , num1 , num2 , num3 , num4 , num5);
printf("STUDENT'S CHOICE FOR THIRD LANGUAGE : %d  \n " , choice);
printf("STUDENT'S GRADE FOR EXTRA ACTIVITY : %d \n", choice2);
printf("STUDENT'S GRADE FOR BEHAVIOUR : %d  \n" , choice3);
printf("STUDENT'S GRADE FOR COMPUTER PRACTICAL : %d  \n",choice4);
printf("STUDENT'S GRADE FOR MATH PRACTICAL : %d  \n", choice5);
printf("STUDENT'S GRADE FOR STUDENT'S PARTICIPATION IN CLASS : %d  \n ", choice6);

printf("\n ***NOTE*** \n THE VALUE 1 IS A+ \n VALUE 2 IS A \n VALUE OF 3 IS B+ \n VALUE OF 4 IS B \n");
printf("\n\\\\\\\\\\\\\\\\\\\\\\\ PRESS ANY TWO KEYS TO EXIT \\\\\\\\\\\\\\\\\\\\\\\\\\\\\ \n");
getch();
getch();
}

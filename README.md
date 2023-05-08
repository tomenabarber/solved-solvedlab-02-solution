Download Link: https://assignmentchef.com/product/solved-solvedlab-02-solution
<br>
Overview:In this lab you are to write a Java program to prompt the user for an integer indicating a year and then print the calendar for that year. Run the instructor’s program in directory ~wang/sample20/lab02 for sample output.

Objective:This lab’s objective is to exercise you with the use of Java’s control statements. You are required to use exactly one while statement, one for statement and one switch statement.You will also practice on how to use some basic input methods of the Scanner class and some formatting techniques of method printf().Activities:1. Copy instructor’s JulianDate class from ~wang/sample20/lab02 into your working directory. The JulianDate class is used to determine the day of the week for the 1st day of January.JulianDate JD = new JulianDate();int date = JD.toJulian(yr,1,1);int dayOfWeek = (date+1)%7; // 0 means Sunday, 1 means Monday, etc.2. Develop your program according the pseudo code given in class.Notes:1. No arrays are allowed in this lab.2. Your output should be closely similar to the output of the instructor’s sample program.3. To determine whether a year is a leap year or not:a. If the year is a century year, the year must be divisible by 400.
---


---

<center><img src="https://i.imgur.com/EZtECRw.png"></center>
<hr>
<h3><b>Guru Nanak Dev Engineering College
    ESC-18104/18105 Programming for Problem Solving</b>
<pre><code>Name-Jasjot Singh Bagga 
Branch-InformationTechnology
Section - A2 
Roll Number - 1921047

# My C programes 
</code></pre>
</h3><h2 id="wap-to-swap-two-numbers-with-the-help-of-third-number">1:WAP to swap two number’s with the help of third number</h2>
<pre><code>#include&lt;stdio.h&gt;
int main()
 {
int first, second, temp;
printf("Enter first number: ");
scanf("%d",  &amp;first);
printf("Enter second number: ");
scanf("%d",  &amp;second);

temp = first

first = second;

second = temp;

printf("\nAfter swapping, firstNumber = %d\n", first);
printf("After swapping, secondNumber = %d", second);   
 return  0
}
</code></pre>
<p><strong>OUTPUT:</strong></p>
<pre><code>Enter first number: 12
Enter second number: 14

After swapping, firstNumber = 14
After swapping, secondNumber = 12
...

</code></pre>
<h2 id="wap-to-swap-two-numbers-without-using-third-number">2: WAP to swap two number’s without using third number</h2>
<pre><code>#include &lt;stdio.h&gt;

int  main()  
{  
int  a,  b;  
  
printf("Input two integers (a &amp; b) to swap\n");  
scanf("%d%d",  &amp;a,  &amp;b);  
  
a  =  a  +  b;  
b  =  a  -  b;  
a  =  a  -  b;

printf("a = %d\nb = %d\n",a,b);  
return  0;  
}
</code></pre>
<p><strong>OUTPUT:</strong></p>
<pre><code>Input two integers (a &amp; b) to swap 12 14
a=14
b=12
</code></pre>
<h2 id="wap-to-find-sum-of-two-numbers">3:WAP to find sum of two numbers</h2>
<pre><code>#include&lt;stdio.h&gt;
int main()
{                                                                                      
 int a;
 int b;
 int c ;
 printf("Enter two numbers to get sum:");
 scanf("%d  %d",&amp;a,&amp;b);
 printf(" \nThe result is :%d + %d= %d\n",a,b,c=a+b);
    return 0;
 }
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>Enter two numbers to get sum:45 55
 
The result is :45 + 55= 100
</code></pre>
<h2 id="wap-to-find-sum-and-average-of-five-numbers">4:WAP to find Sum and average of five numbers</h2>
<pre><code> // sum and average of number
#include&lt;stdio.h&gt;
  int main()
 {                                 
     int a,b,c,d,e,sum,avg;
                                                               
   printf("Enter five numbers:");
   scanf("%d %d %d %d %d",&amp;a,&amp;b,&amp;c,&amp;d,&amp;e);
    sum = a+b+c+d+e;
   printf("The sum is:%d\n",sum);
   avg = sum/5;
   printf("The average is:%d\n",avg);
  }
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>Enter five numbers:1 2 3 4 5 
The sum is:15
The average is:3
</code></pre>
<h2 id="wap-to-check-if-number-is-even-or-odd">5:WAP to check if number is even or odd</h2>
<pre><code>     #include&lt;stdio.h&gt;
int main()
{                                
  int a;   
 printf("Enter a number:");
 scanf("%d",&amp;a);
if(a%2==0)
printf("The  number is even\n");
else
 printf("The number is odd\n");
}
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>Enter a number:4
The  number is even
</code></pre>
<p><em><strong>OR</strong></em></p>
<pre><code>Enter a number:7
The number is odd
</code></pre>
<h2 id="wap-to-check-if-the-no.-is-a-prime-no.-or-not">6:WAP to check if the no. is a prime no. or not</h2>
<pre><code>#include&lt;stdio.h&gt;
int main()
{
int a,b,p=0;
printf("enter the number=");
scanf("%d",&amp;a);
for(b=2;b&lt;a;b++)
{
if(a%b==0)
{
p++;
}
}
if(p==2)
{
printf(" the no. %d is prime no.",a);
} 
else
{
printf(" the no. %d is not prime no.",a);
}
return 0;
}
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>enter the number=21
 the no. 21 is prime no.
</code></pre>
<h2 id="wap-to-check-the-numbers-in-user-specified-range-are-even-or-not">7:WAP to check the numbers in user specified range are even or not</h2>
<pre><code>   
#include&lt;stdio.h&gt;
int main()
{
int a,b,i,n,p=0;
printf("Enter starting and ending number");
scanf("%d%d",&amp;a,&amp;b);
for(i=a;i&lt;=b;i++)
{p=1;
for(n=2;n&lt;i;n++)
{                                                                  if(i%n==0)
{
p=0;
break;}
}
if(p==1){
printf("%d is a prime number",i);
}
}
return 0;
}
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>Enter starting and ending number4 9 
5 is a prime number7 is a prime number
</code></pre>
<h2 id="wap-to-show-puts-value-upto-n-number-using-loop">8:WAP to show puts value upto n number using loop</h2>
<pre><code>// to show punishment using loop
 #include&lt;stdio.h&gt;
 int main()
 {
 int i,a;
 printf("Enter the number upto punishment is shown:");
 scanf("%d",&amp;a);
  for(i=1;i&lt;=a;i++)
puts("WORK HARD AND ACHIEVE SUCCESS ");
return 0;
}
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>Enter the number upto punishment is shown:10
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS
</code></pre>
<h2 id="wap-to-show-areadiametercircumference-of-circle">9:WAP to show area,diameter,circumference of circle</h2>
<pre><code>   #include&lt;stdio.h&gt;
 int main()
  {
    float a;   
float  const pi=3.14;
   printf("Enter radius of circle:");
    scanf("%f\n",&amp;a);
  printf("diameter of circle is:%f\n",2*a);
  printf("circumference of circle:%f\n",2*pi*a);
  printf("Area of circle:%f\n",pi*a*a);
return 0;
 } 
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>Enter radius of circle:6
diameter of circle is:12.000000
circumference of circle:37.680000
Area of circle:113.040001
</code></pre>
<h2 id="wap-to-find-area-and-volume-of-rectangle">10:WAP to find area and volume of rectangle</h2>
<pre><code>//find area and volume of rectangle
#include&lt;stdio.h&gt;
int main()
{
 int l,b,h;
 printf("Enter length of rectangle:");
 scanf("%d",&amp;l);
 printf("\nEnter breadth of rectangle:");
 scanf("%d",&amp;b);
 printf("\nEnter height of rectangle:");
 scanf("%d",&amp;h);
 printf("\nThe area of rectangle is:%d",l*b);
 printf("\nThe volume is :%d\n",l*b*h);
 return 0;
 }
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>Enter length of rectangle:4 

Enter breadth of rectangle:3 

Enter height of rectangle:4

The area of rectangle is:12
The volume is :48
</code></pre>
<h2 id="wap-to-represent-a-table-of-user-input">11 .WAP to represent a table of user input</h2>
<pre><code>#include&lt;stdio.h&gt;
int main()
{
int n,i;
printf("enter the number=");
scanf("%d",&amp;n);
for(i=1;i&lt;=10;i++)
{
printf("\n %d X %d=%d",n,i,n*i);
}
printf("\n");
return 0;
}
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>enter the number=4

 4 X 1=4
 4 X 2=8
 4 X 3=12
 4 X 4=16
 4 X 5=20
 4 X 6=24
 4 X 7=28
 4 X 8=32
 4 X 9=36
 4 X 10=40
</code></pre>
<h2 id="wap-to-convert-fahrenheit-to-celsius">12: WAP to convert Fahrenheit to Celsius</h2>
<pre><code>#include&lt;stdio.h&gt;
int main()
{
float  c,f;
printf("Enter The Fahrenheit Value ");
scanf("%f",&amp;f);
c=(f-32)*5/9;
printf("Temprature in Centigrade=%f\n",c);
return 0;
}
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>Enter The Fahrenheit Value 22
Temprature in Centigrade=-5.555555
</code></pre>
<h2 id="wap-to-show-the-table-of-numbers-in-user-specified-range">13: WAP to show the table of numbers in user specified range</h2>
<pre><code>#include&lt;stdio.h&gt;
int main()
{
int a,b,c,d;
printf("enter the starting and ending no.");
scanf("%d %d",&amp;a,&amp;b);
for(c=a;c&lt;=b;c++)
{
for(d=1;d&lt;=10;d++)
{
printf("\n %dX%d=%d",c,d,c*d);
}
}
return 0;
}
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>enter the starting and ending no.3 5

 3X1=3
 3X2=6
 3X3=9
 3X4=12
 3X5=15
 3X6=18
 3X7=21
 3X8=24
 3X9=27
 3X10=30
 4X1=4
 4X2=8
 4X3=12
 4X4=16
 4X5=20
 4X6=24
 4X7=28
 4X8=32
 4X9=36
 4X10=40
 5X1=5
 5X2=10
 5X3=15
 5X4=20
 5X5=25
 5X6=30
 5X7=35
 5X8=40
 5X9=45
 5X10=50
</code></pre>
<h2 id="wap-to-show-even-tables-in-user-specified-range">14:WAP to show even tables in user specified range</h2>
<pre><code>#include&lt;stdio.h&gt;
int main()
{
int a,b,c,d;
printf("enter the starting and ending no.");
scanf("%d %d",&amp;a,&amp;b);
for(c=a;c&lt;=b;c++)
{
if(c%2==0)
{
for(d=1;d&lt;=10;d++)
{
printf("\n %dX%d=%d",c,d,c*d);
}
}
}
return 0;
}
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>enter the starting and ending no.2 7

 2X1=2
 2X2=4
 2X3=6
 2X4=8
 2X5=10
 2X6=12
 2X7=14
 2X8=16
 2X9=18
 2X10=20
 4X1=4
 4X2=8
 4X3=12
 4X4=16
 4X5=20
 4X6=24
 4X7=28
 4X8=32
 4X9=36
 4X10=40
 6X1=6
 6X2=12
 6X3=18
 6X4=24
 6X5=30
 6X6=36
 6X7=42
 6X8=48
 6X9=54
 6X10=60
</code></pre>
<h2 id="wap-to-show-result-of-operands">15: WAP to show result of operands</h2>
<pre><code>#include&lt;stdio.h&gt;
int main()
{
float a,b;
char c;
printf("enter two numbers:");
scanf("%f %f",&amp;a,&amp;b);
printf("enter the operator to perform (+,-,*,%,/)=");
scanf(" %c",&amp;c);
int d,r;
d=(int)a;
r=(int)b;
switch(c)
{
case '+':
printf("%f",a+b);
break;
case '-':
printf("%f",a-b);
break;
case '%':
printf("%d",d%r);
break;
case '*':
printf("%f",a*b);
break;
case '/':
printf("%f",a/b);
break;
default:
printf("you entered wrong operand");
}
return 0;
}
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>enter two numbers:12 30
enter the operator to perform (+,-,*,%,/)=%
12
</code></pre>
<h2 id="wap-to-print-a-patterns-of-calculator">16: WAP to print a patterns of calculator</h2>
<pre><code>#include&lt;stdio.h&gt;
int main()
{
puts(" _______________");
puts("|               |");
puts("|_______________|");
puts("| 1 | 2 | 3 |   |");
puts("|___|___|___|   |");
puts("| 4 | 5 | 6 | + |");
puts("|___|___|___|___|");
puts("| 7 | 8 | 9 | - |");
puts("|___|___|___|___|");
puts("|     0     | * |");
puts("|___________|___|");
}
</code></pre>
<p><strong>OUTPUT</strong></p>
<pre><code> _______________
|               |
|_______________|
| 1 | 2 | 3 |   |
|___|___|___|   |
| 4 | 5 | 6 | + |
|___|___|___|___|
| 7 | 8 | 9 | - |
|___|___|___|___|
|     0     | * |
|___________|___|
</code></pre>
<h2 id="wap-to-print-a-pattern-of-face">17:WAP to print a pattern of face</h2>
<pre><code>#include&lt;stdio.h&gt;
int a();
int main()
{
a();
}
int a()
{
puts("|__________________|");
puts("|    xxxxxxxxxxxx  |");  
puts("|    (  ^   ^  )   |");
puts("|    (  0   0  )   |");
puts("|     \\   |   /    |");
puts("|      \\  =  /     |");
puts("|       \\___/      |"); 
puts("|         |        |");
puts("|_________|________|");
}
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>___________________
|   XXXXXXXXXXX   |
|   ( ^     ^ )   |
|   ( 0     0 )   |
|    \   |   /    |
|     \     /     |
|      \ = /      |
|       \_/       |
|        |        |
|________|________|
</code></pre>
<h2 id="wap-to-print-stars-pattern">18:WAP to print stars pattern</h2>
<pre><code> // TO show stars using loop 
#include&lt;stdio.h&gt;
int main()
{ int i,j,k;
 printf("Enter the no. to show pattern:");
 scanf("%d",&amp;k);
 
  for(i=k;i&gt;=1;i--)
 {
  for(j=i;j&gt;=1;j--)
 {
  printf("* ");
 }
 printf("\n");
 }
 return 0;
 }
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>Enter the no. to show pattern:8
* * * * * * * * 
* * * * * * * 
* * * * * * 
* * * * * 
* * * * 
* * * 
* * 
*
</code></pre>
<h2 id="wap-to-find-factorial-of-a-number">19:WAP to find factorial of a number</h2>
<pre><code>#include&lt;stdio.h&gt;
int main()
{
int n,i;
unsigned long long factorial=1;
printf("enter a number");
scanf("%d",&amp;n);
if(n&lt;0)
{
printf("ERROR!");
}
else
{
for(i=1;i&lt;=n;i++)
{
factorial*=i;
}
}printf("\nFactorial of %d =%llu\n",n,factorial);
return 0;
}
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>enter a number7

Factorial of 7 =5040
</code></pre>
<h2 id="wap-to-find-the-factorial-of-a-number-by-using-recursion">20:WAP to find the factorial of a number by using recursion</h2>
<pre><code>
#include&lt;stdio.h&gt;
int main()
{
int n,i;
long int mult(int n);
printf("Enter the number");
scanf("%d",&amp;n);

printf("\nfactorial of %d is %d",n,mult(n));
}
long int mult(int n)
{
if(n&gt;=1)
return n*mult(n-1);
else
return 1;
}
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>
Enter the number5

factorial of 5 is 120


</code></pre>
<h2 id="write-a-program-to-add-two-matrices">21:Write a program to add two matrices</h2>
<pre><code>   #include &lt;stdio.h&gt;

    int main()
    {
       int m, n, c, d, first[10][10], second[10][10], sum[10][10];

       printf("Enter the number of rows and columns of matrix\n");
       scanf("%d%d", &amp;m, &amp;n);
       printf("Enter the elements of first matrix\n");

       for (c = 0; c &lt; m; c++)
          for (d = 0; d &lt; n; d++)
             scanf("%d", &amp;first[c][d]);

       printf("Enter the elements of second matrix\n");

       for (c = 0; c &lt; m; c++)
          for (d = 0 ; d &lt; n; d++)
             scanf("%d", &amp;second[c][d]);

       printf("Sum of entered matrices:-\n");
       
       for (c = 0; c &lt; m; c++) {
          for (d = 0 ; d &lt; n; d++) {
             sum[c][d] = first[c][d] + second[c][d];
             printf("%d\t", sum[c][d]);
          }
          printf("\n");
       }

       return 0;
    }


</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>Enter the number of rows and columns of matrix
2
2
Enter the elements of first matrix
11
12
13
13
Enter the elements of second matrix
11
12
13
13
Sum of entered matrices:-
22      24
26      26
</code></pre>
<!--stackedit_data:&#10;eyJoaXN0b3J5IjpbMTk0Njc2OTc1MiwxNjU2OTAxNTI4LC03Mj&#10;g2NzQ5NjUsLTc4ODExMDUzMywxNDAxMzg0NjY0LDE2MTgwMjUy&#10;ODAsNDg3NDA0MzAxLDIwOTY4MjEwMzQsLTIxMjg5MTIwOTIsLT&#10;I2MDQ0OTE2NywtMjc3NjA5ODExLDExMzUyMDA5NjEsLTY0MzA4&#10;ODI1NiwzOTMzOTkyMzgsNzc0OTQ3NzEzLC0xOTM0OTcwMDY2LC&#10;0xNTMzMjE1ODU2LDQwNzQ1NzQyMiwtMjMyMDc4MTA4LDEzMTEw&#10;NDM5MzddfQ==&#10;-->
<!--stackedit_data:&#10;eyJoaXN0b3J5IjpbLTE1MzA1MDQxMjksMTk4NTg2OTYzMSwxOT&#10;UwNjM2OTVdfQ==&#10;-->


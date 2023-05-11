# C_language-11
/*
#include<stdio.h>
#include<string.h>

// Code to compare two strings without using strcmp function
int main ()
{
// declare variables
char str1 [30], str2 [30];
int i = 0, flag=0 ,length1, length2, length;

// take two string input
printf ("Enter string1:");
gets (str1);
printf ("\nEnter string2:");
gets (str2);
//length of both string
length1 = strlen (str1);
length2 = strlen (str2);
if(length1>length2)
length=length1;
else
length=length2;
while (i<length)
{
if( str1 [i] == str2 [i])
{
i++;
continue;
}
if( str1 [i] < str2 [i])
{
flag = -1;
break;
}
if( str1 [i] > str2 [i])
{
flag = 1;
break;
}
}
if (flag == 0)
printf ("\nBoth strings are equal ");
if(flag == -1)
printf ("\nstring1 is less than string2 ");
if( flag == 1)
printf ("\nstring1 is greater than string2 ");
return 0;
}

//code for reversing a string without using strrev()
int main() {
char str[100], temp;
int i, j;
printf("\nEnter the string :");
gets(str);
i = 0;
j = strlen(str) - 1;
while (i < j) {
temp = str[i];
str[i] = str[j];
str[j] = temp;
i++;
j--;
}
printf("\nReverse string is :%s", str);
return 0;
}

// code to check whether the string is palindrome or not
int main() {
char str[100], temp;
char str1[100];
int i, j;
printf("\nEnter the string :");
gets(str);
i = 0;
j = strlen(str) - 1;
strcpy(str1,str);
while (i < j)
{
temp = str[i];
str[i] = str[j];
str[j] = temp;
i++;
j--;
}
if(strcmp(str1,str)==0)
{
printf("\n Given String is Palindrome");
}
else
{
printf("\n Not a Palindrome");
}
return 0;
}

// Code to convert all lowercase into uppercase
int main()
{
char str1[10];
int i,len;
printf("Enter any string \t");
gets(str1);
len=strlen(str1);
for(i=0;i<len;i++)
{
if(str1[i]>='a' && str1[i]<='z')

str1[i]=str1[i]-32;
}
puts("string in upper is");
puts(str1);
return 0;
}

// Code for converting all the uppercase into lowercase
int main()
{
char str1[10];
int i,len;
printf("Enter any string \n");
gets(str1);
len=strlen(str1);
for(i=0;i<len;i++)
{
if(str1[i]>='A' && str1[i]<='Z')
str1[i]=str1[i]+32;
}
puts("string in lower is");
puts(str1);
return 0;
}

//code to save a particular array easily
int main()
{
char names[5][10];
int i,n;
printf("\n Enter the number of students:");
scanf("%d",&n);
fflush(stdin);
for(i=0;i<n;i++)
{
printf("\n Enter the name of student %d: ",i+1);
gets(names[i]);
}
printf("\n Names of the students are:\n");
for(i=0;i<n;i++)
puts(names[i]);
return 0;
}

//Last program of the innning
int main()
{
char s[10],t;
int n,i,j;
printf("\n Enter String:");
gets(s);
n=strlen(s);
for(i=0;i<n-1;i++)
{
for(j=0;j<n-i-1;j++)
{
if(s[j]>s[j+1])
{
t=s[j];
s[j]=s[j+1];
s[j+1]=t;
}
}
}
printf("%s",s);
}
*/

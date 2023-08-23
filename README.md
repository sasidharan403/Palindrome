# EX-2 Palindrome
## Date:


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
### Step 1:
Create a new Class named palindrom.
### Step 2:
Declare three variables of string data type.
1. input - Store the input from user.
2. str - Convert user input to lower case and store it.
3. pal - Reverse the string str and store it.
### Step 3:
Get input from the user and store it. Then convert it to lower case.
### Step 4:
Using for loop, iterate through the each character from the end to begining and add it to the new variable called pal
### Step 5:
Using If-else statement check whether the input string & reversed string are same.
### Step 6:
Print the input and reversed string along with the whether palindrom or not.
### Step 7:
End of the Program.
## Program:
```
Developed By: A.sasidharan
Register Number: 212221240049
```
```C#
using System;
namespace Palindrome
{
    public class palindrome
    {
        public static void Main(string[] args)
        {
            string input, str, pal = "";
            Console.Write("Enter String: ");
            input = Console.ReadLine();
            str = input.ToLower();
            for (int i = str.Length - 1; i >= 0; i--)
            {
                pal += str[i];
            }
            if (str == pal)
            {
                Console.Write("{0} is a palindrome\n", input);
            }
            else
            {
                Console.Write("{0} is not a palindrome\n", input);
            }
        }
    }
}
```
## Output:
![1](https://github.com/sasidharan403/Palindrome/assets/94154712/47a21bc9-6ad3-4c25-a68a-9f8877a19023)
![2](https://github.com/sasidharan403/Palindrome/assets/94154712/824ae5f8-2050-4d86-b858-c62b1377dc5e)

## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.

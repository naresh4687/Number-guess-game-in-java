**Number Guessing game [JAVA]**

If the guessed number is bigger than the actual number, the program will respond with the message that the guessed number is higher than the actual number.
If the guessed number is smaller than the actual number, the program will respond with the message that the guessed number is lower than the actual number.
If the guessed number is equal to the actual number or if the K trials are exhausted, the program will end with a suitable message.

**Approach**: **Below are the steps**:  

The approach is to generate a random number using Math.random() method in Java.
Now using a loop, take K input from the user and for each input print whether the number is smaller or larger than the actual number.
If within K trials the user guessed the number correctly, print that the user won.
Else print that he was not able to guess and then print the actual number.

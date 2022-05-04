# Credit Card Validator

### Introduction
 A Credit Card Validator(CCV) is a software that verifies your credit card and validates it, this program is written using C++ language. CCV helps to verify the card is a valid credit card or not.
 <br>
 This program is based on a simple logic that we will discuss in detail. This program uses the Luhn Algorigthm to validate a Credit Card number.

### Features
 1. Validate your Credit Card
 2. Completely Secure
 3. Works Offline
 4. No Internet Required
 5. Faster
 6. Time Saving
 7. Reliable
 
### Approach
 Credit Card Number Validator, the last digit of a credit card number is the check digit, which protects against transcription errors such as an error in a single digit or switching two digits. 
 The following method is used to verify actual credit card numbers but, for simplicity, we will describe it for numbers with 8 digits instead of 16:
 <br>
 1. Starting from the rightmost digit, form the sum of every alternate digit. For example, if the credit card number is 43589795, then you form the sum: 5 + 7 + 8 + 3 = 23 .
 2. Double each of the digits that were not included in the step 1 . Add all digits of the resulting numbers. For example, with the number given above, digits left out in step 1 from rightmost : 9 , 9 , 5 and 4 , doubling the digits, yields: 18 18 10 8. Adding all digits in these values yields: 1 + 8 + 1 + 8 + 1 + 0 + 8 = 27 .
 3. Add the sums of the two preceding steps. If the last digit of the result is 0, or the sum is the multiple of 10 , then the credit card number is valid, else not valid. In our case, 23 + 27 = 50 , so the number is VALID.
 
### System Requirements
 1. Processor        - Intel Core Pentium or above
 2. Operating System - Windows vista or above
 3. Memory           - 1Gb Ram or more
 4. Hard Disk Space  - 5MB

### Output

Enter Card Number
<br>
![Initial Stage](https://github.com/rrtutors/Credit-Card-Checker-in-CPP/blob/main/img/ccv1.png)
<br>

if VALID
<br>
![Initial Stage](https://github.com/rrtutors/Credit-Card-Checker-in-CPP/blob/main/img/ccv2.png)
<br>

id NOT VALID
<br>
![Initial Stage](https://github.com/rrtutors/Credit-Card-Checker-in-CPP/blob/main/img/ccv3.png)
<br>

## Thanks
# CCV
<img width="1919" height="1031" alt="image" src="https://github.com/user-attachments/assets/ae3e0f6a-6a72-44c4-8928-8d5b120a181d" />**Week 1**
**Task 1 pseudocode**
START 
 
1. Fill kettle with water 
2. Turn kettle on 
3. Wait until water boils 
4. Get a cup 
5. Add coffee powder to cup 
 
6. IF sugar is desired THEN 
  Add sugar 
END IF 
 
7. Pour boiled water into cup 
8. Stir with spoon 
9. Serve coffee 
 
END 
 

**Task 2   Flowchart**
<img width="361" height="907" alt="image" src="https://github.com/user-attachments/assets/4d29d1d5-ae9d-41e8-86bb-c3209e284be5" />

**Task 3 Screenshot of working program**
<img width="1366" height="957" alt="week 1 ss" src="https://github.com/user-attachments/assets/b7b07e86-eff4-47a9-be27-f46704332fc6" />


**Task 4  design and code snippet**
<img width="1373" height="972" alt="image" src="https://github.com/user-attachments/assets/b1597378-b600-475f-ac6a-830d6403ec34" />


**Week 2**

Task 1 Pseudo code and screenshot of code

1. Declare an int variable for the sensor ID and assign the value 99.
2. Declare a float variable for the temperature and assign the value 12.34.
3. Declare a char variable for the status code and assign the value 'A'.
4. Print the values of the variables with descriptive labels.

<img width="1359" height="953" alt="image" src="https://github.com/user-attachments/assets/a27a2bb4-46f7-4cdc-8719-c7aa19c8e216" />


Task 2 pseudocode and screenshot

1. Prompt the user for a two-digit number.
2. Read the number into an integer.
3. Extract the first and second digits using division and modulo operations:
4. First digit: number / 10
5. Second digit: number % 10
6. Recombine the digits in reverse order to form the new number.
7. Print the reversed number.
<img width="1373" height="977" alt="image" src="https://github.com/user-attachments/assets/f4470106-d162-43be-8cdd-c0fd80a2432c" />

Task 3

<img width="1370" height="961" alt="image" src="https://github.com/user-attachments/assets/45ea89b3-052c-45f7-bf26-209cb4e7fc15" />



Task 4 flowchart and code
<img width="1704" height="403" alt="image" src="https://github.com/user-attachments/assets/2983335d-e514-4e62-b33a-6aeba907d95f" />


<img width="1375" height="972" alt="image" src="https://github.com/user-attachments/assets/4f628bf6-d1e6-4695-aa99-8cf934460c7c" />


Task 5 pseudocode and code

1. Prompts the user for a start value and interval.
2. For each step, calculate f(x) using the provided formula
3. Display results in a table.

   <img width="1895" height="986" alt="image" src="https://github.com/user-attachments/assets/1e91dcfc-ad88-4157-b831-6ac9d9e02dfb" />


Task 6

<img width="1919" height="1031" alt="image" src="https://github.com/user-attachments/assets/50ab0bf4-e845-46a3-b183-984d7bd28712" />

Task 7

<img width="1918" height="1032" alt="image" src="https://github.com/user-attachments/assets/a5ae3ce6-ab32-42cc-af63-e27025159e95" />



**Week 3 **

Task 1
Pseudo Code
1. Prompt the user for four temperature readings.
2. Compare the first two readings to find the smaller of the two.
3. Compare the minimum of the first two readings with the third.
4. Compare the current minimum with the fourth reading.
5. Display the smallest value.

Code


<img width="1919" height="1036" alt="image" src="https://github.com/user-attachments/assets/72651526-f609-4d55-8b4f-70c687eb48f9" />


Task 2

Pseudocode

Prompt the user for four temperature readings.
Compare and swap values to arrange the temperatures in ascending order.
Repeat for descending order.

Code
<img width="1919" height="1026" alt="image" src="https://github.com/user-attachments/assets/a33fe7fe-36b4-448c-b4a6-2e3f1cb5c2a6" />


Task 3
Pseudocode

1.Generate a random secret number between 1 and 100.
2. Prompt the user to guess the number (up to 3 times).
3. Compare the guessed number with the secret number and provide feedback on whether it's too high or too low.
4. If correct, display a success message; otherwise, inform the user of the remaining attempts.

Code

<img width="1919" height="1031" alt="image" src="https://github.com/user-attachments/assets/9c70bf38-c96a-4881-b0e7-1615584ca8ab" />

Task 4

Pseudocode

START
INPUT grade

IF grade outside 0-100
   PRINT error
ELSE
   DIVIDE grade by 10

   SWITCH result
      10, 9, 8 → A
      7, 6 → B
      5, 4 → C
      3 → D
      default → F
END

   
Code

<img width="1919" height="1029" alt="image" src="https://github.com/user-attachments/assets/88a262db-89a5-4a26-b07a-44e1c3e8a523" />

   
Task 5
Pseudocode

START
INPUT number

IF outside range
   PRINT error
ELSE
   CHECK positive / negative / zero
   CHECK odd / even
END

code
<img width="1919" height="1028" alt="image" src="https://github.com/user-attachments/assets/c20291d9-8d6b-4635-a9b9-e7ed7508b6db" />


Task 8

pseudocode
START
INPUT character

IF lowercase
   CONVERT to uppercase

PRINT character
END


code

<img width="1919" height="1024" alt="image" src="https://github.com/user-attachments/assets/3c57e077-24d0-4c24-98d6-98d1c83e52b6" />


**Week 4**

Task 1

Pseudocode
START

DECLARE array[10]

FOR i = 0 to 9
    array[i] = -1.0
END FOR

FOR i = 0 to 9
    PRINT array[i]
END FOR

END
Code
<img width="1919" height="1029" alt="image" src="https://github.com/user-attachments/assets/6c99bfa2-6ca7-4080-a77b-9f360b710f60" />


Task 2

Pseudocode
START

DECLARE array with 8 float values

SET min = first element
SET max = first element
SET sum = 0

FOR each element
    IF element < min
        min = element
    ENDIF

    IF element > max
        max = element
    ENDIF

    sum = sum + element
END FOR

average = sum / 8

PRINT min, max, average

END

Code
<img width="1919" height="1028" alt="image" src="https://github.com/user-attachments/assets/7338584e-f194-408a-bde5-e9b5c4444e65" />


Task 3

Pseudocode
START

DECLARE integer array

SET positiveCount = 0
SET negativeCount = 0
SET zeroCount = 0

FOR each element
    IF element > 0
        positiveCount++
    ELSE IF element < 0
        negativeCount++
    ELSE
        zeroCount++
END FOR

PRINT all counts

END

code

<img width="1919" height="1026" alt="image" src="https://github.com/user-attachments/assets/cd6eb8b5-d8e9-4077-9eb6-ca779828b4b5" />


Task 4

Pseudocode

START

DECLARE array of 15 values

INPUT target

SET found = 0

FOR each element
    IF element = target
        PRINT position
        found = 1
        BREAK
    ENDIF
END FOR

IF found = 0
    PRINT not found
ENDIF

END

code

<img width="1919" height="1028" alt="image" src="https://github.com/user-attachments/assets/8dc747a4-b3ce-49f6-8e9c-f7bdf66c98a8" />

Task 5

Pseudocode

START

DECLARE char array

FOR i = last index down to 0
    PRINT array[i]
END FOR

END

Code
<img width="1919" height="1028" alt="image" src="https://github.com/user-attachments/assets/3a8ad178-dc98-44a7-a10e-18a92b15d85d" />


**Week 5**
Task 1

Pseudocode
START

CREATE function print_welcome_message
    PRINT welcome text
END FUNCTION

MAIN
    CALL print_welcome_message
END

Code
<img width="1917" height="1027" alt="image" src="https://github.com/user-attachments/assets/9e9acef3-d3a5-4536-a818-1426ad275901" />




Task 2

Pseudocode

START

CREATE function add_numbers(a, b)
    RETURN a + b
END FUNCTION

MAIN
    INPUT num1, num2
    result = add_numbers(num1, num2)
    PRINT result
END
Code
<img width="1919" height="1032" alt="image" src="https://github.com/user-attachments/assets/64417b45-d840-42cc-b020-6ba3c4ed2a3c" />


Task 3

Pseudocode

START

CREATE circumference(radius)
    RETURN 2 * PI * radius

CREATE area(radius)
    RETURN PI * radius * radius

MAIN
    INPUT radius
    PRINT circumference
    PRINT area
END

Code

<img width="1919" height="1023" alt="image" src="https://github.com/user-attachments/assets/5fdba892-fd30-4ab7-b1f5-de6841a227d8" />


Task 4

Pseudocode

START

CREATE is_even(number)
    IF divisible by 2
        RETURN 1
    ELSE
        RETURN 0

MAIN
    INPUT number

    IF is_even(number)
        PRINT Even
    ELSE
        PRINT Odd
END
code

<img width="1919" height="1026" alt="image" src="https://github.com/user-attachments/assets/a552da3d-2054-4061-a6ff-6f22c64087d5" />

Task 5

Pseudocode
START

CREATE power(base, exponent)

SET result = 1

FOR i = 1 to exponent
    result = result * base

RETURN result

MAIN
    INPUT base, exponent
    PRINT result
END

Code

<img width="1919" height="1028" alt="image" src="https://github.com/user-attachments/assets/d98aa092-5172-4f14-aad6-3f058bd9f741" />


Task 6

Code

<img width="1919" height="1032" alt="image" src="https://github.com/user-attachments/assets/2ce46a45-f89b-4fd5-a3a2-dfa7933bb855" />

**What was the most difficult part?**
Realising that although the code actually looked like it would work, it doesn't because C passes the copies of variables.

**Explain "Pass by Value in your own words**

Pass by value means that the changes made in the function affect only the originals and not the copies.

**Why are function prototypes important?**

Function prototypes allow us to make sure that the function works before it's implemented into longer code.


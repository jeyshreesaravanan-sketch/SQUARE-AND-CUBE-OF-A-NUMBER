
# Square-Cube-of-a-number-using-8051
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
MOV A, 30H
MOV B, A
MUL AB
MOV 40H, A
MOV 41H, B
HERE: SJMP HERE
END
```

## OUTPUT
<img width="1075" height="549" alt="image" src="https://github.com/user-attachments/assets/c3722914-2e19-46c1-8e5f-aee63569ce92" />


## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```
MOV A, 30H
MOV B, A
MUL AB
MOV R2, A
MOV R3, B

MOV A, R2
MOV B, 30H
MUL AB

HERE: SJMP HERE
END
```


## OUTPUT
<img width="893" height="407" alt="image" src="https://github.com/user-attachments/assets/ab24b636-7d1c-41fa-9b92-12042412846c" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.



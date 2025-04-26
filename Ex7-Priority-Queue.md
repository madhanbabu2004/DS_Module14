# EX.NO : 2(B) Priority Queue
## DATE: 03/03/2025
## AIM:
To formulate the C code to display the elements of the priority queue after insertion and deletion operation.

## Algorithm
1. Start 
2. Define a function printArray() that takes an array and its size as parameters. 
3. Loop through the array from index 0 to size-1. 
4. Print each element of the array during the loop. 
5. After printing all elements, print a newline for formatting. 
6. End    

## Program:
```

Program to o display the elements of the priority queue after insertion and deletion operation
Developed by: MADHAN BABU P
RegisterNumber:  212222230075

```
```c

/*#include <stdio.h>
int size = 0;
*/
void printArray(int array[], int size) {
  int i;
  if(size == 0)
  {
      printf("Heap is empty");
  }
  else
  {
    for(i=0; i<size; i++)
    {
      printf("%d ", array[i]);
    }
  }
  
}

```
## Output:
![437354798-aa8d3e98-4e70-4048-9f60-faf5ae636aac](https://github.com/user-attachments/assets/f435b5e3-989d-4900-95ba-bf943148d373)


## Result:
Thus, the C program to display the elements of the priority queue after insertion and deletion operation is implemented successfully

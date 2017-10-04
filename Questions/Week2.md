# Lesson Plan:

- ### Go over some lab sheets.

- ### Question from last week:

    List out the different types of loop control for C.

    - `while (condition) {statement}`
   - `do {statement} while (condition)`
    - `for (int i = 0; i > 10; i++) {statement}`


- #### Using a while loop, iterate a and print a while a is less than 20:
    ```c
    #include <stdio.h>
 
    int main () {

        /* local variable definition */
        int a = 10;

        /* while loop execution */
        while( a < 20 ) {
        printf("value of a: %d\n", a);
        a++;
        }
 
        return 0;
    }
    ```
    Modify the above code for a do while statement
    
- #### Using a for loop do the same:
    ```c
    #include <stdio.h>
 
    int main () {

        int a;
	
        /* for loop execution */
        for( a = 10; a < 20; a = a + 1 ){
            printf("value of a: %d\n", a);
        }
 
        return 0;
    }
    ```
- ### Loop through an array with 5 numbers in it with a for loop:    
    ```c
    #include <stdio.h>
 
    int main () {

        int i, array[5] = {0,1,2,3,4};
	
        /* for loop execution */
        for( i = 0; i < 5; i = i + 1 ){
            printf("value in array: %d\n", array[i]);
        }
 
        return 0;
    }
    ```

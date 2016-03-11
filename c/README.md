Hello World in C
===

Hello World is five lines of code in C:

    #include <stdio.h>
    
    int main() {
        printf("Hello C world!");
        return 0;
    }

The first line, `#include <stdio.h>` includes the C header file *stdio.h* into the main program file. This allows our program to write to the terminal window. The line `int main()` declares that this function is going to return an integer value. The curly brace opens a block, and within that block we use the `printf()` function to display the string "Hello C world!" to the screen. Then we return the value 0, which indicates success. The closing curly brace indicates the end of the `main()` function.

To run *hello.c* you first need to compile it:

    c$ gcc -o hello hello.c
    
This command tells the `gcc` compiler to output an executable file called *hello* based on the code in the C file *hello.c*. You can run this executable from the command line:

    c$ ./hello
    Hello C world!

---

Return to [Hello Worlds](../README.md).
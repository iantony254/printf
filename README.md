##PRINTF PROJECT

This project is a collaborative effort by Ian Anthony and Grace Were to implement our own version of the printf function in C.

DESCRIPTION

The printf function is a standard library function in C that allows you to format and print text to the console. Our implementation aims to replicate the basic functionality of the standard printf function, including support for various format specifiers such as %s, %d, %c, etc.

USAGE

To use our printf function, simply include the main.h header file in your C code. Once done, call the printf function, passing in any desired format specifiers and arguments.
Here's an example usage:

#include main.h

int main()

{

    int num = 42;
    char str[] = "hello";
    printf("The answer is %d and the string is %s", num, str);
    return 0;

}

This will output the following to the console:

    The answer is 42 and the string is hello.

IMPLEMENTATION DETAILS

Our printf function is implemented using a combination of va_arg, va_list, and va_start macros from the standard stdarg.h header file. We also make use of various string manipulation functions such as strlen and strcat to handle the formatting of strings.

CONTACT INFORMATION

Feel free to reach out to graciewere@gmail.com or iantonyochola@gmail.com, if you find a bug or have an idea for a new feature.

LICENSE

MIT License.

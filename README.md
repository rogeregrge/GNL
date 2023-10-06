<h1 align="center">
	42cursus' get_next_line
</h1>

<p align="center">
	<b><i>Development repo for 42cursus' get_next_line project</i></b><br>
	For further information about 42cursus and its projects, please refer to <a href="https://github.com/rogeregrge?tab=repositories"><b>my repo</b></a>.
</p>

# 🗣️ About

> GNL is a function that returns a line, read from a file descriptor.

GetNextLine is the second project in the study program at School 42 (UNIT Factory).
Calling the function get_next_line in a loop will then allow the user to read the text available on the file descriptor one line at
a time until the end of it. It has to behave well both on external files and standard input. The function should return the line that
has just been read. If there is nothing else to read or if an error has occurred it should return NULL.

All functions are created in accordance with Norm - the bunch of rules how code should be formatted.

**NOTE!** <br />
Because of 42 School norm requirements: <br />

- All variables are declared and aligned at the top of each function <br />
- Each function can't have more then 25 lines of code <br />
- C++ style code commenting is forbidden <br />
- Project should be created just with allowed functions otherwise it's cheating. <br />

Of course you can read file lines, using standart C library, but in our case we needed to create our own function, using read, malloc, free and our libft library functions that we created earlier.

The project make student more confident with files manipulations, dynamic memory allocation and using pointers, arrays and linked lists. Also I get familiarized with static variables in this project.

This function and ft_printf(next project) were used in next projects a lot.

#### More about School 42 you can find here: https://en.wikipedia.org/wiki/42_(school)

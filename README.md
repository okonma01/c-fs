# Ext2 File System Implementation in C

This repository contains a C implementation of the ext2 file system, a widely used file system format in Linux. The project aims to provide a functional ext2 file system that supports basic file operations. This README will guide you through the project structure and how to build and run the code.

## Project Structure

The project folder is structured as follows:

- `Makefile`: This file contains the build instructions for compiling the project.
- `ext2.h`: Header file containing data structures, constants, and function prototypes.
- `ext2.c`: Implementation of core ext2 file system functions.
- `ext2dir.c`: Implementation of directory-related functions.
- `ext2fs.c`: Implementation of file system-level functions.
- `ext2file.c`: Implementation of file-related functions.
- `ext2symlink.c`: Implementation of symbolic link functions.
- `ext2test.c`: Test suite for the ext2 file system functions.
- `ext2test.o`: Object file generated from the test suite source.
  
## Building the Project

To build the ext2 file system implementation, follow these steps:

1. Open a terminal window.
2. Navigate to the project directory using the `cd` command.
3. Run the `make` command to compile the project.
4. The compiled executable will be generated (possibly named `ext2fs`). 

## Running Tests

The project includes a test suite (`ext2test.c`) to verify the functionality of the implemented ext2 file system functions. To run the tests:

1. Build the project as mentioned in the previous section.
2. Run `./ext2fs ext2test` in the terminal.
3. The test suite will execute, and you'll see the results on the terminal.

## Usage

After building the project, you can use the generated executable to interact with the ext2 file system. The general syntax is:

`./ext2fs <command> <arguments>`

Replace `<command>` with the desired command and provide relevant arguments.

## Contributing

Contributions to this project are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test thoroughly.
4. Submit a pull request describing your changes.

## License

This project is licensed under the [MIT License](LICENSE).

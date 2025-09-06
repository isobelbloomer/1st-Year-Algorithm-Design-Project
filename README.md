# C File Project

This is a C program that reads in text files and uses circular queues to merge the data into one list by order of weight.

This project received **100%** in Algorithm Design at TU Dublin.

## How it works
- The program reads in lists of data from 4 text files.
- It sorts each list by weight and then sorts each list into a single list sorted by weight.
- All functionality is implemented in a single file (`main.c`).

## Files
- `main.c` → main program
- `input1.txt`, `input2.txt`, `input3.txt`, `input4.txt` → sample input files

## How to run
On Linux/macOS:
```bash
gcc main.c -o program
./program

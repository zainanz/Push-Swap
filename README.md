# Push_Swap

42 School Project — Push_Swap

---

## Description

Push_Swap is about sorting data on a stack, with a limited set of operations, using two stacks (A and B). The goal is to write a program that, given a list of **unique integers**, outputs a sequence of moves to sort them in ascending order in stack A. Duplicates are **not allowed** (input containing duplicates should trigger an error).

---
![Demo](gif/push_swap.gif)

## ⚙ Features / Requirements

- Input is a sequence of integers passed as command-line arguments.  
- No duplicate numbers; if duplicates are found, the program prints `Error` and exits.  
- Only the following operations are allowed:
  - `sa`, `sb`, `ss`
  - `pa`, `pb`
  - `ra`, `rb`, `rr`
  - `rra`, `rrb`, `rrr`
- At the start:
  - All numbers are in stack A (in the order given by arguments).
  - Stack B is empty.  
- At the end:
  - Stack A must be sorted in ascending order.
  - Stack B must be empty.
- If the input is already sorted, no operations (or minimal) should be output.  
- Proper error handling: invalid numbers, out-of-range values, non-integer inputs, etc., should lead to error messages.

---

## Usage

```bash
# Clone the repo
git clone https://github.com/zainanz/push_swap.git
cd push-swap

# Build
make

# Run
./push_swap 4 2 9 1 5

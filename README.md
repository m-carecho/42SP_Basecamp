<div align="center">
<a href="https://github.com/m-carecho/42SP_Basecamp"><img height="20%" width="100%" src="https://user-images.githubusercontent.com/98053054/153719199-efe3a54c-4124-4f66-92fe-69959c8cfd11.png" /></a>
</div>

---

# 🔖 Index

* [What is Basecamp?](#sparkles-what-is-libft)
* [Note](#pushpin_Note)
* [C lists](#bookmark_tabs-list-of-functions)
* [Technologies](#computer-technologies)

---

# :sparkles: What is Basecamp?
Basecamp is the selection process of 42 São Paulo, It is an immersive 20-day training, which takes place virtually through Discord. In this immersion, all people who participate will experience the learning method and culture of 42 in practice.

---

# :pushpin: Note
The exercises included in this repository were refactored and performed after my entry into 42, I decided to redo the lists that I did not perform during basecamp for training purposes, during basecamp I only performed up to list C04.
Shell lists are not included in this repository.

The exercises included here have not been corrected by Moulliette

---

# :bookmark_tabs: C lists

## List  `C00`
#### 📍 Allowed functions: `write`

- [ ] [`Exercice 00 : ft_putchar`]()	- Write a character that displays the character passed as a parameter.

- [ ] [`Exercice 01 : ft_print_alphabet`]()	- Create a function that displays the alphabet in lowercase, on a single line, by ascending order, starting from the letter 'a'.

- [ ] [`Exercice 02 : ft_print_alphabet`]()	- Create a function that displays the alphabet in lowercase, on a single line, by descending order, starting from the letter 'z'.

- [ ] [`Exercice 03 : ft_print_numbers`]()	- Create a function that displays all digits, on a single line, by ascending order. 

- [ ] [`Exercice 04 : ft_is_negative`]()	- Create a function that displays 'N' or 'P' depending on the integer's sign entered as a parameter. If n is negative, display 'N'. If n is positive or null, display 'P'.

- [ ] [`Exercice 05 : ft_print_comb`]()	- Create a function that displays all different combinations of three different digits on ascending order, listed by ascending order - yes, repetition is voluntary.

- [ ] [`Exercice 06 : ft_print_comb2`]()	- Create a function that displays all different combination of two digits between 00 and 99, listed by ascending order. 

- [ ] [`Exercice 07 : ft_putnbr`]()	- Create a function that displays the number entered as a parameter. The function has to be able to display all possible values within an int type variable.

- [ ] [`Exercice 08 : ft_print_combn`]()	- Create a function that displays all different combinations od n numbers by ascending.



## List  `C01`
#### 📍 Allowed functions: `write` only in exercise 05

- [ ] [`Exercice 00 : ft_ft`]()	- Create a function that takes a pointer to int as a parameter, and sets the value "42"
to that int.

- [ ] [`Exercice 01 : ft_ultimate_ft`]()	- Create a function that takes a pointer to pointer to pointer to pointer to pointer
to pointer to pointer to pointer to pointer to int as a parameter and sets the value
"42" to that int.

- [ ] [`Exercice 02 : ft_ultimate_ft`]()	- Create a function that swaps the value of two integers whose addresses are entered
as parameters.

- [ ] [`Exercice 03 : ft_ultimate_ft`]()	- Create a function ft_div_mod prototyped like this :
`void ft_div_mod(int a, int b, int *div, int *mod);`
This function divides parameters a by b and stores the result in the int pointed by
div. It also stores the remainder of the division of a by b in the int pointed by mod.

- [ ] [`Exercice 04 : ft_ultimate_div_mod`]()	- Create a function ft_ultimate_div_mod with the following prototype :
`void ft_ultimate_div_mod(int *a, int *b);`
This function divides parameters a by b. The result of this division is stored in the
int pointed by a. The remainder of the division is stored in the int pointed by b.

- [ ] [`Exercice 05 : ft_putstr`]()	- Create a function that displays a string of characters on the standard output.

- [ ] [`Exercice 06 : ft_strlen`]()	- Create a function that counts and returns the number of characters in a string

- [ ] [`Exercice 07 : ft_rev_int_tab`]()	- Create a function which reverses a given array of integer (first goes last, etc).

- [ ] [`Exercice 08 : ft_sort_int_tab`]()	- Create a function which sorts an array of integers by ascending order.



## List  `C02`
#### 📍 Allowed functions: `write`

- [ ] [`Exercice 00 : ft_strcpy`]()	- Reproduce the behavior of the function strcpy (man strcpy).

- [ ] [`Exercice 01 : ft_strncpy`]() - Reproduce the behavior of the function strncpy (man strncpy).


- [ ] [`Exercice 02 : ft_str_is_alpha`]()	- Create a function that returns 1 if the string given as a parameter contains only
alphabetical characters, and 0 if it contains any other character.

- [ ] [`Exercice 03 : ft_str_is_numeric`]()	- Create a function that returns 1 if the string given as a parameter contains only
digits, and 0 if it contains any other character.

- [ ] [`Exercice 04 : ft_str_is_lowercase`]()	- Create a function that returns 1 if the string given as a parameter contains only
lowercase alphabetical characters, and 0 if it contains any other character.

- [ ] [`Exercice 05 :  ft_str_is_uppercase`]()	- Create a function that returns 1 if the string given as a parameter contains only
uppercase alphabetical characters, and 0 if it contains any other character.

- [ ] [`Exercice 06 : ft_str_is_printable`]()	- Create a function that returns 1 if the string given as a parameter contains only
printable characters, and 0 if it contains any other character.

- [ ] [`Exercice 07 : ft_strupcase`]()	- Create a function that transforms every letter to uppercase.

- [ ] [`Exercice 08 : ft_strlowcase`]()	- Create a function that transforms every letter to lowercase

- [ ] [`Exercice 09 : ft_strcapitalize`]()	- Create a function that capitalizes the first letter of each word and transforms all
other letters to lowercase.

- [ ] [`Exercice 10 : ft_strlcpy`]()	- Reproduce the behavior of the function strlcpy (man strlcpy).

- [ ] [`Exercice 11 : ft_putstr_non_printable`]()	- Create a function that displays a string of characters onscreen. If this string contains characters that aren’t printable, they’ll have to be displayed in the shape of
hexadecimals (lowercase), preceeded by a "backslash".

- [ ] [`Exercice 12 : ft_print_memory`]()	- Create a function that displays the memory area onscreen
• The display of this memory area should be split into three "columns" separated by a space :
  ◦ The hexadecimal address of the first line’s first character followed by a ’:’.
  ◦ The content in hexadecimal with a space each 2 characters and should be
  padded with spaces if needed (see the example below).
  ◦ The content in printable characters.
• If a character is non-printable, it’ll be replaced by a dot.
• Each line should handle sixteen characters.
• If size equals to 0, nothing should be displayed





## List  `C03`
#### 📍 Allowed functions:

- [ ] [`Exercice 00 : `]()	-

## List  `C04`
#### 📍 Allowed functions:

- [ ] [`Exercice 00 : `]()	-

## List  `C05`
#### 📍 Allowed functions:

- [ ] [`Exercice 00 : `]()	-

## List  `C06`
#### 📍 Allowed functions:

- [ ] [`Exercice 00 : `]()	-

## List  `C07`
#### 📍 Allowed functions:

- [ ] [`Exercice 00 : `]()	-

## List  `C08`
#### 📍 Allowed functions:

- [ ] [`Exercice 00 : `]()	-

## List  `C09`
#### 📍 Allowed functions:

- [ ] [`Exercice 00 : `]()	-

## List  `C10`
#### 📍 Allowed functions:

- [ ] [`Exercice 00 : `]()	-

## List  `C11`
#### 📍 Allowed functions:

- [ ] [`Exercice 00 : `]()	-

## List  `C12`
#### 📍 Allowed functions:

- [ ] [`Exercice 00 : `]()	-

## List  `C13`
#### 📍 Allowed functions:

- [ ] [`Exercice 00 : `]()	-






---

# :computer: Technologies

This Project was made with:

* [C](https://devdocs.io/)
* [Shell](https://unixguide.readthedocs.io/en/latest/unixcheatsheet/)
* [clang](https://clang.llvm.org/)

---

<p align="center">
made with 💖 by m-carecho
</p>
# gg_compiler(Good Going compiler)

# Contributers :

Glen Martin, 
Gary Mendonca, 
Blessy Varghese

# Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
* [C compiler](https://gcc.gnu.org/)
* [Flex](https://github.com/westes/flex)
* [Bison](https://www.gnu.org/software/bison/)

### Compilation Steps
##### Terminal
```bash
$ lex lex.l
$ yacc -d yacc.y
$ gcc yacc.tab.c -ll -ly 
$ ./a.out
```
```bash
$ gcc -o back back.c
$ ./back



	


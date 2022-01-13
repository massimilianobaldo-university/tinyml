# TinyML
TinyML is a simple interpreter for the core operations described in the metalanguage ML.

The aim of this project is to implement the algorithm of type inference.

This is a porting of the existing repository of my professor [Alvise Sapnò](https://github.com/alvisespano/FL-unipd-2021-22).

The main reason of this porting is to use the dotnet cli for executing the entire program, and not be oblige to use the Visual Studio IDE.

## Installation
You can simply clone the repo using the command `git clone https://github.com/massimilianobaldo/TinyML`.

## Usage
Move inside the directory *"./src/TinyML"*.

Once there, you can use:

* `dotnet build` to compile the interpreter

* `dotnet run` to use the interpreter in interactive mode

* `dotnet run <name-of-file.tml>` to evaluate all the expression inside the *".tml"* file.

## License
[MIT](https://choosealicense.com/licenses/mit/)
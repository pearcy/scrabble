
# _Scrabble_

#### _Test-Driven Development With C# Project, July 15, 2020_

#### By _**Joseph Pearce, Christine Augustine**_

## Description

_A project to introduce the C# language and the .NET Core framework. Create a Scrabble Tester._

### Specs

An application that takes a word and returns the Scrabble score for that word. 

| Behavior | Input | Output |  Completed(Y/N?)  |
| -------- | ----- | ------ | -------- |
|  Console Input/Test        |  A, E, I, O, U, L, N, R, S, T  |      1   |       N   |
|  Console Input/Test        |  D, G  |      2   |       N   |
|  Console Input/Test        |  B, C, M, P   |      3   |       N   |
|  Console Input/Test        |  F, H, V, W, Y       |      4   |       N   |
|  Console Input/Test        |  K  |      5  |       N   |
|  Console Input/Test        |  J, X  |      8  |       N   |
|  Console Input/Test   |  Q, Z  |      10  |       N   |
|  If user enters a word, program returns a letter score  |  DOG |      5  |       N   |


## Setup/Installation Requirements

1. Clone this repository from GitHub.
2. Open the downloaded directory in a text editor of your choice.
  (VSCode, Atom, etc.)
3. To install the REPL dotnet script, run dotnet tool install -g dotnet-script in your terminal.
4. Run the program with the command dotnet build.

## Known Bugs

There are no known bugs at the time of this update.
 
## Technologies Used

* C#
* .NET Core
* Git and GitHub


### License

This software is licensed under the MIT license.

Copyright (c) 2020 **_Joseph Pearce, Christine Augustine_**
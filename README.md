# CONNECT4 MinMax Algorithm

A C++ Connect4 game project that uses **Minimax** and **Alpha-Beta Pruning** algorithms to play the game and compare their performance.

## About the Project

This project was developed as part of an Artificial Intelligence coursework project in C++.

The program allows different AI strategies to play Connect4 against each other and analyzes their performance using different evaluation functions.

## Algorithms Used

* Minimax with Alpha-Beta Pruning
* Alpha-Beta Search

## Features

* 6 × 7 Connect4 game board
* AI-based gameplay
* Three different evaluation functions
* Comparison of different AI search algorithms
* Performance analysis of each algorithm
* Displays the number of nodes generated and expanded
* Measures execution time
* Measures memory usage
* Displays game path length and winning result

## Performance Metrics

The program records:

* Total nodes generated
* Total nodes expanded
* Execution time
* Memory used
* Game path length
* Winning result

## Technologies Used

* C++
* Minimax Algorithm
* Alpha-Beta Pruning
* Artificial Intelligence
* Game Search Algorithms

## How to Run

### 1. Compile the project

Open the project folder in VS Code and run:

```bash
g++ main.cpp -o connect4
```

### 2. Run the program

```bash
./connect4
```

On Windows PowerShell:

```powershell
.\connect4.exe
```

### 3. Select the comparison type

The program provides three comparison options:

1. Minimax Alpha-Beta vs Alpha-Beta Search
2. Minimax Alpha-Beta vs Minimax Alpha-Beta
3. Alpha-Beta Search vs Alpha-Beta Search

Then select an evaluation function from **1, 2, or 3** for each player.

## Example

The program displays the Connect4 board after each move and provides performance information such as:

```text
Total nodes
Nodes expanded
Time spent
Memory used
Game path length
Winning player
```

## Project Structure

```text
CONNECT4-MinMax-Algorithm/
│
├── main.cpp
├── Player.h
└── README.md
```

## Project Purpose

The main purpose of this project is to understand how game-search algorithms work and compare their performance using different evaluation functions in a Connect4 environment.



# IQPuzzle Solver
> Tugas Kecil 1 IF2211 Strategi Algoritma
Penyelesaian IQ Puzzler Pro dengan Algoritma Brute Force
Semester II Tahun 2024/2025

# Description
Program for solving IQ Puzzler Pro in 2D on an MxN board and a 3D pyramid with an MxN base


## Usage

How to run the program

1. Open a terminal or command prompt.
2. Navigate to the folder where the file is stored using the following command:
   - For **Linux** or **Windows** users:
     ```bash
     cd /path/to/folder
     ```

3. Navigate to the `bin` folder with the following command:
   - For **Linux** or **Windows** users:
     ```bash
     cd bin
     ```
  
4. Once in the correct directory, run the following command:  
    ```bash
    java Main
    ```

5. If successful, the program interface will appear:
    ```bash
    Enter file name:
    ```

6. For input, make sure to place the `.txt` file in the `test` folder with the following format: 
    ```bash
    M N P
    S
    block_1_SHAPE
    block_2_SHAPE
    ...
    block_P_SHAPE
    ```
    Example: 
    ```bash
    5 5 7
    DEFAULT
    A
    AA
    B
    BB
    C
    CC
    D
    DD
    EE
    EE
    E
    FF
    FF
    F
    GGG

    ```

    ### Description:

    - **M, N** = board dimensions (MxN)  
    - **P** = number of blocks used  
    - **S** = board type (DEFAULT/PYRAMID)  
    - **block_P_SHAPE** = blocks represented by sequences of letters A–Z
    
## Features

This program can:
1. Solve IQ Puzzler Pro on a 2D board of size MxN.
2. Solve IQ Puzzler Pro by constructing a 3D pyramid.
3. Save the solution as a text file or an image.


## Created by

Henry Filberto Shenelo (13523108)


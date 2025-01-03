
# Huffman and LZW Compression Project

## Overview
This project demonstrates the implementation of two essential lossless data compression algorithms:
1. **Huffman Coding**: An optimal prefix coding algorithm based on the frequency of characters.
2. **LZW Compression**: A dictionary-based compression technique.

The project was implemented as part of the **Data Structures and Algorithms** coursework, showcasing efficient file compression and decompression techniques.

## Features
1. **Huffman Coding**: Utilizes a binary tree structure to generate compressed files.
2. **LZW Compression**: Uses a dynamically built dictionary to encode and decode files.
3. **File Handling**: Processes text files for compression and decompression.
4. **Algorithm Modularity**: Separate modules for Huffman coding, LZW, dictionary management, and file operations.

## File Structure
- `huffman.c`: Implements Huffman Coding.
- `lzw.c`: Implements LZW Compression.
- `dictionary.c`: Provides dictionary management utilities for LZW.
- `file.c`: Contains file handling operations for compression and decompression.
- `array.c`: Auxiliary functions for array management.
- `algorithms.c`: Additional algorithmic utilities.
- `message.txt`: Sample input text file for compression.

## Compilation and Execution
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/huffman-lzw-compression.git
   ```
2. Navigate to the project directory:
   ```bash
   cd huffman-lzw-compression
   ```
3. Compile the code using the provided Makefile:
   ```bash
   make
   ```
4. Run the executables for Huffman or LZW compression:
   ```bash
   ./huffman message.txt compressed_message.txt
   ./lzw message.txt compressed_message.txt
   ```

## Prerequisites
- A C compiler (e.g., GCC).
- Basic knowledge of data structures and algorithms.

## Results
The project demonstrates the efficiency of Huffman and LZW compression algorithms, providing insights into space savings and computational performance.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgements
Special thanks to the Data Structures and Algorithms faculty for guiding this project.

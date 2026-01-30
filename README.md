# CODTECH-C-Internship-T4
COMPANY : CODTECH IT SOLUTIONS
NAME    : OM NARENDRA DOKHE
INTERN ID : CTIS1983
DOMAIN  : C LANGUAGE
DURATION : 4 WEEKS
MENTOR  : NEELA SANTOSH
OUTPUT  :
<img width="1919" height="1079" alt="Image" src="https://github.com/user-attachments/assets/4a00bb64-b3bb-404b-a647-ac56d18d99a5" />

DESCRIPTION :
This task focuses on implementing a basic data compression and decompression tool using the Run Length Encoding (RLE) algorithm in the C programming language. Data compression is an important concept in computer science, used to reduce the size of data for efficient storage and faster transmission. Compression techniques are widely applied in file formats, multimedia systems, networking, and storage optimization.

In this task, a text-based compression tool was developed that reads an input file and generates a compressed output file using the RLE method. Run Length Encoding is one of the simplest forms of lossless compression, where repeated characters are replaced with a single character followed by the count of its repetitions. For example, if the input contains the string AAAABBBCC, the compressed form becomes A4B3C2. This reduces redundancy and minimizes file size when data contains frequent repetitions.

The program provides both compression and decompression functionalities through a menu-driven interface. During compression, the program reads the input file character by character. It counts consecutive occurrences of the same character and writes the character along with its frequency into the compressed file. This approach ensures that repeated sequences are stored efficiently. After reaching the end of the file, the last sequence is also written properly, ensuring correctness of the compression output.

Decompression is the reverse process. The program reads the compressed file, extracts the character and its count, and then reconstructs the original content by writing the character repeatedly into a decompressed output file. This confirms that the compression algorithm is lossless, meaning the original data can be fully recovered without any loss of information.

The implementation was done using standard file handling functions in C such as fopen(), fgetc(), fputc(), fprintf(), and fclose(). Proper error handling is included to ensure that the program behaves correctly if input or output files cannot be opened. The code was written in a modular way with separate functions for compression and decompression, improving clarity and maintainability.

This task was developed and executed on Windows 11 using Visual Studio Code as the programming editor. The GCC compiler from MinGW-w64 was used to compile and run the program inside the VS Code integrated PowerShell terminal. Input and output text files such as input.txt, compressed.txt, and decompressed.txt were used to verify the correctness of the tool.

Run Length Encoding is commonly used in real-world applications where repeated patterns occur frequently, such as simple image compression formats, fax transmission systems, and basic encoding utilities. Although RLE is not suitable for all types of data, it serves as an excellent introduction to compression algorithms and helps in understanding how more advanced compression methods work internally.

This task provides valuable experience in algorithm implementation, file processing, and practical application of encoding techniques. It strengthens problem-solving skills and demonstrates how C programming can be used to build real utilities that handle data efficiently. Overall, this project forms a strong foundation for exploring advanced topics such as Huffman coding, LZW compression, and multimedia encoding systems.

Tools and Platform Used

Language: C
Compiler: GCC (MinGW-w64)
Editor: Visual Studio Code
Operating System: Windows 11

Commands to Compile and Run

Ensure task4.c is present in the folder, then execute:

gcc task4.c -o task4
.\task4.exe

Example usage:

Compression:

Input file: input.txt

Output file: compressed.txt

Decompression:

Input file: compressed.txt

Output file: decompressed.txt

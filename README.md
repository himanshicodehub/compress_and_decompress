# compress_and_decompress
This is a C++ project that shows how to compress and decompress files using multithreading. It splits the file into parts and processes them in parallel to make the operation faster. The code is simple and helps beginners learn how multithreading can improve performance in file handling.

# ⚙️ C++ File Compression & Decompression Tool (Multithreaded)

This is a simple C++ project that shows how to compress and decompress files using **multithreading**. It splits files into smaller chunks and processes them in parallel, making the operation faster and more efficient. This project helps beginners understand how multithreading can improve performance in file handling tasks.

## 🚀 Features

- Compress large files using multiple threads
- Decompress files back to original form
- Faster execution using `<thread>` for parallel processing
- Simple and beginner-friendly code

## 📂 Project Structure

- `main.cpp` – Contains the logic for compression, decompression, and multithreaded execution.
- `README.md` – Project documentation.

## 🛠 Requirements

- C++11 or above
- Any C++ compiler (e.g., g++, clang++)
- Basic understanding of threads and file I/O

## 🔧 How to Compile & Run

```bash
g++ -std=c++11 -pthread main.cpp -o compressor
./compressor

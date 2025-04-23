# cudalab6
This project demonstrates how to compute the square root of each element in a large array using CUDA C++ on a GPU. The results are stored in a separate array, and the execution time is measured for various array sizes.

## 📋 Features

- CUDA kernel to compute square roots (`sqrtf`)
- Measures execution time for:
  - 50,000 elements
  - 500,000 elements
  - 5,000,000 elements
  - 50,000,000 elements
- Runs efficiently on Google Colab using GPU acceleration
- Compares the time for each of the given four guven elements
When N = 50000	Time = 0.1230 ms
When N = 500000	Time = 0.1134 ms
When N = 5000000	Time = 0.2676 ms
When N = 50000000	Time = 1.8581 ms

## Duke IDS 706 Data Engineering mini project 8 
---

[![py_ci](https://github.com/nogibjj/Yuwen-IDS706-miniproject8/actions/workflows/py_cicd.yml/badge.svg)](https://github.com/nogibjj/Yuwen-IDS706-miniproject8/actions/workflows/py_cicd.yml)
[![rs_ci](https://github.com/nogibjj/Yuwen-IDS706-miniproject8/actions/workflows/rs_cicd.yml/badge.svg)](https://github.com/nogibjj/Yuwen-IDS706-miniproject8/actions/workflows/rs_cicd.yml)

---

**Summary**

The objective of Week 8 mini project is to rewrite a Python Script in Rust and compare its performance in running time, memory usage and CPU usage.

---

**Code Location**

You can find the original Python code in the following files:
- `main.py`
- `test_main.py`


Rust code in the following files:
- `src\main.py`
- `src\lib.py`



These functions enable the creation of a simple dataset and the calculation of its descriptive statistics in Python and Rust language.

---

**Python Result**
Make py_test result:
![Alt text](<py_test_result.png>)

---

**Comparison**
![Alt text](<py_result.png>)
![Alt text](<rs_result.png>)

Language | Running Time | CPU Usages | Memory Usage 
--- | --- | --- | --- 
Python | 0.0161s | 16.7% | 95.8% 
Rust | 2.32ms | 5.20% | 85.2% 

The numerical result shows that the Rust performance exceeds Python's running time, CPU usage, and memory usage in this specific case. Overall, Rust looks to be more efficient in this data analysis case.

Python's performance is hindered by its interpreted nature, dynamic typing, and resultant high CPU and elapsed time usage. In contrast, Rust's compiled design, strong typing, and memory control lead to efficient resource usage and shorter execution times, making it a better choice for high-performance and resource-efficient tasks.


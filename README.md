# **StressMate : CP Stress Testor**
---

## 📝 Introduction

In competitive programming, verifying the correctness of your optimized solution is just as important as achieving high performance. Optimized code can often pass sample test cases but fail on hidden or edge cases due to subtle bugs or unhandled scenarios. This is where a **stress tester** proves to be an essential tool.

This project provides a simple yet effective **stress testing framework** designed specifically for competitive programming. It helps automate the process of:

- ✅ Generating random test cases
- ✅ Running both brute-force and optimized solutions
- ✅ Comparing outputs
- ✅ Reporting mismatches for debugging

By continuously testing your solutions against a variety of inputs, this tool helps catch bugs early and boosts your confidence in the correctness of your implementation.

Whether you're practicing, debugging a failing submission, or preparing for contests like Codeforces, AtCoder, or LeetCode, this stress tester will save you time and effort.


---

## 🚀 Getting Started

This project uses a Bash script (`stress_test.sh`) to automate the stress testing process. It compiles all necessary components, repeatedly generates test cases, compares outputs, and stops on the first mismatch or failure.

### ✅ Prerequisites

Before running the script, make sure you have:

- A Unix-based system (Linux or macOS)
- `g++-13` installed and available in PATH
- `timeout` command:
  - On **Linux**, it's usually available by default.
  - On **macOS**, install it via `brew install coreutils` (it will be `gtimeout`)
- All required files:
  - `generator.cpp`: generates test cases
  - `brute.cpp`: brute-force (correct but slow) solution
  - `optimal.cpp`: optimized solution to test
  - `checker.cpp`: custom output comparator

---

### 🏃 How to Run

```bash
# Make the script executable
chmod +x stress_test.sh

# Run the stress tester
./stress_test.sh

```



---

### Some Snapshots


<img width="512" height="294" alt="Screenshot 2025-07-25 at 1 39 15 AM" src="https://github.com/user-attachments/assets/643a7253-88dc-4394-adce-8226a5ed5a70" />

<img width="366" height="81" alt="Screenshot 2025-07-25 at 1 40 37 AM" src="https://github.com/user-attachments/assets/1f08f15b-55fc-420d-8960-fb5f86448d18" />


<img width="320" height="294" alt="Screenshot 2025-07-25 at 1 40 21 AM" src="https://github.com/user-attachments/assets/80e4a855-6b74-4d09-abd8-6c53625cf152" />

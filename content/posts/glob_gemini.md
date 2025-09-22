+++
date = '2025-09-22T17:09:06+08:00'
draft = false
title = 'gemini-cli glob pattern'
+++

# use `glob` to include specific file

```
glob **/*.py, any problems of my project structure
``` 

**Answer**:

✦ Based on the file list, here are a few observations and suggestions for your project structure:

   * Good Separation: You have a src directory for your main application logic, a scripts directory for utility scripts, and a test directory, which is a great
     practice for separating concerns.

   * Root Directory Clutter: There are many Python scripts in your root directory (e.g., simulate_with_formulas.py, generate_formula.py, check_correlation.py).
     Consider moving these into the scripts directory to keep your project's root clean and organized.

   * Testing Coverage: You currently have a single test file (test/main_test.py). For a project of this size, you might want to create more targeted test files
     that correspond to the different modules in your src directory to ensure your code is reliable.

  Overall, the structure is a good start. Cleaning up the root directory and expanding your test suite would be the most impactful improvements.
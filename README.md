# Insertion-Sort
Patika - Veri Yapıları ve Algoritmalar / Insertion Sort

Question 1:

[22, 27, 16, 2, 18, 6] --> Insertion Sort

Step 1: min number = 2 - Change 22 and 2 --> [2, 27, 16, 22, 18, 6]      - n
Step 2: min number = 6 - Change 27 and 6 --> [2, 6, 16, 22, 18, 27]      - n-1
Step 3: min number = 16 - no need to change --> [2, 6, 16, 22, 18, 27]   - n-2
Step 4: min number =18 - Change 22 and 18 --> [2, 6, 16, 18, 22, 27]     - n-3

Big-O: (n*(n-1))/2 = (n^2 - n)/2 ---> O(n^2)

Time Complexity: Average Case

Question 2:

[7, 3, 5, 8, 2, 9, 4, 15, 6] --> First 4 Step based on Selection Sort

Step 1: min = 2 --> [2, 3, 5, 8, 7, 9, 4, 15, 6]
Step 2: min = 3 --> [2, 3, 5, 8, 7, 9, 4, 15, 6] - no need to change
Step 3: min = 4 --> [2, 3, 4, 8, 7, 9, 5, 15, 6]
Step 4: min = 5 --> [2, 3, 4, 5, 7, 9, 8, 15, 6]

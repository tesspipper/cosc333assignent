Teresia Kungu EB3/61581/22 C++

Runtime Analysis
Time Complexity:
The Fibonacci function makes two recursive calls for each input 
n:fibonacci(n−1) and fibonacci(n−2).
This results in an exponential growth of recursive calls, forming a binary tree-like structure. As the number of calls increases exponentially with n, the time complexity is O(2ⁿ).

Space Complexity:
The space complexity is determined by the depth of the recursion stack. Since the maximum depth of recursive calls is n, the call stack can expand up to n frames. Thus, the space complexity is O(n).









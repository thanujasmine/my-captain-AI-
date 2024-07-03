# my-captain-AI-

Here is a simple Python program to generate Fibonacci numbers:

```
def fibonacci(n):
    fib_seq = [0, 1]
    while len(fib_seq) < n:
        fib_seq.append(fib_seq[-1] + fib_seq[-2])
    return fib_seq

n = int(input("Enter the number of terms: "))
print(fibonacci(n))
```

This program defines a function `fibonacci(n)` that generates a list of Fibonacci numbers up to the `n`-th term. The function starts with a list `[0, 1]` and repeatedly appends the sum of the last two numbers to the list until it reaches the desired length. The main part of the program asks the user for the number of terms and prints the corresponding Fibonacci sequence.

For example, if you input `8`, the program will output `[0, 1, 1, 2, 3, 5, 8, 13]`.

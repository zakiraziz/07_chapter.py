I have learn in chapte7 This Thing
For Loop
A loop that repeats a block of code a fixed number of times, often used when the number of iterations is known.

Example in Python:
python
Copy code
for i in range(5):
    print(i)
While Loop
A loop that continues to execute as long as a specified condition is true. Used when the number of iterations is not known beforehand.

Example in Python:
python
Copy code
i = 0
while i < 5:
    print(i)
    i += 1
Do-While Loop (or Do-Until)
Similar to the while loop, but the condition is evaluated after the first iteration, ensuring the loop executes at least once.

Example in C++:
cpp
Copy code
int i = 0;
do {
    cout << i;
    i++;
} while (i < 5);
Nested Loops
A loop inside another loop. The inner loop is executed completely for each iteration of the outer loop.

Example in Python:
python
Copy code
for i in range(3):
    for j in range(3):
        print(f"i={i}, j={j}")
For-Each Loop
Used to iterate over elements in a collection, such as lists or arrays. Common in languages like Python and Java.

Example in Python:
python
Copy code
numbers = [1, 2, 3, 4]
for num in numbers:
    print(num)
Infinite Loop
A loop that never ends on its own, often caused by incorrect logic or intentional design. Usually, it's controlled with break statements.

Example in Python:
python
Copy code
while True:
    print("This is an infinite loop")
    break  # Use this to stop the loop
Each type of loop has specific use cases depending on the problem you're trying to solve.

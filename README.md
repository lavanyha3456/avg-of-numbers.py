# avg-of-numbers.py

count = int(input("Enter the count of numbers: "))
i = 0
sum = 0
for i in range(count):
    x = int(input("Enter an integer: "))
    sum = sum + x
avg = sum/count
print(" The average is: ", avg)



output:
Enter the count of numbers: 7
Enter an integer: 3
Enter an integer: 7
Enter an integer: 9
Enter an integer: 9
Enter an integer: 5
Enter an integer: 3
Enter an integer: 3
The average is:  5.571428571428571


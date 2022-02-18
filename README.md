# ass-1-18-02-22
#Write a program to print count of n prime numbers.
num=int(input("Enter range:"))

count=0

print("Prime numbers:",end=' ')

for n in range(2,num):

    for i in range(2,n):

        if(n%i==0):

            break

    else:
        count=count+1
        
print(count)

output:
Enter range:15
Prime numbers:6

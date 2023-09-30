# break.py

#program to demonstrate use of  break  statement
num=0
for num in range(10):
    num=num+1
    if num==6:
        break
    print("num has value",num)
print("encounterd break ! out of loop")

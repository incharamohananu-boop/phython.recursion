# phython.recursion
def add(a,b):  
    print(a+b)
add(1,2)
#difference between print and return
def add(a,b):    #return used when assigning  variables   to other variables
    return(a+b)
c=add(1,2)
print(c)

#ensureing that it works on every variables
def add(*a):
    return(a)
c=add(1,2,3,4,5)
print(c)
#print sum of numbers
def add(*numbers):
    return sum(numbers)
print(add(3,4,5))

def totalsum(*numbers):
    result=0
    for num in numbers:
        result+=num
    return result
print(totalsum(1,2,3,4,5))

students={
    "keerthi":1234,
    "ankith":2345
}
print(students["keerthi"])

students=[
    {"name":"chandhana","marks":100},
    {"name":"keerthi","marks":10},
    {"name":"anjali","marks":123}
]
marks=[100,10,123]    #marks sorting
marks.sort()
print(marks)

marks.sort(reverse=True)
print(marks)

#for students
students.sort(key=lambda x:x["marks"])
print(students)

students.sort(key=lambda x:x["marks"],reverse=True)
print(students)


#recursion
#it can be breakdown into simple problems


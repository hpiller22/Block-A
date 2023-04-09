# Block-A
def top():
    SIZE = 3  
    
#print the top 5 lines of Block A
    print(" "*(SIZE*4)+"X"*(SIZE*6+1)) #line 1
    print(" "*(SIZE*4)+"X"*(SIZE*6+1)) #line 2
    print(" "*(SIZE*4)+"X"*SIZE+" "*(SIZE*4+1)+"X"*SIZE) #line 3
    print(" "*(SIZE*4)+"X"*(SIZE*3)+" "+"X"*(SIZE*3)) #line 4
    print(" "*(SIZE*4)+"X"*(SIZE*3-1)+"   "+"X"*(SIZE*3-1)) #line 5
top()

#print lines 6-8 of Block A
def blueshaded():
    SIZE = 3
    for i in range(3):
        print(" "*(SIZE*5-i)+"X"*SIZE+" "*SIZE+"*"*(2*i+1)+" "*SIZE+"X"*SIZE)
blueshaded()

#print lines 9-11 of Block A
def greenshaded():
    SIZE = 3
    for i in range(3):
        print(" "*(SIZE*4-i)+"X"*SIZE+" "*SIZE+"*"*SIZE+" "*(2*i+1)+"*"*SIZE+" "*SIZE+"X"*SIZE)
greenshaded()

#print lines 12-13 of Block A
def middle():
    SIZE = 3
    for i in range(2):
        print(" "*(SIZE*3-i)+"X"*SIZE+" "*SIZE+"*"*(2*i+13)+" "*SIZE+"X"*SIZE)
middle()

#print lines 14-16 of Block A
def yellowshaded():
    SIZE = 3
    for i in range(3):
        print(" "*(SIZE*2-i+1)+"X"*SIZE+" "*SIZE+"*"*SIZE+" "*(2*i+11)+"*"*SIZE+" "*SIZE+"X"*SIZE)
yellowshaded()

#print line 17 of Block A
def bottomline():
    SIZE = 3
    for i in range(1): 
        print(" "*(4)+"X"*SIZE+" "*SIZE*4+" "*(2*i+17)+"X"*SIZE)
bottomline()

#print line 18-22 of Block A
def bottom(): 
    SIZE = 3
    print(" "*(SIZE*2-5)+"X"*(SIZE*12+5)) 
    print(" "*(SIZE*2-5)+"X"*(SIZE*12+5)) 
    print(" "*(SIZE*1-2)+"X"*SIZE+" "*(SIZE*4+23)+"X"*SIZE)
    print(" "*(SIZE*2-5)+"X"*(SIZE*12+5)) 
    print(" "*(SIZE*2-5)+"X"*(SIZE*12+5)) 
bottom()


def top():
    SIZE = 4 
#print the top 5 lines of Block A
    print(" "*(SIZE*4)+"X"*(SIZE*6+1)) #line 1
    print(" "*(SIZE*4)+"X"*(SIZE*6+1)) #line 2
    print(" "*(SIZE*4)+"X"*SIZE+" "*(SIZE*4+1)+"X"*SIZE) #line 3
    print(" "*(SIZE*4)+"X"*(SIZE*3)+" "+"X"*(SIZE*3)) #line 4
    print(" "*(SIZE*4)+"X"*(SIZE*3-1)+"   "+"X"*(SIZE*3-1)) #line 5
top()

#print lines 6-8 of Block A
def blueshaded():
    SIZE = 4
    for i in range(3):
        print(" "*(SIZE*5-i)+"X"*SIZE+" "*SIZE+"*"*(2*i+1)+" "*SIZE+"X"*SIZE)
blueshaded()

#print lines 9-11 of Block A
def greenshaded():
    SIZE = 4
    for i in range(3):
        print(" "*(SIZE*4-i+1)+"X"*SIZE+" "*SIZE+"*"*(3)+" "*(2*i+1)+"*"*(3)+" "*SIZE+"X"*SIZE)
greenshaded()

#print lines 12-13 of Block A
def middle():
    SIZE = 4
    for i in range(2):
        print(" "*(SIZE*3-i+2)+"X"*SIZE+" "*SIZE+"*"*(2*i+13)+" "*SIZE+"X"*SIZE)
middle()

#print lines 14-16 of Block A
def yellowshaded():
    SIZE = 4
    for i in range(3):
        print(" "*(SIZE*2-i+4)+"X"*SIZE+" "*SIZE+"*"*(3)+" "*(2*i+11)+"*"*(3)+" "*SIZE+"X"*SIZE)
yellowshaded()

#print line 17 of Block A
def bottomline():
    SIZE = 4
    for i in range(1): 
        print(" "*(SIZE*2-i+1)+"X"*SIZE+" "*SIZE*4+" "*(2*i+15)+"X"*SIZE)
bottomline()

#print line 18-22 of Block A
def bottom():
    SIZE = 4
    print(" "*(SIZE*2-3)+"X"*(SIZE*11+4)) 
    print(" "*(SIZE*2-3)+"X"*(SIZE*11+4)) 
    print(" "*(SIZE*1+1)+"X"*SIZE+" "*(SIZE*4+24)+"X"*SIZE)
    print(" "*(SIZE*2-3)+"X"*(SIZE*11+4)) 
    print(" "*(SIZE*2-3)+"X"*(SIZE*11+4)) 
bottom()

def top():
    SIZE = 5
#print the top 5 lines of Block A
    print(" "*(SIZE*4)+"X"*(SIZE*6+1)) #line 1
    print(" "*(SIZE*4)+"X"*(SIZE*6+1)) #line 2
    print(" "*(SIZE*4)+"X"*SIZE+" "*(SIZE*4+1)+"X"*SIZE) #line 3
    print(" "*(SIZE*4)+"X"*(SIZE*3)+" "+"X"*(SIZE*3)) #line 4
    print(" "*(SIZE*4)+"X"*(SIZE*3-1)+"   "+"X"*(SIZE*3-1)) #line 5
top()

#print lines 6-8 of Block A
def blueshaded():
    SIZE = 5
    for i in range(3):
        print(" "*(SIZE*5-i)+"X"*SIZE+" "*SIZE+"*"*(2*i+1)+" "*SIZE+"X"*SIZE)
blueshaded()

#print lines 9-11 of Block A
def greenshaded():
    SIZE = 5
    for i in range(3):
        print(" "*(SIZE*4-i+2)+"X"*SIZE+" "*SIZE+"*"*(3)+" "*(2*i+1)+"*"*(3)+" "*SIZE+"X"*SIZE)
greenshaded()

#print lines 12-13 of Block A
def middle():
    SIZE = 5
    for i in range(2):
        print(" "*(SIZE*3-i+4)+"X"*SIZE+" "*SIZE+"*"*(2*i+13)+" "*SIZE+"X"*SIZE)
middle()

#print lines 14-16 of Block A
def yellowshaded():
    SIZE = 5
    for i in range(3):
        print(" "*(SIZE*2-i+7)+"X"*SIZE+" "*SIZE+"*"*(3)+" "*(2*i+11)+"*"*(3)+" "*SIZE+"X"*SIZE)
yellowshaded()

#print line 17 of Block A
def bottomline():
    SIZE = 5
    for i in range(1): 
        print(" "*(SIZE*2-i+4)+"X"*SIZE+" "*SIZE*4+" "*(2*i+13)+"X"*SIZE)
bottomline()

#print line 18-22 of Block A
def bottom():
    SIZE = 5
    print(" "*(SIZE*2-1)+"X"*(SIZE*10+3)) 
    print(" "*(SIZE*2-1)+"X"*(SIZE*10+3)) 
    print(" "*(SIZE*1+4)+"X"*SIZE+" "*(SIZE*4+23)+"X"*SIZE)
    print(" "*(SIZE*2-1)+"X"*(SIZE*10+3)) 
    print(" "*(SIZE*2-1)+"X"*(SIZE*10+3)) 
bottom()


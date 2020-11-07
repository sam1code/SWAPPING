# SWAPPING
A simple algorithm for Swapping of any number of variables without taking any extra variable.
STEP-1 
Declare the variables [Let a,b,c,d,…..,n   So here we have to swap ‘n’ number of variables ] and take input in all variables.
STEP-2
Firstly add all the values of all the variables which you want to swap in one variable[ Let suppose in ‘a’ you can choose any variable
a=a+b+c+d+….+n
]
STEP-3
Now choose that variable where you want to store ‘a’ [ value of a will be transferred to that variable, Let suppose ‘b’ ]
STEP-4
Use the formula b=a-(b+c+d+…..+n)
Now value of a stored in ‘b’.
Now choose the variable where you want to store ‘b’.[Let suppose ‘c’]
c= a-(b+c+d+…..+n)
Here the golden formula which is used for every swap is k=a-(b+c+d+….+n)
STEP-5
At last the last variable in which we swapped have to swap that value of the variable to that variable which you choosed in step number 2.
[a= a-(b+c+d+…..+n) ] 
STEP-6
EXIT.


/--------Examples------\
Swap 5 numbers like 
i.	a=10,b=20,c=30,d=40,e=50       a=20,b=30,c=40,d=50,e=10
ii.	a=10,b=20,c=30,d=40,e=50       a=30,b=40,c=50,d=10,e=20
iii.	a=10,b=20,c=30,d=40,e=50       a=50,b=10,c=20,d=30,e=40
Answers
i.	a=a+b+c+d+e                                             ii.      a=a+b+c+d+e
e=a-(b+c+d+e)					    d=a-(b+c+d+e)
d=a-(b+c+d+e)					    b=a-(b+c+d+e)
c=a-(b+c+d+e)				              e=a-(b+c+d+e)
b=a-(b+c+d+e)					    c=a-(b+c+d+e)
a=a-(b+c+d+e) 					    a=a-(b+c+d+e)
iii. 	     a=a+b+c+d+e
	     b=a-(b+c+d+e)
	     c=a-(b+c+d+e)
	     d=a-(b+c+d+e)
	     e=a-(b+c+d+e)
	     a==a-(b+c+d+e)


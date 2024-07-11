# Calculator using python
n1=float(input("Enter  value 1:"))
n2=float(input("Enter  value 2:"))
ch=input("Choose sign")
if (ch=='+'):
    print("Addition:",n1+n2)
elif (ch=='-'):
    print("Substraction:",n1-n2)
elif (ch=='*'):
    print("Multiply:",n1*n2)
elif (ch=='/'):
    print("Division:",n1/n2)
elif (ch=='%'):
    print("Module:",n1%n2)
else:
    print("Enter valid sign")

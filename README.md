# Algebra-Call_Borromeo_Grace-Antonette---9-24-2026
----- MAIN PROGRAM -----
def main()
    print("ALGEBRA & CALCULUS 1")
  print (FIND THE VALUE OF (X)= FORMULA:
F(x)=(ax^2+bx+c) ")

  while True:
    print("\n1. Solve a linear equation9ax + b =c)")
    print("2. Solve a quadratic equation (ax^2 +bx +c=0)")
    print("3. Evaluate f(x)= ax^ 2+ bx + c ")
    print("4. Find the devative f'(x) at a Point")
    print("5. Estimate limit as x approches a value")
    print("6. Compute definite integral of f(x)")
    print("7. Quit")

    choice= input("nEnter your choice (1-7):")

    if choice == "1"
       # 1. Linear Equation: ax + b = c
       a= float(input(input("Enter a:"))
       b= float(input (Enter b:"))
       c= float(input(Enter c:"))
       if a == 0:
        print("No solution or infinite solution(a=0)")
       else: 
        x= (c-b)/a
        print(f"Solution:x ={x:.4f}")

       elif choice == "2":
        a = float(input(Enter a: )")
        b = float(input (Enter b:)")
        c = float(input ( Enter c:)")
        disc = b**2-*a*c
        if disc>0:
            x1= (-b + math.sqrt(disc))/(2*a)
            x2= (-b- math.sqrt(disc))/(2*a)
            print(f"One reel root: x1 ={x1:.4f})
        else:
            real = -b/ (2*)
            imag= math.sqrt(-disc) / (2*a)
            print(f"One real root: x = {x:.4f})+{imag:. 4f}i")
        
        elif choice 
        print(" Example: f(x)= x2 + 3x-1")
        a= float(input("Value x approches:"))
        def f(x) : return x **2 + 3*

# tip-calculator
print("Welcome to the tip calculator.")
total_bill = input("What was the total bill? $")
percent = input("What percentage tip would you like to give? 10 , 12 or 15 ?")
people = input("How many people to split the bill? ")
x = float(total_bill)
y = float(percent)
z = int(people)
tip = round((x/z)*(1+y/100))
print(f"Each person should pay: ${tip}")

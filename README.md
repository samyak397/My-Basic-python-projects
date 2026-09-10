# My Family Expense calculator Project.

Income = float(input("Write your Income: "))
Rent = float(input("Write your Rent: "))
Groceries = float(input("Write your groceries expense: "))
Remaining_money = float(input("Side expenses: "))

print("Total expense is:", Rent + Groceries + Remaining_money)

print("Remain after rent:", Income - Rent)
print("Remain after Groceries:", Income - Groceries)
print("Remain after Side expenses:", Income - Remaining_money)
print("Remaining money left over:", Income - Rent - Groceries - Remaining_money)

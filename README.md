# Python-5
# Problem 5: Employee Bonus

# Get user input for employee information
last_name = input("Enter employee last name: ")
salary = float(input("Enter employee salary: "))
job_level = int(input("Enter job level: "))

# Determine bonus rate based on job level
if job_level >= 10:
    bonus_rate = 0.25
elif 5 <= job_level <= 9:
    bonus_rate = 0.20
else:
    bonus_rate = 0.10

# Calculate bonus
bonus = salary * bonus_rate

# Display results
print(f"\nEmployee Last Name: {last_name}")
print(f"Bonus: ${bonus:.2f}")

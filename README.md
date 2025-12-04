# RENT-CALCULATOR-
I learn how to make rent calculator with tthe help of python. Hope, you find it useful 👍  and give me some suggestions and some useful tips for improving in python and also as to get ready for job.

# Rent Calculator

print("Let's print Rent Calculator now: ")

rent= int(input("Enter the amount of rent here: "))
food= int(input("Enter the amount of food ordered: "))
electricity_spend= int(input("Enter the total of electricity spend: "))
charge_per_unit= int(input("Enter the charge per unit: "))
persons= int(input("Enter the number of persons living in the room/flat: "))

total_bill= electricity_spend*charge_per_unit
total_amount_spent= rent+food+total_bill
rent_amount_per_person= total_amount_spent//persons

print(f"Each person will pay: Rs.{rent_amount_per_person}.")

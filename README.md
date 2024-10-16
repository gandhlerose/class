#Nested Decision Structures
#Prgram 3-5

MIN_SALARY = 30000.0
MIN_YEARS = 2

salary = float(input("Enter your annual salary"))
years_on_job = int(input("Enter years on the job"))

if salary >=MIN_SALARY:
    if years_on_job >= MIN_YEARS:
      print("You meet the requirement for number of employment years")
      print("You have worked",years_on_job, "and the minimum requirement is ", MIN_YEARS)
      print("You qualify for the loan")
    else:
      print("You do not meet the requirement for number of employment years")
      print("You have been employed ", years_on_job,"year(s)")
      print("You must be employed a minimum of", MIN_YEARS, " years to qualify")
      print("You do not qualify for the loan")
else:
      print("Your current salary is $", format(salary, '.2f'))
      print("You must earn a minimum of $", format(MIN_SALARY, '.2f'), "to qualify for the loan")

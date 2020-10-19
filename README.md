#Keegan McCormack
#This system will be on choosing a payment system at Mathnasium Tutoring Center.
#I used radius.com which is the website we use to give us the prices of the Payment plans.
#It could also be used for the cost of private lessons.
#Also to see how many employees are needed to come in per hour.
Yearly_plan=279
#This is how much you would pay monthly not for the whole year but you must pay for a whole year
Monthly_plan=329
#This is for people per year
print("Choose your Matnasiusm Plan"):
print("Yearly Plan is 279 per month and: $",Yearly_plan*12,"for the whole year"):
print("Or you can do it month by month and pay: $"+Monthly_plan)
input("Type in Monthly plan or Yearly plan to choose: "
if int=Monthly Plan:
    num1=input("How many students will you like to enroll:"))
    Monthlyper=110-10*num1
#We give a small discount for the people that enroll more than 1 student about an additional 10 percent off the whole
#per student
    result= 329*num1%Monthlyper
    print("You will be paying: $"+result,"per month.")
if int=Yearly plan:
    num1 = input("How many students will you like to enroll:"))
    Monthlyper = 110 - 10 * num1
    result = 279 * num1 % Monthlyper
    Yearly_result=result*12
    print("You will be paying: $"+result,"per month"):
    print("And you will be paying: $"+Yearly_result,"every year")
#We also provide private lessons for different students for those who need one on one help
private=80
num2=input("How many private lessons would you like for the month:")
private_cost=int(num2)*80
print("You are paying: $"+private_cost,"this month on private lessons.")
#This will help decide how many instructors are needed to schedule for the amount students coming in(Per hour)
instruct1=input("How many students are coming in from 2:30-3:30:")
private_lesson1=input("How many private lessons are coming in from 2:30-3:30:")
    reg_num1=(int(instruct)-int(private_lesson))//4
    total_num1=reg_num+int(private_lesson)
    print("You will need "+total_num1+"instructors from 3:30-4:30")
instruct2=input("How many students are coming in from 3:30-4:30:")
private_lesson2=input("How many private lessons are coming in from 2:30-3:30:")
    reg_num2=(int(instruct2)-int(private_lesson2))//4
    total_num2=reg_num2+int(private_lesson2)
    print("You will need "+total_num2+"instructors from 3:30-4:30")
instruct3=input("How many students are coming in from 4:30-5:30:")
private_lesson3=input("How many private lessons are coming in from 4:30-5:30:")
    reg_num3=(int(instruct3)-int(private_lesson3))//4
    total_num3=reg_num3+int(private_lesson3)
    print("You will need "+total_num3+"instructors from 4:30-5:30")
instruct4=input("How many students are coming in from 5:30-6:30:")
private_lesson4=input("How many private lessons are coming in from 5:30-6:30:")
    reg_num4=(int(instruct4)-int(private_lesson4))//4
    total_num4=reg_num4+int(private_lesson4)
    print("You will need "+total_num4+"instructors from 5:30-6:30")
instruct5=input("How many students are coming in from 6:30-7:30:")
private_lesson5=input("How many private lessons are coming in from 6:30-7:30:")
    reg_num5=(int(instruct5)-int(private_lesson5))//4
    total_num5=reg_num5+int(private_lesson5)
    print("You will need "+total_num5+"instructors from 6:30-7:30")
instruct6 = input("How many students are coming in from 6:30-7:30:")
private_lesson6 = input("How many private lessons are coming in from 6:30-7:30:")
    reg_num6 = (int(instruct6) - int(private_lesson6)) // 4
    total_num6 = reg_num6 + int(private_lesson6)
    print("You will need " + total_num6 + "instructors from 6:30-7:30")
###This will be used for grading Assessments###
Initial_Score=input("What was the Initial Assessments score:")
New_Score=input("What is the current score:")
if Initial_Score>=80:
    print("Great work give the next Assessment!")
if Initial_Score==100
    print("Give them 100 punch cards!")
if Initial_Score!=100
    print("Better luck next time")
if Initial_Score<80:
    print("Have them try again.")
elif New_Score>=80:
    print("Just needed to see it twice")
else:
    print("Have an instructor go over contents with student.")
if Initial_Score>New_Score:
    print("Contact parent as they have not improved")
elif Initial_Score==New_Score:
    print("Contact parent as they have not improved")
elif Initial_Score<New_Score:
    then improvement=New_Score-Initial_Score
    print("They have improved by "+""+"percent")
assessment=100
while assessment>80
    print(assessment)
    assessment=assessment-1
print("Give them the next Assessment")
for Initial_Score in range(80,101)
    print("Give them the next Assessment")
else:
    print("Have them try a new one")
if Initial_Score>=80 and New_Score>=80
    print("Give them a treat and have them work on some Mathnasium Material")
elif Initial_Score>=80 or New_Score>=80
    print("Good job you have gone up a grade level!")
else:
    print("Have them brush up on some of the work they are getting wrong.")
if not Initial_Score<New_Score:
    print("They have lost understanding of the subjects")

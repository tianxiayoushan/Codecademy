# Codecademy
#RBB Training Quiz or Test

print('Welcome to RBB Traing Quiz!\nPlease read questions carefully.')
from time import sleep
from random import randint
sleep(1)
user_name=input("Please type your name: ".title())
sleep(1)
print("Quzi Begining!")
sleep(2)
#Adding questions into dictionary "quiz"
quiz = {
    "Question 1" : "What kind of business does Royal Business Bank doing?\nA: Commercial Banking;\nB: Risk Management;\C: Financial Institution\D:Good business",
    "Question 2" : "Which one of following is not correct?"
}
#Creat dictionary of correct answers
correct_answer = {
    "Question 1" : "B"
}

#def score
def score(count):

#Choice and print out question
for question in quiz:
    print(question)

user_choice = str(input("Type your Choice: ").upper())

count = 0
for answer in correct_answer:
    if answer == user_choice
        count += 1
    else:
        count += 0
    return count

#Random Questions
#random_question = quiz{randint(0, len(quiz) - 1)}





#def grade
def get_letter_grade(score):
  if score >= 90:
    return "A"
    print("Congraduation!")
  elif score >=80:
    return "B"
  elif score >=70:
    return "C"
  elif score >=60:
    return "D"
  else:
    return "F"
#Show the result
print("The quiz is end. Please wait for your manager.")
code = "risk management"
manager_input = str(input().lower())
if code == manager_input
    print(user_name\n + "Grade: "+get_letter_grade()+ " " + "Socre: " + score())
    print("Please record the grade and score on evaluation sheet.\n Thanks you!")

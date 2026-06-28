# codesoft.python programming

1 .##CODE FOR PASSWORD GENERATOR

import random import string

print("===password generator==") length = int(input("enter password length:")) print(\nchosr password type:") print("1.letters only") print("2. letters + numbers") print("3. letters + numbers + charactrers")

choice = input("enter your choice(1/2/3):")

if choice =="1": characters = string.ascii_letters elif choice =="2": characters = string.ascii_letter +string.digits elif choice =="3": characters = string.ascii_letter + string.digits+ string.punctuation else: print("invalid choice!") exit() password =" "

for i in range (length): password += random.choice(characters) print("\ngenerate password:",password)

CODE FOR SIMPLE CALCULATOR
print("simple calcultor") num1 = float(input("enter first number:") num2 = float(input("enter a second number:")

operation = input("enter operator (+,-,*,/)")

if operation =="+" print("result = ",num1+num2)

elif operation =="-" print('result =",num1-num2)

elif operation =="" print("result= ",num1num2)

elif operation == "/" if num2!=0: print("result=",num1/num2) else: print("cannot divid by zero")

else: print("invalid operation"0

3.. CODE ROCK-PAPER-SCISSOR GAME

import random choics =["rock","paper","scissor")

user_score = 0 computer_score = 0

print("=== rock paper scissor game ===")

while true print("\nchoose one: rock,paper,scissor") user =input("your choice:").lower()

if user not in choices: print('invalid choices! please try again") continue

computer = random.choice(chioces)

print("you chose:" user) print("computer chose:"computer)

if user == computer print ("it is a tie")

elif(user == "rock" and computer =="scissor)or\ (user =='paper" and computer =="rock") or
(user == "scissor" and computer =="paper"):

print("you won!")
user_score+=1
else: print("comuter wins!") computer_score+=1

print("\nscore") print("you:",user_score) print("computer:",computer_score)

play_again = input('\nDo you want to play again?(yes/no):").lower()

if paly_again!="yes": print(\nfinal score") print("you:",user_score) print("computer:",computer_score) print("thanks for playing !") break

import random
import sys

number1= (random.random() * 33)//1
number1= int(number1)

def guess_num(number):
    print("Guess a number between 1 and 32:")
    user_input = input()
    guess = int(user_input)
    if guess==number:
        print("Correct!")
        return False
    elif guess<number:
        print("Your guess is too low")
        return True
    elif guess>number:
        print("Your guess is too high")
        return True

print("Round One:")
i=0
while True:
    guess_num(number1)
    i+=1
print("Number of guesses {}".format(i))

print("The number was {}" .format(number1))

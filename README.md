# computerquizgame
Beginner level project showing a computer game on Jupyter Notebook

def cpu_quiz():
    print("Welcome to my CPU quiz!")
    playing = input("Do you want to play? ").lower()
    
    if playing == "yes": 
        print("Great! Let's play")
        score = 0

    else: 
        print("Okay, maybe next time!")
        return  # This will stop the function here

    answer = input("What does CPU stand for? ").lower()
    if answer == "central processing unit":
        print("Well done! That is the correct answer")
        score = score + 1
    else:
        print("Unfortunately that's not correct")

    answer = input("What does GPU stand for? ").lower()
    if answer == "graphics processing unit":
        print("Well done! That is the correct answer")
        score = score + 1
    else:
        print("Unfortunately that's not correct")

    answer = input("What does RAM stand for? ").lower()
    if answer == "random access memory":
        print("Well done! That is the correct answer")
        score = score + 1
    else:
        print("Unfortunately that's not correct")

    answer = input("What does PSU stand for? ").lower()
    if answer == "power supply unit":
        print("Well done! That is the correct answer")
        score = score + 1
    else:
        print("Unfortunately that's not correct")

    print("You got " + str(score) + " questions correct out of 4!")
    print("You got " + str((score/4) * 100) + "%.")

cpu_quiz()

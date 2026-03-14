questions = [
    ["Who is the Virat Kohali?", "We wrestler", "Cricketer", "Actor", "Astronaut", 2],
    ["What is The Capital Of India?", "Berlin", "New Delhi", "Maharahsra", "Hydrabad", 2],
    ["Which Planet is Known as Red Planet?", "Earth", "Venus", "Mars", "Jupyter", 3],
    ["What is The largest Mammal?", "Shark", "Blue whell", "Elephant", "Girafee", 2],
    ["What is The Square Root of 18?", "180", "600", "476","324", 4],
    ["Which is The Smallest Country in The World?", "San Marino", "Vatican City", "MOnaco", "Liechtenstein", 2],
    
]

prizes = [100000, 320000, 400000, 45000, 50000, 600000]

i = 0
for question in questions:
    
    print(question[0])
    print(f"a. {question[1]}")
    print(f"b. {question[2]}")
    print(f"c. {question[3]}")
    print(f"d. {question[4]}")
    
    # check whether the answer is correct or not
    
    a = int(input("enter your answer: 1 for a, 2 for b, 3 for c, 4 for d\n"))
    if (question[5] == a):
        print("correct answer")
    else:
        print(f"Incorrect the correct answer was {question[5]}")
        print("Better luck next time!")
        break
    
    sum += prizes[i]
    print("You won {prizes[i]}")
    i +=1

    

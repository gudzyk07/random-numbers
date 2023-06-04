import random

def generate_random_code():
    for _ in range(10):
        num = random.randint(1, 100)
        if num % 2 == 0:
            print(f"{num} is even")
        else:
            print(f"{num} is odd")

generate_random_code()

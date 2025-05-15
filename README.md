import random
def super_extreme_random():
    if random.randint(1, 10**6) == 1:
        if random.randint(1, 10**6) == 1:
            for _ in range(264):
                if random.randint(1, 10**6) != 1:
                    return random.randint(1, 999)  
            return 777
    return random.randint(1, 999)  
for _ in range(10):
    print(super_extreme_random())

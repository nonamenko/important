import random

def guess_the_number():
    print("Ласкаво просимо до гри 'Вгадай число'!")
    print("Комп'ютер загадав число від 1 до 100. Спробуйте вгадати його!")

    number_to_guess = random.randint(1, 100)
    attempts = 0

    while True:
        try:
            guess = int(input("Введіть число: "))
            attempts += 1

            if guess < number_to_guess:
                print("Занадто мало! Спробуйте ще раз.")
            elif guess > number_to_guess:
                print("Занадто багато! Спробуйте ще раз.")
            else:
                print(f"Вітаю! Ви вгадали число {number_to_guess} за {attempts} спроб(у/и).")
                break
        except ValueError:
            print("Будь ласка, введіть коректне число.")

if __name__ == "__main__":
    guess_the_number()

import math


def mean_calc(x, y):
    sum_of_numbers, count_of_numbers = 0, 0
    for i in range(x, y + 1):
        sum_of_numbers += i
        count_of_numbers += 1

    print("Среднее:", round(sum_of_numbers / count_of_numbers, 2))
    print("бывает")
test
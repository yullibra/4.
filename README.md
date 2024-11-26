# 4.
data = [4, -30, 30, 100, -100, 123, 1, 0, -1, -4]

if __name__ == '__main__':
    # Сортировка без использования lambda-функции
    result = sorted(data, key=abs, reverse=True)
    print(result)

    # Сортировка с использованием lambda-функции
    result_with_lambda = sorted(data, key=lambda x: abs(x), reverse=True)
    print(result_with_lambda)

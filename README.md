def count_even_odd(numbers):
    even_count = sum(1 for n in numbers if n % 2 == 0)
    odd_count = len(numbers) - even_count
    return even_count, odd_coun

if __name__ == "__main__":
    nums = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
    even, odd = count_even_odd(nums)
    print(f"Even numbers: {even}, Odd numbers: {odd}")


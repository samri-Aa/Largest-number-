# Largest-number-
def find_largest(numbers):
    if len(numbers) == 0:
        return None
    
    largest = numbers[0]
    
    for num in numbers:
        if num > largest:
            largest = num
nums = [10, 45, 23, 67, 89, 2]
print("Largest number:", find_largest(nums))

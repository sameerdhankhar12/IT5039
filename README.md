# IT5039
def print_star_pattern(n):
    for i in range(n):
        print(' ' * (n - i - 1) + '*' * (2 * i + 1))

n = 5  # Change this value for a larger or smaller star
print_star_pattern(n)

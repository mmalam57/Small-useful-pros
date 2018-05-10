# Small-useful-pros
Multiple useful 

SQUARE ALL
nums = [1,2,3,4,5,6]
square_all = map(lambda nums : nums **2, nums)
print(list(square_all))
[1, 4, 9, 16, 25, 36]

# Concatenate
add_bangs = (lambda a: a + '!!!'), and the function call is: add_bangs('hello')

## Filter () and Lambda ()
fellowship = ['frodo', 'samwise', 'merry', 'aragorn', 'legolas', 'boromir', 'gimli']

Use filter() to apply a lambda function over fellowship: result
result = filter( lambda member : len(member) > 6, fellowship)

Convert result to a list: result_list
result_list = list(result)

Convert result into a list and print it
print(result_list)

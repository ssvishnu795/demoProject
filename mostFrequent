def make_dict(letters):
    dictionary = []
    for letter in letters:
        dictionary[letter] = 1+ dictionary.get(letter,0)
    return dictionary

def most_frequent(word):
    letters = [letter.lower() for letter in word if letter.isalpha()]
    dict = make_dict(letters)
    res = []
    for key in dict:
        res.append((dict[key],key))
    res.sort(reverse=True)
    for count,val in res:
        print(count,val)

most_frequent('abcdefgascerfev')

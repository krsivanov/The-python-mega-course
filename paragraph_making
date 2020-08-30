def string_format(string):
    if "where" in string.lower() or "what" in string.lower() or "how" in string.lower() or 'when' in string.lower():
        string = string+"? "
    else:
        string = string + ". "
    string = string.title()

    return string

result =''
user_input = input("Say something: ")

while user_input !="\End":
    result += string_format(user_input)
    user_input = input("Say something:")

print(result)

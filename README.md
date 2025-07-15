# Function.11
Direct recursive in function
def string(s):
    if len(s)==0:
        return s
    return string(s[1:])+[0]
text = input("entr a word : ")
print(string(text))
    

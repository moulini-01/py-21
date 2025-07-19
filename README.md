# py-21
comparing stirngs using python
def compare_string(s1,s2):
    if len(s1)!=len(s2):
        return "not equal"
    for i in range(len(s1)):
        if (s1[i]!=s2[i]):
            return "not equal"
    else:
            return "equal"
print(compare_string("cat","cat"))

# Alphabet
#Rhina G. Pagaran

def string(s):
  my_string = input ("Enter String:")
  d={"UPPER_CASE":0, "LOWER_CASE":0}
  for c in s:
        if c.isupper():
           d["UPPER_CASE"]+=1
        elif c.islower():
           d["LOWER_CASE"]+=1
        else:
           pass
  print ("No. of Upper case characters : ", d["UPPER_CASE"])
  print ("No. of Lower case Characters : ", d["LOWER_CASE"])
  
string('the quick brown fox jumps over the lazy dog')

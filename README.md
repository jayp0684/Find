# Find

#str = "X-DSPAM-Confidence:0.8475"

#Use find and string slicing to extract the portion of the 
#string after the colon character and then use the float function 
#to convert the extracted string into a floating point number.

#results should include what index position the colon is 
#in as well as the float value

str = "X-DSPAM-Confidence:0.8475"

ipos = str.find(":")
print(ipos)
piece = str[ipos+2:]
print(piece)
value = float(piece)
print(value)
#print(value + 42.0)

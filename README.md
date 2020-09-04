# area-of-circle-and-extension
#program to find area of circle in Python using π
PI = 3.14
r = float(input("Enter the radius of the circle: "))
area = PI * r * r
print("%.2f" %area)







#print the extension 

fn= input("Enter Filename: ")

f = fn.split(".")

print ("Extension of the file is : " + f[-1])

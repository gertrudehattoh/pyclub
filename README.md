# pyclub
#this code finds what is a leap year

#finding the leap year
data = input('Enter a year: ' )
def leap_year(data):
   if data%4 ==0:
    if data%100== 0:
      if data%400==0:
        print('is a leap year')
      else:
        print('it is not a leap year')
    else:
      print('it is not a leap year')
   else:
    print('is not a leap year')    
leap_year(2000)  

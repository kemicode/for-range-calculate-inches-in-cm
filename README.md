# for-range-calculate-inches-in-cm
calculate inches in cm

#Start Program
#Get Value of inches
#Print line of output
#Set for condition in range
#Print output to 2 decimal places
#End Program


#start program

#Get Value of inches
inches = range(1,12)

#Print line of output
print('INCHES\t   CM')

#Set for condition in range
for inches in range (1,13):
    cm = (float(inches * 2.54))
    
#Print output to 2 decimal places
    print(f'{inches:6.2f}\t{cm:6.2f}')

#End Program

#Name: Jose Melquiades Escobar

#make magic numbers into named constant
userInputOne = 1
userInputTwo = 2
userInputThree = 3
userInputFour = 4
userInputFive = 5
userInputSix = 6
userInputSeven = 7
userInputEight = 8
userInputNine = 9
userInputTen = 10 


#ask user to input a number between 1 and 10
userNumber = int( input ('Enter a number between 1 and 10: '))

#display numeber and roman numeral
if userNumber < userInputOne:           #check if the number is less than 1
    print ('Error: Invalid Number')         #print error message
elif userNumber > userInputTen:         #check if the number is greater than 10
    print ('Error: Invalid Number')         #print error message
else: 
    print ('Number \t Roman Numeral')
    print ('')
    print ('1 \t I')        #display the Roman Numeral version of 1
    print ('2 \t II')       #display the Roman Numeral version of 2
    print ('3 \t III')    #display the Roman Numeral version of 3
    print ('4 \t IV')      #display the Roman Numeral version of 4
    print ('5 \t V')       #display the Roman Numeral version of 5
    print ('6 \t VI')       #display the Roman Numeral version of 6
    print ('7 \t VII')    #display the Roman Numeral version of 7
    print ('8 \t VIII')   #display the Roman Numeral version of 8
    print ('9 \t IX')      #display the Roman Numeral version of 9
    print ('10 \t X')        #display the Roman Numeral version of 10








#display only user's numer and its roman numeral counter part 
'''   
#display numeber and roman numeral
print ('')
if userNumber < userInputOne:           #check if the number is less than 1
    print ('Error: Invalid Number')         #print error message
elif userNumber > userInputTen:         #check if the number is greater than 10
    print ('Error: Invalid Number')         #print error message
elif userNumber == userInputOne:        #check if the number is 1
    print ('Number \t Roman Numeral')
    print (userInputOne, '\t I')        #display the Roman Numeral version of 1
elif userNumber == userInputTwo:        #check if the number is 2 
    print ('Number \t Roman Numeral')
    print (userInputTwo, '\t II')       #display the Roman Numeral version of 2
elif userNumber == userInputThree:      #check if the number is 3
    print ('Number \t Roman Numeral')
    print (userInputThree, '\t III')    #display the Roman Numeral version of 3
elif userNumber == userInputFour:       #check if the number is 4
    print ('Number \t Roman Numeral')
    print (userInputFour, '\t IV')      #display the Roman Numeral version of 4
elif userNumber == userInputFive:       #check if the number is 5 
    print ('Number \t Roman Numeral')
    print (userInputFive, '\t V')       #display the Roman Numeral version of 5
elif userNumber == userInputSix:        #check if the number is 6 
    print ('Number \t Roman Numeral')
    print (userInputSix, '\t VI')       #display the Roman Numeral version of 6
elif userNumber == userInputSeven:      #check if the number is 7 
    print ('Number \t Roman Numeral')
    print (userInputSeven, '\t VII')    #display the Roman Numeral version of 7
elif userNumber == userInputEight:      #check if the number is 8 
    print ('Number \t Roman Numeral')
    print (userInputEight, '\t VIII')   #display the Roman Numeral version of 8
elif userNumber == userInputNine:       #check if the number is 9 
    print ('Number \t Roman Numeral')
    print (userInputNine, '\t IX')      #display the Roman Numeral version of 9
elif userNumber == userInputTen:        #check if the number is 10
    print ('Number \t Roman Numeral')
    print (userInputTen, '\t X')        #display the Roman Numeral version of 10
'''


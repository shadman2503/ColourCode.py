# ColourCode.py
B1 = str(input("Type the 1st Colour Band: "))
B2 = str(input("Type the 2nd Colour Band: "))
B3 = str(input("Type the 3rd Colour Band: "))
B4 = str(input("Type the 4th Colour Band: "))

if B1 == 'Black' or B1 == 'black' :
    B1 = 0
elif B1 == 'Brown' or B1 == 'brown' :
    B1 = 1
elif B1 == 'Red' or B1 == 'red' :
    B1 = 2
elif B1 == 'Orange' or B1 == 'orange' :
    B1 = 3
elif B1 == 'Yellow' or B1 == 'yellow' :
    B1 = 4
elif B1 == 'Green' or B1 == 'green' :
    B1 = 5
elif B1 == 'Blue' or B1 == 'blue' :
    B1 = 6
elif B1 == 'Violet' or B1 == 'violet' :
    B1 = 7
elif B1 == 'Grey' or B1 == 'grey' :
    B1 = 8
elif B1 == 'White' or B1 == 'white' :
    B1 = 9
elif B1 == 'Gold' or B1 == 'gold' :
    B1 = 0
elif B1 == 'Silver' or B1 == 'silver' :
    B1 = 0
elif B1 == 'NO Colour' or B1 == 'no colour' :
    B1 = 0

if B2 == 'Black' or B2 == 'black' :
    B2 = 0
elif B2 == 'Brown' or B2 == 'brown' :
    B2 = 1
elif B2 == 'Red' or B2 == 'red' :
    B2 = 2
elif B2 == 'Orange' or B2 == 'orange' :
    B2 = 3
elif B2 == 'Yellow' or B2 == 'yellow' :
    B2 = 4
elif B2 == 'Green' or B2 == 'green' :
    B2 = 5
elif B2 == 'Blue' or B2 == 'blue' :
    B2 = 6
elif B2 == 'Violet' or B2 == 'voilet' :
    B2 = 7
elif B2 == 'Grey' or B2 == 'grey' :
    B2 = 8
elif B2 == 'White' or B2 == 'white' :
    B2 = 9
elif B2 == 'Gold' or B2 == 'gold' :
    B2 = 0
elif B2 == 'Silver' or B2 == 'silver' :
    B2 = 0
elif B2 == 'NO Colour' or B2 == 'no colour' :
    B2 = 0

if B3 == 'Black' or B3 == 'black' :
    B = 1
elif B3 == 'Brown' or B3 == 'brown' :
    B3 = 10
elif B3 == 'Red' or B3 == 'red' :
    B3 = 100
elif B3 == 'Orange' or B3 == 'orange' :
    B3 = 1000
elif B3 == 'Yellow' or B3 == 'yellow' :
    B3 = 10000
elif B3 == 'Green' or B3 == 'green' :
    B3 = 100000
elif B3 == 'Blue' or B3 == 'blue' :
    B3 = 1000000
elif B3 == 'Violet' or B3 == 'violet' :
    B3 = 10000000
elif B3 == 'Grey' or B3 == 'grey' :
    B3 = 100000000
elif B3 == 'White' or B3 == 'white' :
    B3 = 1000000000
elif B3 == 'Gold' or B3 == 'gold' :
    B3 = 0.1
elif B3 == 'Silver' or B3 == 'silver' :
    B3 = 0.01
elif B3 == 'NO Colour' or B3 == 'no colour' :
    B3 = 0

if B4 == 'Black' or B4 == 'black' :
    B4 = 0.2
elif B4 == 'Brown' or B4 == 'brown' :
    B4 = 0.01
elif B4 == 'Red' or B4 == 'red' :
    B4 = 0.02
elif B4 == 'Orange' or B4 == 'orange' :
    B4 = 0.03
elif B4 == 'Yellow' or B4 == 'yellow' :
    B4 = 0
elif B4 == 'Green' or B4 == 'green' :
    B4 = 0.05
elif B4 == 'Blue' or B4 == 'blue' :
    B4 = 0.06
elif B4 == 'Violet' or B4 == 'violet' :
    B4 = 0.125
elif B4 == 'Grey' or B4 == 'grey' :
    B4 = 0.3
elif B4 == 'White' or B4 == 'white' :
    B4 = 0.1
elif B4 == 'Gold' or B4 == 'gold' :
    B4 = 0.05
elif B4 == 'Silver' or B4 == 'silver' :
    B4 = 0.1
elif B4 == 'NO Colur' or B4 == 'no colour' :
    B4 = 0.2

B5 = float(f"{B1}{B2}")
B6 = float(B5*B3)
B7 = float(B6*B4)

print(f"The Maximum Value of Resistance: {B6+B7} Ohm")
print(f"The Minimum Value of Resistance: {B6-B7} Ohm")

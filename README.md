#Car Worth
###How Much is Your Car Worth?

Data about the retail price of 2005 General Motors cars can be found in car_data.csv.

### The columns are:
- Price: suggested retail price of the used 2005 GM car in excellent condition.
- Mileage: number of miles the car has been driven
- Make: manufacturer of the car such as Saturn, Pontiac, and Chevrolet
- Model: specific models for each car manufacturer such as Ion, Vibe, Cavalier
- Trim (of car): specific type of car model such as SE Sedan 4D, Quad Coupe 2D
- Type: body type such as sedan, coupe, etc.
- Cylinder: number of cylinders in the engine
- Liter: a more specific measure of engine size
- Doors: number of doors
- Cruise: indicator variable representing whether the car has cruise control (1 = cruise)
- Sound: indicator variable representing whether the car has upgraded speakers (1 = upgraded)
- Leather: indicator variable representing whether the car has leather seats (1 = leather)

###Tasks, Part 1
- Find the linear regression equation for mileage vs price.
- Chart the original data and the equation on the chart.
- Find the equation's R2 score (use the .score method) to determine whether the equation is a good fit for this data. (0.8 and greater is considered a strong correlation.)
###Tasks, Part 2
- Use mileage, cylinders, liters, doors, cruise, sound, and leather to find the linear regression equation.
- Find the equation's R2 score (use the .score method) to determine whether the equation is a good fit for this data. (0.8 and greater is considered a strong correlation.)
- Find the combination of the factors that is the best predictor for price.
###Tasks, Part 3
- Research dummy variables in scikit-learn to see how to use the make, model, and body type.
- Find the best combination of factors to predict price.

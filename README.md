# Data Types (String, Int)



## Learning Objectives - The student should be able to..

* Create strings using type annotation as such:

```swift
let fourthPlanet: String
```

* Structure the proper sentence (which will help them not only understand what it is that's going on, but help them Google things and begin to develop the proper habit of not making the assumption that they get it when they really don't) in describing the above code.

```swift
// We declared a variable named fourthPlanet that is of type String
```
* Explain the difference between type inference and type annotations. 
* Create a variable of type Int



## What the student can do at this point 

* Create variables and constants
* Use the print function to print strings to console
* Can distinguish where it's appropriate to use let over var
* A student has NOT seen the following syntax (yet) using type annotations.

```swift
let name: String
name = "Jim"

let movieTitle: String = "Wall-E"
```



## Outline / Notes

*  Build the narrative around the various planets (maybe?).
* Familiarize the student (again) with what it is they know asking them to create a constant named thirdPlanet in the playground file where the value is "Earth".
* What if we wanted create a variable named ninthPlanet and not give it a value. This type of question should make the student think a little bit before we go into the answer. Then show them this:

```swift
let ninthPlanet: String
```

* Then assign a value to ninthPlanet. Maybe include a gif here of Neil deGrasse Tyson, considering we're about to assign the value "Pluto" to ninthPlanet. Pluto is no longer a planet.

```swift
ninthPlanet = "Pluto"
```

* In the playground file, the student should have already written the following code - let thirdPlanet = "Earth". Have them do the following. Hold the option key on their keyboard and while hovering over the thirdPlanet variable, a question mark should appear. Tap on your mouse. You should see a small box appear, in that box you should see 'Declaration - let thirdPlanet: String'. Tell the student how this is been occurring behind the scenes for them all along in the prior readme's. 



* The student at this point should be asking... well which one should I use going forward and why? 

```swift
// per apples documentation
/* 
It is rare that you need to write type annotations in practice. If you provide an initial value for a constant or variable at the point that it is defined, Swift can almost always infer the type to be used for that constant or variable.
*/
```

* Writing this all in one line as follows:

```swift
let fifthPlanet: String = "Jupiter"
```

* I like the idea of having the student be asked to do the following in a playground files, completing the following sentences:

```swift
let sixthPlanet: String = "Saturn"
// sixthPlanet is a constant of type ______

let seventhPlanet = "Uranus"
// seventhPlanet is a constant of type ______
```

* Now that we understand what a String is, how can represent numbers? Have the student type the following in a playground file:

```swift
let numberOfCountriesInAfrica = 54
```

* After doing so, have them option click the variable to see what it's type is. This will be the first time they see the type Int so we might find it necessary to define it here.
* Challenge them to create something like the following (which will reintroduce string interpolation):

```swift
let sixthPlanet = "Saturn"
let numberOfMoonsOfSaturn = 62
print("There are \(numberOfMoonsOfSaturn) orbiting \(sixthPlanet).")
// prints "There are 62 moons orbiting Saturn."

```



 

<a href='https://learn.co/lessons/DataTypes' data-visibility='hidden'>View this lesson on Learn.co</a>

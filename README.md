# Loops Lab

## Instructions for lab submission

1. Fork the assignment repo
1. Clone your Fork to your machine
1. Complete the lab
1. Push your changes to your Fork
1. Submit a Pull Request back to the assignment repo
1. Paste a link to of your Fork on Canvas and submit


## Question 1

Write code that prints all the numbers from 1 to 150, **inclusive.**
let quest1 = 1...150
var answer1 = 1

while answer1 <= 150 {
print(answer1)
answer1 += 1
}
***
## Question 2

Write code that prints all the numbers from 142 to 159, **exclusive.**
var answer1 = 142

while answer1 < 159 {
print(answer1)
answer1 += 1
}

***
## Question 3

Write code that prints only the even numbers from 15 to 80, **inclusive.**

let quest3 = 15...80
var answer1 = 16

while quest3.contains (answer1) && answer1 % 2 == 0 {
print(answer1)
answer1 += 2
}

or 

let quest3 = 15...80
var answer1 = 16

while quest3.contains (answer1){
if answer1 % 2 == 0 {
print(answer1)
}
answer1 += 1
}
***
## Question 4

Write code that prints only the odd numbers from 19 to 51, **inclusive.**

let quest4 = 19...51
var answer1 = 19

while quest4.contains (answer1){
if o99iu
print(answer1)
}
answer1 += 1
}

***
## Question 5

Write code that prints all the numbers that end in a **5** from 1 to 100, **exclusive.**
let quest5 = 1...100

for idk in quest5 {
if idk % 5 == 0 && idk % 2 != 0{
print (idk)
}
}


***
## Question 6

Write code that prints all the numbers that end in a 7 from 1 to 40, **inclusive.**

let quest6 = 1...40

for i in quest6 where (i % 10 == 7){
print(i)
}

***
## Question 7

Given a range of numbers from 20 to 150 inclusive, print out all the numbers that follows these conditions:

`Numbers that are divisible by 3`

let quest7 = 20...150

for i in quest7 where (i % 3 == 0){
print(i)
}

***
## Question 8

Given a range of numbers from 20 to 150 inclusive, print out all the numbers that follows these conditions:

`Numbers that are divisible by 2 and 3`

let quest8 = 20...150

for idk in quest8 {
if idk % 3 == 0 && idk % 2 == 0{
print (idk)
}
}

***
## Question 9

Given a range of numbers from 20 to 150 inclusive, print out all the numbers that follows these conditions:

`Numbers that end with a 4`

let quest9 = 20...150

for i in quest9 where (i % 10 == 4){
print(i)
}


***
## Question 10

Given a range of numbers from 20 to 150, print out all the numbers that follows these conditions:

`Print out numbers: 31, 35, 40 to 60.`

let quest10 = 20...150

for idk in quest10 {
if idk == 31 {
print (idk)
}
if idk == 35 {
print (idk)
}
if idk == 40 {
print (idk)
}
if idk == 60 {
print (idk)
}
}

***
## Question 11

Without using Xcode, how many times will the loop below run?  Explain why.

```swift
var i = 5

while (i > 3) {
i += 1
}

// this loop will run an indefinite number of times. It will crash your computer. 

```

***
## Question 12

Change the code below to make the loop stop executing when i reaches 9.

```swift
var i = 5

while (i > 3) {
i += 1
}
```
var i = 5

while (i > 3) && (i < 10) {
i += 1
}

***
## Question 13

Change the code below to make the loop stop executing after it has run 1,000 times.

```swift
var i = 5

while (i > 3) {
i += 1
}
```
var i = 5

while (i > 3) && (i < 1005 ) {
i += 1
print (i)
}
***
## Question 14

Change the code below to make the loop stop executing after it has run 1,000 times and also make it print out the current value of i **only if i is an even number.**

```swift
var i = 5

while (i > 3) {
i += 1
}
```
var i = 5

while (i > 3) && (i < 1005 ){
if i % 2 == 0 {
print (i)
}
i += 1
}
***
## Question 15

What's the difference in syntax between the following two while loops?  Will their outputs be different?  Explain why or why not.

```swift
var i = 1
//loop one
while i <= 10 {
print("i = \(i)")
i += 1
}

//loop two
var i = 1

repeat {
print("i = \(i)")
i += 1
} while i <= 10
```
these loops behave the same.
loop 1 checks the conditional before incrementing the variable
loop 2 icrements  the variable and then checks the code for permission to loop
***
## Question 16

What's the difference between `break` and `continue`?  Give an example that demonstrates their differences.


***
## Question 17

Without using Xcode, what will the loop below print? Select all that apply.

```swift
for i in 1...10 {
if (i >= 4 && i <= 7){
continue
}
print(i)
}
```

[]1
[]2
[]3
[]8
[]9
[]10

***
## Question 18

Without using Xcode, what will the loop below print? Select all that apply.

```swift
for i in 1...10 {
if (i >= 4 && i <= 7){
break
}
print(i)
}
```

[]1
[]2
[]3


***
## Question 19

Without using Xcode, what will the loop below print?  Explain below.

```swift
outerloop: for x in 1...3 {
innerloop: for y in 1...3 {
if y == 2{
continue outerloop
}
print("x = \(x), y = \(y)")
}
}
```
x = 1, y = 1
x = 2, y = 1
x = 3, y = 1

the code runs the inner loop for each of the intergers in the outer loop. when the loops gets to integer two in the inner loop, it restarts the outerloop loop without printing the remaining integers of y.


***
## Question 20

Write code that prints out all the points in the area bounded by (0,0), (10,0), (0,10) and (10,10) **where** x and y are both integers.

outerloop: for x in 0...10 {
innerloop: for y in 0...10 {
print("x = \(x), y = \(y)")
}
}

***
## Question 21

Write code that prints out all the points in the area bounded by (0,0), (10,0), (0,10) and (10,10) **where** the difference of x and y is at least 5, and x and y are both integers.


outerloop: for x in 0...10 {
innerloop: for y in 0...10 {
if x - y == 5 {
print("x = \(x), y = \(y)")
}
}
}

***
## Question 22

Print the first `N` square numbers. A **square number**, also called perfect square, is an integer that is obtained by squaring some other integer; in other words, it is the product of some integer with itself (ex. 1 = 1*1, 4 = 2 * 2, 9 = 3* 3 …).

Example:
Input: `var N = 5`

Output:
```swift
1
4
9
16
25
```


var N = 1

while N <= 5 {
print (N * N)
N += 1
}


***
## Question 23

Given an integer N draw a square of N x N asterisks. Look at the examples.

Example 1:
Input: `var N = 2`

Output:
```swift
**
**
```

Example 2:
Input: `var N = 3`

Output:
```swift
***
***
***
```

var N = 1

while N <= 3 {
print ("***" )
N += 1
}

Hint 1
Try printing a single line of * first.

Hint 2
You can use print("") to print an empty line.

***


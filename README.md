# What I Learned In Week 4

## *Boolean*
The data type that can only have two values: `True` or `False`. It used to compare values.

    Operators that can be used with booleans:
    === "equal to and equal type" compares what is on the left of the operator to the right.
    && "and" operator is used if statement on the left and on the right of operator need to pass.
    || "or" operator is used if either of statements is true.
    ! "bang" operator is used to change another operator to opposite value.

## *If/Else Statement*
These statements are used to create conditions.

    if (!isNaN(num)){
        return "That's a number!"
    } else if (isNaN(num)) {
        return "That's not a number!"
    }
    else {
        return "I don't know what's going on!"
    }

In the example above we are passing 'num' and checking if it is a number using operator !isNaN (not not a number). And if passed value is `true` we return "That's a number!" and if it's `false` value will be checked by the next `if` statement. If the value doesn't return `true` to any `if` statement, `else` will be used.

## *Ternary*
The operator that takes 3 arguments at the same time. Can be used as a replacement for a simple if/else statement.

    result = !isNaN(x)  ? 'Yes' : 'No';

First argument is a condition. Second argument is the result if passed value returns true. Third argument is the result if passed value returns false. 

## *Iffy Project*
I chose to make a bill splitting node app. 
The project that seemed to be easy to make introduced interesting challenges. I had to figure out why the user input wasn't calculated. Turns out that any input turns into a string. I've used `parseFloat` to change input to decimal value. 

## *Human Resource Machine*
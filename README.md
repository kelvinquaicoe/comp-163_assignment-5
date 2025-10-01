# comp-163_assignment-5
assignment
#Why you chose each loop type for each challenge 
In challenge 1, I used a while loop as there was no certain number of iterations as only a certain condition needed to be met. That being must not be equal to 1

In challenge 2, a for loop was used as the number of iterations was from 2 to n-1. n being positive_num.

In challenge 3, for loops were used for no particular reading as while loops would also work in this scenario as I just needed to find a number from a range. eg. (while i in column:)

#How your solutions work 
#Challenge 1
first took an input on n (current_number). A count was set to zero to count the number of iterations that would occur. A while loop was used on condition that n not be 1. If not then if n%2 was 0, then current number would be divided be two using // as to not leave as float. The loop would run till the number is 1.Then the else conditions were also implemented. Then the count or steps and number sequence is outputted.

#Challenge 2
Input is taken as a positive integer.
If the number was less than 2, an error message is displayed.
Otherwise, divisors are tested from 2 up to n-1. If any divisor evenly divides the number, it is not prime. 
If no divisors are found, the number is prime. loop is run till all the nubers in the range are done.

#Challenge 3
Ranges for rows and columns (1 to 10) are defined usiong range(1,11).Nested for loops print products of row × column.
Formatting (:4) keeps numbers aligned properly. end='' was used to move to a different line.

#Any AI assistance used
Ai was used to find bugs eg. in scenario 1:
    (else:
        current_number = (current_number*3)+1
    sequence.append(current_number)
    step_count += 1)
I did not use the proper indentation and AI helped me identify this mistake.
AI helped me in Identifying technical errors like using = instaed of ==

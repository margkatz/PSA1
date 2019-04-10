Name: Margaux Katz
  Login: cs8bsp19ir
  Date: 8 April 2019
  
  ## "Debugging Code"

  Errors: cannot find symbol - Array not string
  Incorrect: for (int = 0; i < array.length(); i++)
  Fix: for (i = 0; i < array.length; i++)
  Explanation: Correction starts at the index < array.length
  rather than index < array.length() because we are
 passing through an array not a string.
  //
  
 Error: incompatible types- int[] cannot be converted into boolean
 Incorrect: if (array = null)
 Fix: if (array == null)
 Explanation: Correction is (array == null) rather than
 (array = null) because it returns true only if the two references
 point to the array.
 //

Error: runtime error- Array out of bounds
Incorrect: if (i = 0; i <= array.length; i++)
Fix: if (i =0; i < array.length; i++)
 Explanation: Correction starts at the index
 is less than array.length rather than equals to or less than.
//

 Error: logic error- wrong symbol
  Incorrect: return max + min;
 32 Fix: return max - min;
 33 Explanation: Return the max value - the min value
 34 instead of adding the two together.
 35 
 36 Error: logic error- double average assigned to wrong value
 37 Incorrect: return ( sum / (array.length):
 38 Correct: return ((double)sum / array.length);
 39 Explanation: assign double to sum so a more accurate
 40 average value is printed

Error: runtime error- Array copy printed incorrectly
Incorrect: array[i] = result[i]
Fix: result[i] = array[i];
Explanation: the array[i] needs to be on the right side
of the equal sign because it gets assigned to the value on the left.
 Error:

## "Styling Code"
Rule Violated: 10- Write header comments (javadoc) for each method
Incorrect: // Print all the numbers in the input Array/
Fix: /Print all the numbers in the input array
 @param array input array to print array
 @return the newly printed array//
 Explanation: to describe the method functionality in more depth

 Rule Violated: 7 - magic number
 Incorrect: for (int i = 0; i < array.length / 2; i++)
 Fix: int even = 2;
 for (int i = 0; i < array.length / 2; i++)
 Explanation: defining the magic number to make it
 more descriptive.
 
 Rule Violated: 5- proper identing
 Incorrect: }
 }
         }
 Fix: use gg=G command to properly indent 140 lines
 Explanation: identing makes so the code is
 understandable and clear. 
 
 ## More Questions
 
 It is important to write comments in the code
 because then we can better understand the method's purpose
 and expected output. We can clearly identify the method's
 functionality.
 
 The given in-line comment is not ideal because it is
 redudent because it says initialize int. Instead you
 might say //set initial length to BLANK and iterate through
 array and increment when BLANK//. Be more straight forward
  
 ## Testing hammingDecode

 op1: Method returns original String and doesn't actually decode anything.
 op2:
 op3:
 op4:
~           

# Camel-Banana-Problem-
Aim-To print the maximum number of bananas that can be transferred to the destination using only camel

Problem statement: A person has 3000 bananas and a camel. The person wants to transport the maximum number of bananas to a destination which is 1000 KMs away, using only the camel as a mode of transportation. The camel cannot carry more than 1000 bananas at a time and eats a banana every km it travels. What is the maximum number of bananas that can be transferred to the destination using only camel (no other mode of transportation is allowed).

Procedure-

Since it is not possible to transport the bananas in a single run, the idea could be to use some checkpoints between the starting point and the destination where we will leave the bananas.
As we have 3000 bananas we have to take 3 forward and two backward trips to transfer all the bananas to a checkpoint(say, A). Now we walk with 1000 bananas and walk towards A.
Also Camel can’t move more than 500 miles forward and then backward due to its load capacity. There can be more than 1 checkpoint.
There would be one or more than one checkpoint. We are breaking each section of the checkpoint in the sections of length one.
At each subsequent mile, we are subtracting the no. of bananas lost in travelling each mile from the total no. of bananas. To calculate the total bananas left after 1 mile we use another variable start.

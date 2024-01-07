<!-- Okay so the thing is that we have to find the nth highest salary -->
<h2>How to Procees></h1>
<p>
Step-1 ) We would need to drop the duplicates . Since nth highest doesnt include the duplicate values 
<br>
Step-2) Now after dropping duplicates from salary column , there can be some values which will bcome Null
<br>
Step -3) So we have to drop those null Values now!
<br>
Step-4) Now , we would need to sort the values since if they are sorted then we can easily determine which value is larger or which is smaller
<br>
Step-5) Now There can be 2 things if N is negative return NULL{This condition can also be written at the first step}
<br>
2nd one can be if N> len(employee) that means we to find say 4th largest value and total lenght is 3 which is impractical
so return null
<br>
Step-6
Now finally return the nth largest salary using Iloc /Loc it would be in the (len-n)cell
</p>
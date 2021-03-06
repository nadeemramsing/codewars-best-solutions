# codewars-best-solutions
From which new tricks and lessons can be learnt.

# JavaScript
- Using RegExp's Capturing Groups to manipulate strings
- Third solution is better / simpler / less bug-prone (according to comments)
- Groups:
    1. First character of word
    2. Remaining characters of word
- \b => Word boundary (used to match word; e.g: /\b(\w*)\b/g)
- \w => Any alphanumeric character including the underscore; equivalent to [A-Za-z0-9_]
- <a href="https://www.codewars.com/kata/520b9d2ad5c005041100000f">Link</a>

![](images/chrome_2018-05-08_11-40-45.png)

----------

- Calling functions that accepts multiple arguments using an Array
- <a href="https://www.codewars.com/kata/remove-the-minimum">Link</a>

![](images/chrome_2018-05-08_12-05-57.png)

----------

- Using RegExp's Capturing Groups to manipulate strings
- Own solution is pretty interesting and simple as well.
- String interpolation used to separate last item of array.
- <a href="https://www.codewars.com/kata/format-a-string-of-names-like-bart-lisa-and-maggie">Link</a>

![](images/chrome_2018-05-08_12-13-52.png)

----------

- Using Array Destructuring for better readability
- Avoids annoying array[n]
- <a href="https://www.codewars.com/kata/categorize-new-member">Link</a>

![](images/chrome_2018-05-08_13-41-16.png)

# Python
- Vowel Count
    1) Using Regex
    2) Using List Comprehension: an elegant way to define and create lists based on existing lists
- <a href="https://www.codewars.com/kata/54ff3102c1bad923760001f3/python">Link</a>

![](images/vowelcount1.png)

- Lambda function: Small anonymous function

![](images/vowelcount2.png)

----------

- Mapping a List
    1) Using List Comprehension
    2) Using map
- <a href="https://www.codewars.com/kata/57f781872e3d8ca2a000007e">Link</a>

![](images/listwithoutamap.png)

----------

- Abbreviating a two-word name
    1) Using List Destructuring
    2) Using List Comprehension
- <a href="https://www.codewars.com/kata/57eadb7ecd143f4c9c0000a3">Link</a>

![](images/abbreviateatwowordname.png)

# C#
- Check if an array contains a value
    1) Using namespace System.Linq
    2) Using namespace System
- Tips: 
    - *Classes* can be made available using **using static** directive 
        - e.g. **using static System.Linq.Enumerable**
    - *Namespace aliases* can be used to avoid name clashes 
        - e.g. **using Linq=System.Linq**
- <a href="https://www.codewars.com/kata/57cc975ed542d3148f00015b">Link</a>

![](images/arraycontains.png)
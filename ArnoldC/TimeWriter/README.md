# Time Writer

## Original Brief
I've decided I want my computer to keep me updated on the time so I'm never late again. I want a talking clock takes a 24-hour time and translates it into words.

Input Description
An hour (0-23) followed by a colon followed by the minute (0-59).
Output Description
The time in words, using 12-hour format followed by am or pm.

Sample Input data:
- 00:00
- 01:30
- 12:05
- 14:01
- 20:29
- 21:00

Sample Output data
- It's twelve am
- It's one thirty am
- It's twelve oh five pm
- It's two oh one pm
- It's eight twenty nine pm
- It's nine pm

## Programming Language
ArnoldC (https://lhartikk.github.io/ArnoldC/)

## Language Constraints
As ArnoldC can only store and manipulate boolean and integer variables, the input format can only be a three- or four-digit integer:
- 0000
- 130
- 1205
- 1401
- 2029
- 2100
Additionally, there is no way to print to the console without a new line, so the output is spread; one word per line.

ECE281_CE1
==========
# Computer Exercise 1

## Truth Table

|   A   |   B   |   C   |   F   |
| ------|------ |-------|-------|
| 0     | 0     | 0     | 0     |
| 0     | 0     | 1     | 0     |
| 0     | 1     | 0     | 0     |
| 0     | 1     | 1     | 1     |
| 1     | 0     | 0     | 1     |
| 1     | 0     | 1     | 1     |
| 1     | 1     | 0     | 0     |
| 1     | 1     | 1     | 1     |

## Circuit Output

![alt tag](https://github.com/seanbapty/ECE281_CE1/blob/master/CE_output_picture.JPG)

## Analysis

Based on the given circuit, the output (F) should equal 1 for A!B + BC. Given this information,
the output makes sense yielding 1 four times for !ABC, A!B!C, A!BC, and ABC. All of these satisfy
either A!B OR BC.

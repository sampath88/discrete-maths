# CMU Discrete Mathematics 2/1
https://www.youtube.com/live/0K540qqyJJU?si=DV5c16lA3-Y2IqnD


# How many 4 digit numbers are there?

![Alt text](image-1.png)

- each place can have 10 choices, from 0 to 9

# How many 4 digit nubmers are there? where the first digit is non-zero.

![Alt text](image-2.png)

- ecah place can have 10 choices, except the first place.
- the first place can not have a zero, remaining 1...9= 9 choices.
  ![Alt text](image-3.png)

# How many 4 digit numbers with 1st non-zero digit and no two same digits next to each other?

![Alt text](image-4.png)

- The first place will have 9 choices, because of non-zero digit.
- The remaining will have 10 choices, but to avoid same digit next to each other, will only have 9 choices.

### Note: what if we start from right to left direction?
![Alt text](image-5.png)

#### Conditions
1. Start with non-zero digit.
2. No two digits next to each other are same.

# How many 4 digit numbers are even, along with above conditions?
![Alt text](image-6.png)

### > let's solve the same problem for one and two digit numbers.
![Alt text](image-7.png)
- if we observe, the total single digit numbers are 10, in them  4 even and 5 odd.(with above conditions)
- similarly for two digit numbers, the total two digit numbers are 90, in them 45 even and 45 odd.
- if we remove the same digits there will be 41 even and 40 odd.

![Alt text](image-8.png)

# Final soultion
![Alt text](image-9.png)
- if we observe carefully, there is a pattern.
- we can find total numbers by 9<sup>n, where n is number of digits
- the total number of n digit numbers divided by 2 to the rounding off.
- if we look closely, +1 is adding alternatively, so we can resolve this by adding (-1)<sup>n.